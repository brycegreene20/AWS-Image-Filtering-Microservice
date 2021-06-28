#  Udagram Image Filtering Microservice

Project:

Setup Node Environment

-Initialized a new project: npm i & run the development server with npm run dev

-Created a new endpoint in the server.ts file

-Coded an endpoint in ./src/server.ts which uses query parameter to download an image from a public URL, filter the image, and return the result.

-Utilized import {filterImageFromURL, deleteLocalFiles} from './util/util';

-Deployed this system to Elastic Bean Stalk AWS Service. 
 Used EBCLI commamds including : 'eb init', 'eb create' for the new environment, and 'eb deploy' to deploy your image-filter service


# Local Host URL
http://localhost:8082/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg


# Elastic Beanstalk URL
http://src-dev.us-east-1.elasticbeanstalk.com/filteredimage?image_url=https://upload.wikimedia.org/wikipedia/commons/b/bd/Golden_tabby_and_white_kitten_n01.jpg


# Elastic Beanstalk Envirornment Health Status (When Active)
![image](https://user-images.githubusercontent.com/67281298/123658747-032fdc80-d800-11eb-8e63-69957cf59eab.png)
