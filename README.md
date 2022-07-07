## Challenge 13 E-Commerce Back End

## Table of Contents

- [User Story](#user-story)
- [Description](#description)
- [Usage](#usage)
- [Requirements](#requirements)
- [Application](#application)
- [Questions](#questions)

## User Story

- AS A manager at an internet retail company
- I WANT a back end for my e-commerce website that uses the latest technologies
- SO THAT my company can compete with other e-commerce companies

## Description

This application is the back end for an e-commerce site using Express.js API and Sequelize to interact with a MySQL database.

## Usage

- Clone the repository into your directory
- Open the command line in this directory
- Install 'npm install'
- Invoke the command 'npm start'
- In mysql create the database using 'source db/schema.sql'
- Seed the database using 'npm run seed'
- Use insomnia to test the CRUD Operations

## Requirements

- GIVEN a functional Express.js API
- WHEN I add my database name, MySQL username, and MySQL password to an environment variable file
- THEN I am able to connect to a database using Sequelize
- WHEN I enter schema and seed commands
- THEN a development database is created and is seeded with test data
- WHEN I enter the command to invoke the application
- THEN my server is started and the Sequelize models are synced to the MySQL database
- WHEN I open API GET routes in Insomnia for categories, products, or tags
- THEN the data for each of these routes is displayed in a formatted JSON
- WHEN I test API POST, PUT, and DELETE routes in Insomnia
- THEN I am able to successfully create, update, and delete data in my database

## Application

[Link to video walkthrough](https://drive.google.com/file/d/1eBDYQPnt2w41vAmReEK7hCtzm8-RLEdy/view?usp=sharing)

## Questions?

For any questions, please email gilinamcbride@gmail.com, or visit any other projects on [Github](github.com/gilinamcbride).
