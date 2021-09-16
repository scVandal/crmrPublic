# quickActionRedirectFlow

## Description
Hate that flows can't redirect to record pages out of the box? So did a client of mine, which is where this Aura component came from. This simple component leverages the lightningQuickAction interface to create a invocable action that can be called in a flow. It takes a recordId of any SObject record and does a simple redirect of the user from the flow to the page.

## Usage
Deploy this to your org, then drop it into a flow using the Action element. Pass a recordId and the action will redirect the user. Please note: this will end the flow - be sure to use this at the logical end of your flow.

## Extension
This component can easily be extended/changed to redirect to a specific Lightning Record Page, Community page or even an external page.
