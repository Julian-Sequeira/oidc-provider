# OIDC Privacy Preserving Provider

## Instructions

Clone the repo and run `npm i` to get the necessary dependencies. 
**Note:** The `nanoid` npm package was deliberately downgraded to v3.0 as the latest version is not compatible with non-EJS node applications, will have to find a replacement later.

The entrypoint to this application is `index.js`. You run can it using `npm run-script server`.

## Application Structure

`support/account.js` : functions to add, create, and find user credentials
`support/config.js` : stores client (relying party) data, as well as server signing info
`routes/koa.js` : endpoint handlers

## Storage

Currently the applications uses an in-memory solution to store issued tokens, codes, user sessions, and dynamically registered clients.
There is support for MongoDB, which I will use at a later point.


## Testing Accounts

## Routes
