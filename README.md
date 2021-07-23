## GIDEON OTENG

## APP INSTRUCTIONS

This is the backend of an ecommerce shop. User's are going to create an account, log into their account, search items and proceed to buy them.

## Changes

- Added `UserLogout` resource in `user.py`;
  - Imported and added to `app.py`
- Modified blacklist loader so it checks the JWT's `'jti'` key instead of the `'identity'`.
- Made `BLACKLIST` initially an empty set.
