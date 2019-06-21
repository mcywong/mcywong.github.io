---
layout: post
title: Database
subtitle: Designing the Schema
image: /img/dfoLogoCropped.jpg
tags: [Hell Logger, Databases]
---
### Defining the Schema
For relational databases it is important to design the schema or rules applied on the data properly.

Heres a quick sketch of the schema design that I will use:

![databaseSchema](/img/schema.PNG)

Underlined in red are the primary keys Account.username, Character.name, and HellRun.ID.

Since the username and character names in the game must be unique, they make perfect primary keys.

One account can have multiple characters and each character can have multiple hell runs logged.

### Design Tradeoffs
Hell runs are currently designed to be compiled where one row represents all the runs done in a day. Alternatively, the runs could be logged individually. Grouping the data by date reduces the amount of rows required to be stored. This is advantagous when there is a limited amount of space in free tier database services.