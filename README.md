# CS561-Assignment-2

### What I have done:
app.js file is used for mock server, in the code I have added the following:
  - const express = require('express') --Importing Express framework 
  - const port = 3000 --Local port 3000
  - Created a function to fetch the weather as a .json file 
  - Also I have added the mock response and print statement to know if you are connected to mock server

### Steps to do:
1. Create an EC2 instance on AWS and launch it.
2. Use command to get npm and node working and refer https://ostechnix.com/install-node-js-linux/ for the assistance to add the node commands in linux instance of EC2.
3. After setting up node and npm, use the command node app.js
4. copy public ip address and add that to your url
5. Final URL should look like this "http://107.22.156.69:3000/data/2.5/weather?q=location&appid=your_api_key"
