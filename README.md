# Introduction

Worked through tutorial concerning Python REST APIs with Flask, Connexion and SQLAlchemy via [realpython.com](www.realpython.com), specifically [this](https://realpython.com/flask-connexion-rest-api/) tutorial.

# Misc

**Action**|**HTTP Verb**|**Description**
:-----:|:-----:|:-----:
Create|POST|Create a new, unique thing
Read|GET|Read the information about a thing or collection of things
Update|PUT|Update the information about an existing thing
Delete|DELETE|Delete a thing

**Action**|**HTTP Verb**|**URL Path**|**Description**
:-----:|:-----:|:-----:|:-----:
Create|POST|/api/people|Defines a unique URL to create a new person
Read|GET|/api/people|Defines a unique URL to read a collection of people
Read|GET|/api/people/Farrell|Defines a unique URL to read a particular person in the people collection
Update|PUT|/api/people/Farrell|Defines a unique URL to update an existing order
Delete|DELETE|/api/orders/Farrell|Defines a unique URL to delete an existing person