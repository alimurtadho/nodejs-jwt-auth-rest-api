# Documentation
 APIs that we need to provide:
Methods	 || Urls	         ||Actions
POST	 ||/api/auth/signup	 ||signup new account
POST	 ||/api/auth/signin	 ||login an account
GET	     ||/api/test/all	 ||retrieve public content
GET	     ||/api/test/user	 ||access User’s content
GET	     ||/api/test/admin	 ||access Admin’s content

## Project setup
```
npm install
```

Then, edit `app/config/db.config.js` with correct DB credentials.

### Run
```
node server.js
```
