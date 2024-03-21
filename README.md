# Substract two numbers

This is a node.js application that uses express framework to substract two numbers.

## How to use

Prerequistes:

1.  Install Node.js in your device
2.  Install Node Package Manager (npm) in your device

Steps

1. Download the repository to your local machine.
2. Navigate to the project directory on in your terminal.
3. Then run `npm install` to install express and other required dependencies.
4. To run the server, run `node server.js`.
5. By default this server listens to port 3000.
6. To make a GET request to substract two numbers using the API type the following link on your browser `http://localhost:3000/subTwoNumbers?n1=20&n2=10`. You can replace the number values with your preferences. In this example, n1 is 20 and n2 is 10.

Response

When the GET request is successful, the server will respond with the JSON object

```
{ "statusCode": 200, "data": 10 }
```
