# Introduction

This repository hosts the source code of http://www.midica.org/ &mdash; the documentation website for Midica, the Music programming and processing tool:
https://github.com/truj/midica

# Requirements

This project is based on Foundation for Sites 6.8.1 which requires:

- Node.js in Version 12 or 14
- Yarn or npm

So you need to install Node.js first in an appropriate version. (Tested with v14.21.3).

Then you need yarn, if you don't have it already:

`sudo npm install -g yarn`

# Download and run

In your local git directory, clone this repository:

`git clone git@github.com:truj/midica.org.git`

Then switch to the new directory:

`cd midica.org`

And install the dependencies:

`yarn`

(`npm install` could work as well.)

Then you can run the project with:

`yarn start`

(`npm start` could work as well.)

# Productive Version

To build a productive version, type:

`yarn build`

Then you find the resulting files in the dist directory.
