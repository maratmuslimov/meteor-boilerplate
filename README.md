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

<pre>
├── LICENSE
├── README.md
├── client
│   ├── helpers
│   ├── lib
│   ├── stylesheets
│   │   └── vendors
│   │       ├── kube
│   │       │   ├── css
│   │       │   ├── js
│   │       │   └── less
│   │       ├── main.less
│   │       └── mrmrs-colors
│   │           └── less
│   └── templates
│       ├── application
│       │   ├── layout.css
│       │   ├── layout.html
│       │   └── layout.js
│       └── includes
├── lib
│   ├── collections
│   ├── permissions.js
│   └── router.js
├── package
├── public
│   └── images
└── server
    ├── fixtures.js
    └── publications.js
</pre>

## Motivation

As I don't like to redo the same steps over and over when starting a meteor
project, here is the basic of what I need.

## Installation

Just clone it and start developing.
Best to have meteor installed before hand.

## Contributors

Momday

## License
MIT
