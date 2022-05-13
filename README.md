# Secure your brand new AWS account

This repo contains some very basic security configurations that can be applied to a new AWS account that is not a part of an AWS Organization.

This is designed for people who don't know (yet) what they're doing and don't want to learn (yet).
It is divided into three parts:
- 1: A CloudFormation template that you can apply with just one click, which will apply some security configurations (listed in another section)
- 2: Another CloudFormation template that will ask you for some input values and will apply some more security configurations (listed in another section)
- 3: A list of manual steps that cannot be automated and that you will want to perform to apply some more security configurations.

The idea is to group together as many security configurations as possible (that are relevant to a single account) and let a person who is new to AWS apply these configurations to the AWS account they just created in an easy way that requires no knowledge of how this stuff even works.
The reasoning behind this is that people create AWS accounts to start trying some stuff, or to do a workshop, and they don't want to dedicate some time (yet) to understand security in AWS. More often than not, these people will continue using their AWS accounts for similar learning purposes and only after months or even years of getting into AWS will they learn how to secure an AWS account (or better yet, an Organization) and realize how exposed they were.

These security configurations are NOT perfect, they are NOT the best practices and will NOT offer production-grade security, but they will leave brand new AWS users slightly less exposed, in just a couple of clicks and with zero knowledge required. This is meant to be a starting point, and while it will include some information and learning resources, they are not necessary to apply these configurations (actually, you are encouraged to first apply them and then read up some more). Ideally, eventually, you will learn enough about security in AWS to build a more secure setup (tip: look into Organizations and using multiple accounts).

## 1: Completely automated security configurations

## 2: Automated security configurations that require your input

## 3: Security configurations that you will need to apply manually
