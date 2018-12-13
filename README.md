This project is my solution to the assignment sent through e-mail.

## Prerequisites

This README is written for:
- Mac OS

## Requirements

### Install Node.js runtime environment
```
https://nodejs.org/en/
```

## Getting started

### Change the client identifier key
Please navigate to the folder '/origo/src/pages', then open the file 'StationOverview.js'.
```
Change line '4' to include your client identifier key available for free at 'https://developer.oslobysykkel.no/clients'
```

### Run the backend
In the terminal, please navigate to the folder 'origo_backend' located inside 'origo'(root folder).
Then, run:
```
$ npm install
```
When finished, run:
```
$ npm start
```
The backend is a simple http proxy solution for redirecting requests to oslobysykkel.no.
By doing this, no CORS related issues will hopefully be present while developing, or testing on different environments.

### Run the client
In the terminal, please navigate to the folder 'origo'(root folder).
then, run:
```
$ npm install
```
When finished, run:
```
$ npm start
```
