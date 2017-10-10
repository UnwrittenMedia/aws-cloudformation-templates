# Authorize an account to create stacks

## Introduction

This is a simple (full-permission) way of providing a single account permission to create stacks from the Stack Set tool.

To create stacksets in an account, you need some IAM roles, as well as to specify which account will host the stack set.

This template allows for all to be a single account, or for another account to create stacks in this one.
You may also create multiple instances of this template to allow multiple accounts the permission.


## IAM Policies

This template primarily deals with IAM policies. So, you will need to check the relevant box every deploy.


## Create Stack

It should not matter which region you create the stack in. IAM policies are more or less global.

