# Secure your brand new AWS account

This repo contains some very basic security configurations that can be applied to a new AWS account that is not a part of an AWS Organization. Some of these configurations are FREE, some are not (though they are very cheap and are recommended). They are separated into different parts, so you can apply just the free ones if that's what you want.

This is designed for people who don't (yet) know what they're doing and don't want to learn (yet).
It is divided into six parts:
- 1: A CloudFormation template that you can apply with just one click, which will apply some FREE security configurations (listed in another section)
- 2: A CloudFormation template that you can apply with just one click, which will apply some NOT FREE security configurations (listed in another section)
- 3: Another CloudFormation template that will ask you for some input values and will apply some more FREE security configurations (listed in another section)
- 4: Another CloudFormation template that will ask you for some input values and will apply some more NOT FREE security configurations (listed in another section)
- 5: A list of manual steps that cannot be automated and that you will want to perform to apply some more security configurations (some are marked FREE, some are marked NOT FREE).
- 6: A list of things that you should read, to better understand how to use your AWS account in a secure way.

The idea is to group together as many security configurations as possible (that are relevant to a single account) and let a person who is new to AWS apply these configurations to the AWS account they just created in an easy way that requires no knowledge of how this stuff even works.
The reasoning behind this is that people create AWS accounts to start trying some stuff, or to do a workshop, and they don't want to dedicate some time (yet) to understand security in AWS. More often than not, these people will continue using their AWS accounts for similar learning purposes and only after months or even years of getting into AWS will they learn how to secure an AWS account (or better yet, an Organization) and realize how exposed they were.

These security configurations are NOT perfect, they are NOT the best practices and will NOT offer production-grade security, but they will leave brand new AWS users slightly less exposed, in just a couple of clicks and with zero knowledge required. This is meant to be a starting point, and while it will include some information and learning resources, they are not necessary to apply these configurations (actually, you are encouraged to first apply them and then read up some more). Ideally, eventually, you will learn enough about security in AWS to build a more secure setup (tip: look into Organizations and using multiple accounts).

## 1: Completely automated security configurations (FREE)

Implemented:

Coming soon:
- Enable AWS CloudTrail
- Create a strong password policy for IAM Users

## 1: Completely automated security configurations (NOT FREE)

Implemented:

Coming soon:
- Delete the root user access keys

## 2: Automated security configurations that require your input (FREE)

Implemented:

Coming soon:
- Create IAM User with Administrator Access
- Billing alerts

## 2: Automated security configurations that require your input (NOT FREE)

Implemented:

Coming soon:
- Failed login attempt notification

## 3: Security configurations that you will need to apply manually

Implemented:

Coming soon:
- Set a secure password for root user (FREE)
- Configure MFA for root user (FREE except for the cost of the MFA device)
- Configure MFA for IAM Users with Administrator Access (FREE except for the cost of the MFA device)
- Enable Amazon GuardDuty (NOT FREE)
