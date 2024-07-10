# Polling System API

## Setup

1. Clone the repository
2. Run `npm install` to install dependencies
3. Set up MongoDB and update `config.js` with the MongoDB URI
4. Run `npm start` to start the server

## Endpoints

- `POST /questions/create` - Create a question
- `POST /questions/:id/options/create` - Add an option to a question
- `DELETE /questions/:id/delete` - Delete a question
- `DELETE /options/:id/delete` - Delete an option
- `POST /options/:id/add_vote` - Add a vote to an option
- `GET /questions/:id` - View a question with its options and votes
