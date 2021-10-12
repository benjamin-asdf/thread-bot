# ben-test-bot

A bot reproducing a bug with discord or discljord api

## Usage

- run bot with core ns as entry point
-  Add bot to a test server
- @Mention the bot
- wait for the bot to create a channel
- message as user in channel and observe the logs

- expectation: bot recieves events from thread, since he can view it

- what happens: bot doesn't recieve "message-create" event
