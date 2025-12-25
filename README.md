# REST API Testing Framework

Reusable REST API automation framework using Postman, Newman, and GitHub Actions.

## Features
- CRUD API testing
- JavaScript assertions
- Environment-based execution
- Automated CI runs
- HTML reports

## How to Run Locally

### Install Newman
npm install -g newman

## Run Collection
newman run postman/collection.json -e postman/environment.json

## CI/CD

Tests run automatically on every push using GitHub Actions