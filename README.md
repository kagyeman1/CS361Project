# CS361Project

ACCESSING MY MICROSERVICE 

1)I will send over my Microservice (Assignment8server.js) via email.

2)Place the file in your root directory of your project folder.

3)Open a terminal and access your project directory from the command line.

4)Install the necessary libraries to run zmq on your IDE.

5)Once the libraries are installed, on command line type in Node Assignment8server.js.

6)This should start the microservice.

7 )Run your project on another terminal.


HOW TO REQUEST DATA FROM MY MICROSERVICE

1)Your project should already have the ZeroMQ module imported into your project. If not, do so now.

2)Change your localhost to port 3001 to where you will start receiving messages.

3)Your application should make a request using ZeroMQ and waits for my microservice to receive the request.

4)Once the microservice receives your message, a)it will reply back acknowledging your request and b)send the 
URL for the ticker.csv file.


HOW TO RECEIVE DATA USING MY MICROSERVICE

1)Your application will contact the microservice.

2)Once contact has been made, your application will receive the return reply from my microservice.

3)Next, my microservice will then send back a csv url to your application.

4)Once you receive the URL, you can then can manipulate the data however you want. 

![image](https://user-images.githubusercontent.com/122496065/218302200-95b3a460-bb85-48cc-9944-100053251554.png)
