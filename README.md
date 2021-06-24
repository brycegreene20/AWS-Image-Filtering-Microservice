Udagram Image Filtering Microservice
Before submitting, check if you have completed all criteria in the project rubric. The project submission should include a Git repository and a link to the endpoint URL for a running elastic beanstalk deployment (provided through the student notes).

Project:

Setup Node Environment
You'll need to create a new node server. Open a new terminal within the project directory and run:

Initialized a new project: npm i
run the development server with npm run dev
Create a new endpoint in the server.ts file
The starter code has a task for you to complete an endpoint in ./src/server.ts which uses query parameter to download an image from a public URL, filter the image, and return the result.


Utilized import {filterImageFromURL, deleteLocalFiles} from './util/util';
Deployed this system to Elastic Bean Stalk AWS Service. 
Used 'eb init', 'eb create' a new environment, adn 'eb deploy' to deploy your image-filter service

