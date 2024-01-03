# TrelloAPI
This repository contains a Postman collection for testing various Trello REST API endpoints. The test scope is based on the official Trello API documentation, which you can find [here](https://developer.atlassian.com/cloud/trello/rest/api-group-boards/#api-boards-post).

# Tested Features:
### Board
- Create a board.
- Get a board.
- Update a board.
### List
- Create a list on a board.
- Get a list.
- Update a list.
### Card
- Create a card on a list.
- Get a card.
- Update a card.
- Get a field on a card.
- Create an attachment on a card.
- Get an attachment.
- Create a lable on a card.
- Create a checklist on a card.
- Get a checklist.
- Create a checkitem on a checklist.
- Get a checkitem.
- Create a comment on a card.
- Create a reaction to a comment.
### Delete
- Delete action's reaction.
- Delete an action.
- Delete a checkitem.
- Delete a checklist.
- Delete an attachment.
- Delete a card.
- Delete a Board.

## Test Cases
- Check status code.
- Check response time.
- Check the response format as expected.
- Validate returned values in the response body.
- Validate the response body schema.
- Ensure proper handling of errors.
  
## Prerequisites
- Installing postman tool.
- A Trello account.
- Trello authentication (generate a valid key and token).
- Importing collection and environment into postman.
  
#### Now, Your Postman collection is ready to run.
### additional steps :
- run collection using the Newman tool.
- creating a Newman report attached to the project.

