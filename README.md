# slack-dev-experiments
Slack Development experiments (apps/bots) with node.js

Please look at payload-button.json:

API Docu: https://api.slack.com/interactive-messages#responding

I want to respond to my message like this:
https://a.slack-edge.com/dcb1/img/api/message_guidelines/Example_6.gif

I send a 

	var response = {
        "text": "Create Purchase Order for Beam Breaker B-3",
        "replace_original": true,
        "attachments": [
            {
                "title": "Create Purchase Order", ...

and want to leave out the button and replace it with something like you show this in your picture, but which field is it? It is not a "text" and I can't find the info in the API documentation...
