# snapshotalyzer-3000

Demo project to manager AWS

## About

This project is a demo, and uses boto3 to manage AWS CE2 instance snapshots.


## Configuring

shotty uses the configuration fgile created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run python shotty/shotty.py <command> <--project=PROJECT>`

*commands* are list, start or stop
*project* optional
