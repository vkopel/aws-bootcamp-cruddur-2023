# Week 0 — Billing and Architecture

## Required Homework/Tasks

### Install AWS CLI

I was not able to use Gitpod or Github Codespaces due to browser issues.
So I decided to use local environment.

In order to prove that I am able to use the AWS CLI.
I am providing the instructions I used for my configuration of my local machine on windows.

I did the following steps to install AWS CLI.

I install the AWS CLI via command in **Command Prompt**:

```
curl "https://s3.amazonaws.com/aws-cli/awscli-bundle.zip" -o "awscli-bundle.zip"
unzip awscli-bundle.zip
sudo ./awscli-bundle/install -i /usr/local/aws -b /usr/local/bin/aws
```

I attempt to run the command by typing in `aws`

```
C:\Users\Valdano>aws
'aws' is not recognized as an internal or external command,
operable program or batch file.
```

### Create a Budget

I created my own Budget for $1 because I cannot afford any kind of spend.

![Image of The Budget Alarm I Created](/journal/assets/billing-alarm.png)

### Recreate Logical Architectural Design 

![Cruddur Logical Design](/journal/assets/logical-architecture-recreation-diagram.png)

[Lucid Charts Share Link](https://lucid.app/lucidchart/3b8593fc-1f1c-4c80-bfdf-f0a7b767bb9a/edit?viewport_loc=-393%2C-2539%2C2798%2C1282%2C0_0&invitationId=inv_a6ce0412-00a6-40a8-82ce-bef798036b4c)
