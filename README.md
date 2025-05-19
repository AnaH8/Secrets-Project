# Secrets project
Authentication project that allows you to view and submit a secret only if you are authenticated

## Built with
- Node.js
- EJS
- PostgreSQL
- CSS

## How it looks
[!home page](/public/images/home-page.JPG)
[!registration and login](/public/images/secrets.JPG)
[!submit a secret](/public/images/submit.JPG)

## What does the project do
- allow users to register/login with OAuth or email and password, using passport strategies
- salting and hashing password for db storage, using bcrypt
- check if user exists in db
- check if user is authenticated
- allow authenticated users to submit a secret

### To be added in the future
- display a random secret, either from the users' input (db) or from an API