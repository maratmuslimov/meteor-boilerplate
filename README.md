## Synopsis

This is my meteor boiler plate.
Meteor with the following packages:
    accounts-password            Password support for accounts
    anti:fake                    Random text and data generator
    autopublish                  Publish the entire database to all clients
    ian:accounts-ui-bootstrap-3  * Bootstrap-styled accounts-ui with multi-language support.
    less                         The dynamic stylesheet language
    meteor-platform              Include a standard set of Meteor packages in your ap

The "insecure" package was removed and the basic tree folder is as followed:

├── client
│   ├── helpers
│   ├── lib
│   ├── stylesheets
│   │   └── vendors
│   │       ├── kube
│   │       │   ├── css
│   │       │   ├── js
│   │       │   └── less
│   │       └── mrmrs-color
│   │           └── less
│   └── templates
│       ├── application
│       └── includes
├── lib
│   └── collections
├── package
├── public

## Motivation

As I don't like to redo the same steps over and over when starting a meteor
project, here is the basic of what I need.

## Installation

Just clone it and start developing.
Best to have meteor installed before hand.

## Contributors

Momday

## License
Apache
