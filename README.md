# snapshotalyzer-3000

Demo project to manage AWS EC2 instances snapshots

## About

This project is a demo, and uses boto3 to manage AWS EC2 instances snapshots.

## Configuring

shotty uses the configuration file created by the AWS cli. e.g.

`aws configure --profile shotty`

## Running

`pipenv run "python shotty/shotty.py" ou python shotty/shotty.py <command> <subcommand> <--project=PROJECT>"`

	*command* is instances, volumes or snapshots
	*subcommand* depend on command (list start stop create)
	*project* is optional