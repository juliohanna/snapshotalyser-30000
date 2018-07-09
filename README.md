# snapshotalyser-30000

demo project to manage AWS EC2 instances snapshots

## About

This project is a demo , and uses boto3 to manage AWS EC2 instances snapshots.

## Configuring

Shotty uses the Configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python "shotty/shotty.py" <command> <subcommand> <--project=PROJECT>`

*command* is instances, volumes, or snapshots
*subcommand* - depends on command
*project* is optional
