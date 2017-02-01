This is an example of using GraphQL to handle user login/logout and registration

Well, GraphQL doesn't do this on it's own it just passes the username and password to the request then the request is processed by passportjs which actually take care of everything.

# Packages used for auth
- [passport.js](https://github.com/jaredhanson/passport)
- [passport-local-mongoose](https://github.com/saintedlama/passport-local-mongoose)

# Installation
- clone the repo
```
git clone https://github.com/shalkam/graphql-login.git
```
then cd to the directory
```
cd graphql-login
```

# Development
- First make sure that you MongoDB up and running (you can configure the database connection at `/src/config.js`)
- then just run
```
npm run dev
```

# Build
- run this command
```
npm run build
```
- This repo is based on this awesome [boilerplate](https://github.com/jlongster/backend-with-webpack/) you will have all node packages bundled in just one file you will need to install only `mongoose` externally.
