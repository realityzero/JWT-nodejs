# JWT-nodejs

## Instructions
1. Clone repo
2. Create .env file `touch .env`
3. Run `npm i` - installs dependencies
4. Create secret keys with by running `require('crypto').randomBytes(64).toString('hex')`
5. Add envs in .env file
6. `npm run devStart` - starts a simple server that validates jwt token w/ request
7. `npm run devStart2` - starts authorization server
