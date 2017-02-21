# Number Facts
This is Action on Google that uses Node as a fulfillment provider. It can be loaded to any of the devices supporting Actions on Google, which currently (Feb. 13, 2017) consists of Google Home and Google Pixel. Tell it a number and it will give you some fact about it. It uses [Numbers API](numbersapi.com) to retrieve the facts. Please refer to **Usage** section for example use cases.  

# Setup Instructions
Most of the steps here are the same as in [Actions on Google](https://github.com/actions-on-google) official GitHub page.
1. Create a new [API.AI](https://api.ai)
2. Click on the project gear icon to see the project settings.
3. Select "Export and Import".
4. Select "Restore from zip". Follow the directions to restore.
5. Select the NumberFacts.zip file in this repo.
6. Deploy this app to your preferred hosting environment (I recommend ngrok for local development).
7. Set the "Fulfillment" webhook URL to the hosting URL.
8. Make sure all domains are turned off.
9. Enable Actions on Google in the Integrations.
10. Provide an invocation name for the action.
11. Authorize and preview the action in the [web simulator](https://developers.google.com/actions/tools/web-simulator).

# Usage
`Numbers API` provides different types of facts: date, year, math and trivia (default). You can communicate with `Number Facts` by asking it about any of those types.
Sample queries include:
1. Tell me what happened on the 3rd?
2. Tell me something mathematical about 333?
3. Tell me about year 777?
4. Tell me about number 5

# License
MIT (see LICENSE.md)
