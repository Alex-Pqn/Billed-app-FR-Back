## Backend - Billed

### OpenClassrooms fork for P9 - "Développeur Concepteur Logiciel"

This codebase contains the code needed to run the backend for Billed.

## Prerequisites

- You will need to have Node and `npm` installed locally on your machine.

| Node Version | Supported          |
| ------------ | ------------------ |
| 18.17.1      | :white_check_mark: |

> [!WARNING]
> The [frontend](https://github.com/Alex-Pqn/Billed-ocr_dcl) must also be installed in order to launch this project.

## Start App

### Install
```
npm install
```

### Compiles for development
Runs the API in the development mode. \
The API is available on local port `5678`, so [http://localhost:5678/](http://localhost:5678/)
```
npm run run:dev
```

## Accounts / Login

| Email                      | Password          | Is Admin |
| -------------------------- | ----------------- | -------- |
| admin@test.tld             | admin             | Yes      |
| employee@test.tld          | employee          | No       |