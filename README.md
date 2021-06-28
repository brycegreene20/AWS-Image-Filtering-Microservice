#  Udagram Image Filtering Microservice

Project:

Setup Node Environment
Created a new node server. Open a new terminal within the project directory and run:

Initialized a new project: npm i
run the development server with npm run dev
Create a new endpoint in the server.ts file
The starter code has a task for you to complete an endpoint in ./src/server.ts which uses query parameter to download an image from a public URL, filter the image, and return the result.


Utilized import {filterImageFromURL, deleteLocalFiles} from './util/util';
Deployed this system to Elastic Bean Stalk AWS Service. 
Used 'eb init', 'eb create' a new environment, adn 'eb deploy' to deploy your image-filter service

