#Web Streams using NodeJS

If you would like to share big files between the server and front end, probably you will decide to split the files or create many requests to get this chunk of data step by step.

To reduce the cost and create a constant connection between the front end and the backend we can use webstreams to split the big files into chunk jsons and share their step-by-step with only one request.  

This little project has been using web streams to do it. 

We have a server and a client app to simulate this communication.

We are using node 19 to do it. 

To execute it, open the server folder and run:
`npm install` && `npm run dev`

And then, open a new terminal and run:
`npm install` && 'npm run start`

To run the frontend we will use `http-server`

To run the backend we will use `node --watch`


