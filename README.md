La Fourchette 2012
==================

"La Fourchette" is an application that manages the relation between clients, plates and Chefs in a Restaurant environment.
Clients enter in the restaurant, can book plates from the table and can see (status) in real time (Long Polling) the preparation.

The project is composed of 2 majors Layers:

- A Ruby-On-Rails Application: RESTful service from clients, Html-Based client with Long-Polling for Chefs and waiters.
- A Backbone.js Application using REST for Clients.

The Client application, using Backbone.js, is written in CoffeeScript.

The project is fully workable, but has been developed only for SUPINFO University purposes, and didn’t have expectations such as:

- Strong Database Design (Relational + Non-Relational)

- Continuous Integration Plan (Tests and Deployment)
