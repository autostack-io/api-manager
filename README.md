# ASAM
ASAM is an API management developed by Autostack Community.

## Summary
- About API management
- Features
- Install and Build

## About API management
> API management is the process of creating and publishing web APIs, enforcing their usage policies, controlling access, nurturing the subscriber community, collecting and analyzing usage statistics, and reporting on performance. API Management components provide mechanisms and tools to support developer and subscriber community. [Wikipedia](https://en.wikipedia.org/wiki/API_management).

## Features
- API Gateway
- API Discovery
- Load Balancer
- Access Control

## Install and Build
Clone the repository:
```sh
$ git clone https://github.com/autostack-io/ASAM.git
$ cd ASAM
```
Run this commands on `dashboard` folder:
```sh
$ cd dashboard
$ npm install && npm run build
```
Go back to the previous directory
```sh
$ cd ..
```
Run this commands on `controller` folder:
```sh
$ cd controller
$ npm install && npm run build
```