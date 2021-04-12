# Introduction

This repository hosts the source code of http://www.midica.org/ &mdash; the documentation website for Midica, the Music programming and processing tool:
https://github.com/truj/midica

# Requirements

This project is based on Foundation-CLI which requires Node.js

So you need to install Node.js first.

Then install Foundation-CLI:

`sudo npm install --global foundation-cli`

# Download and run

In your local git directory, clone this repository:

`git clone git@github.com:truj/midica.org.git`

Then switch to the new directory:

`cd midica.org`

And install the dependencies:

`npm install`

Then you can run the project either with:

`npm start`

or with:

`foundation watch`

# Productive Version

To build a productive version, type:

`foundation build`

Then you find the resulting files in the dist directory.
