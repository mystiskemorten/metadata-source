# Postman

## Set up
1. Import collection and environment
2. Select imported environment at top bar to the right
3. Open request "token exchange"
4. Open tab "Authorization"
5. Scroll down to the bottom of the right pane 
6. Click "Get New Access Token" button
7. Perform authentication
8. When the modal pop ups with the new token, click "Use Token" button

If you now run the collection sequentially, you will synchronize the variables in the KUDAF database with the variables in metadata.json.

This is what the requests in the collection do:
- The first request "token exchange" will do a token exchange to obtain an access token for KUDAF backend.
- The second request "delete variables" deletes all variables in the database.
- The third request "post variables" inserts all variables in metadata.json.

# Run collection sequentially
How to run the collection sequentially

1. Click the sync folder.
2. Click the "Run" button at the top bar

## Postman
3. Click the "Run manually" button

## Postman CLI
3. Click the "Automate runs via CLI" button
4. Create API key by clicking "Add API key" button
5. Copy code snippet and run in terminal
