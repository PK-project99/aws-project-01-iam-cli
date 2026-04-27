# Project 1: IAM + CLI Setup

## What I built
Secured the AWS root account with MFA, created a least-privilege
IAM admin user (Puneet-admin), generated CLI access keys, and
configured the AWS CLI to authenticate programmatically.

## What I learned
- Root account should never be used for day-to-day work
- IAM users with AdministratorAccess are the right starting point
  for personal learning accounts
- aws sts get-caller-identity is the fastest way to verify CLI auth
