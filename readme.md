# Flyway Desktop Demo

This repo exists to help demo the Flyway Desktop applicationa and Flyway Enterprise subscription from Redgate. This contains a series of folders designed to help showcase how Flyway works across various platforms to build and deploy code.

Each sub folder has a description of the process used for that particular platform and the automation tools that are used.

## Application Description

The application that I am building here is a speaking CV tracker, where I can load in data about the events at which I speak and deliver content. The idea is that databases exist to keep track of the events, with live updates added as I deliver talks based on this system.

## Platforms

The main platforms that I am using for this are these:

- SQL Server
- Oracle Express Edition
- PostgreSQL
- MySQL

The way that I have set up each of these is described below. The intention is to use as similar a set of database structures for each platform as possible.

### SQL Server

SQL Server is the primary platform I use and the first one that I set up to handle this.