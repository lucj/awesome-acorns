# Postgres

This Acorn provides a Postgres database as an Acorn Service. This Acorn can be used to create a database for your application during development. It runs a single Postgres container which can be backed by a persistent volume is the *persistency* argument is set to *true*. 

A default user is automatically generated during the creation process.