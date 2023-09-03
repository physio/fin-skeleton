# fin-skeleton
A simply skeleton if you want to start to develop in stock world.

The idea is to give support to those who are not very familiar with python, but who want to start with something usually. The advanced python developer definitely doesn't need this project for his work.

I want to introduce you to a very trivial project, but one that could be useful for anyone who decides to develop code to create software that allows you to play on the stock market.
I'm trying to prepare all the useful tools of the trade to be able to concentrate on your business, avoiding wasting time with those parts of the code that add little value to your work, but are necessary to work.

The main goal is to use the least number of external libraries, in order to be easier to maintain.

If you decide to collaborate I'm very happy, please fork the project.

I hope they can be useful for your work.

## The Idea

The idea is to write software that performs at least these simple functions:

- periodically performs one or more requests to an API service on the value of a specific share
- saves its historical value on a database

## Getting Started

The first step to perform is to clone the project. Being a skeleton of a project, I advise you to rename the root folder of the project.

Another thing I suggest you do is to delete the .git folder and re-initialize your git project (git init). This has the advantage of being able to abstract you from the skeleton, but the disadvantage of missing out on future updates. Evaluate what could be the best solution for your job.

```sh
git clone git@github.com:physio/fin-skeleton.git
rm fin-skeleton myProjectName
cd myProjectName
```

## Folder Structure

The structure of the project is inspired by the dictates of the DDD.

I probably did something wrong, but please let me know so I can correct it. Or if you prefer, correct it yourself.

## Database

to save the data of a share title, it is necessary to choose the database on which to support your work. I have seen Excel sheets used many times, but we want to do something more. So I thought about creating a connection to SQLlite. However, I have created a simple repository on it, so that if you decide to change the type of database, it will be easy for you to make the necessary changes.

In the root of the project I created a simple .sql file which is used to populate your database with the tables needed to run the project correctly.
