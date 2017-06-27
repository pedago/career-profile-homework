# Smartly Backend Homework

At Smartly we have a REST API that supports fetching and making updates to the various records in our system.  The purpose of this coding assignment is to design and develop a working API for a simplified version of a Smartly user’s career profile.

## Overview

Develop a database schema and API that can be used to create, fetch, and update a simplified version of a Smartly user’s career profile.

### Data Model

The career profile should include the following:

 - [ ] A reference to a specific user
 - [ ] A “personal fact” about the user 
 - [ ] Whether the user is open to working remotely
 - [ ] A list of jobs the user has had, each with the following information:
  - [ ] The company’s name
  - [ ] The user’s job title
  - [ ] The date range during which the user worked at this job
  - [ ] A list of responsibilities that the user had at this job

### API

The API should...

 - [ ] require authentication (more on this below)
 - [ ] accept a JSON-formatted career profile and create new records in the database or update existing ones, as necessary
 - [ ] allow a user to fetch and update his own career profile
 - [ ] allow an admin user to fetch and update any career profile
 - [ ] not allow a normal user (non-admin) to fetch or update someone else's profile
 - [ ] return responses with appropriate HTTP response codes for success and failure conditions

### Authentication

Authentication should...

 - [ ] allow for identifying the role or user associated with the requests to support admin/non-admin permissions described above
 - [ ] assume all requests are delivered over HTTPS
 - [ ] be sufficient to implement this toy homework assignment; it need not be a comprehensive solution.

Note that your authentication implementation may use 3rd party libraries, if you wish.

## Deliverables

Upon successful completion of this project the candidate should provide:

 - All server-side code, database schema, configuration and architectural details necessary for a competent engineer to be able to setup a running instance of the service
 - Unit and/or functional tests
 - Instructions for interacting with the API, such as via 3rd party tool, the command line, or even simple web UI.

## Additional Notes and Rules

 - You may consult any books, websites, or other references you wish.
 - You may use any third-party tools, libraries, frameworks, etc. that you wish.
 - The result should represent the caliber of work we can expect from you so please do the work yourself.
