# Coba Code Challenge

This README will explain the code challenge to join the Coba Development Team. Make sure you read all of this
file before starting with the code.

## Requirements

- Unix base system(OSX or Ubuntu) or Windows with WSL.
- Rails 6 or higher
- GitHub account to create the repository for later review

### Bonus requirements

You can go with:
- Docker latest version
	- [Docker for mac](https://docs.docker.com/docker-for-mac/install/)
	- [Docker for Ubuntu](https://docs.docker.com/install/linux/docker-ce/ubuntu/#install-docker-ce)
  - [Docker for WSL](https://docs.docker.com/desktop/windows/wsl/)
- Docker Compose lastest version
	- [Install Docker Compose](https://docs.docker.com/docker-for-mac/install/)
- [Docker account](https://hub.docker.com/signup)

## Description

For this challenge you are a developer at an ecommerce company, where the manager handed you a [CSV file](Superstore_sales.csv) with a list of products
and you have to **migrate all of the information in there to a relational model**. In this we are expecting you to:

- Identify the models and create them through the terminal, along with their migrations
- Views & Controllers are not being evaluated, so you can ignore that
- You can use the seed file for the migration, and if you use service objects, those are **bonus points**
- Don't be afraid to use enums, or any special field on the database that might be useful, it is better to take risks

## Objectives

- [ ] Provide unit tests for all the models or services you use

**Notes:**

- For the testing suite, you are free to choose the tool of your preference. For example, RSpec, Minitest, Capybara.

## Constraints

- Follow the workflow you currently use, for example one branch per feature, or atomic commits
- Work for up to **three hours** and deliver the code as is
- There are no restrictions on the gems you can use

## Schedule

**You have 1 week to deliver the application up to the point where you got.**

We are happy to help you building the challenge, you can always ask for help to any of the developers listed below:

- [Abraham Kuri](mailto:kuri@coba.ai)

## Delivery

Once you are done with the challenge or the week is over:

- Make sure you send an email to [kuri@coba.ai](mailto:kuri@coba.ai) with the link of your Github repository and the running application

## Review

To review the challenge we are going to check:

-	The models you identified during the process
- The associations you made between models
- The tests you performed
- The migration script
