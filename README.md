# EX01 Developing a Simple Webserver
## Date: 12.09.25

## AIM:
To develop a simple webserver to serve html pages and display the list of protocols in TCP/IP Protocol Suite.

## DESIGN STEPS:
### Step 1: 
HTML content creation.

### Step 2:
Design of webserver workflow.

### Step 3:
Implementation using Python code.

### Step 4:
Import the necessary modules.

### Step 5:
Define a custom request handler.

### Step 6:
Start an HTTP server on a specific port.

### Step 7:
Run the Python script to serve web pages.

### Step 8:
Serve the HTML pages.

### Step 9:
Start the server script and check for errors.

### Step 10:
Open a browser and navigate to http://127.0.0.1:8000 (or the assigned port).

## PROGRAM:
```
<!doctype html>
<html>
    <head>
    </head>
    <body bgcolor="cyan">
        <table border="1" align="center" bgcolor="pink" cellpadding="10">
            <caption><h1>List of protocol</h1></caption>
            <tr><th>S.NO</th><th>Name of the layer</th>
                <th>Name of the protocol</th>
            </tr>
            <tr>
                <td>1</td><td>Application Layer</td><td>HTTP,FTP</td>
            </tr>
            <tr>
                <td>2</td><td>Transport Layer</td><td>TCP & UPD</td>
            </tr>
            <tr>
                <td>3</td><td>Network Layer</td><td>IPV4,IPV6</td>
            </tr>
            <tr>
                <td>3</td><td>Network Access Layer</td><td>Ethernet</td>
            </tr>

        
    </table>
    </body>

```


## OUTPUT:
<img width="1548" height="540" alt="Screenshot 2025-09-10 140330" src="https://github.com/user-attachments/assets/b5b7b1da-31b8-4dab-8e5c-916b4eecea89" />

## RESULT:
The program for implementing simple webserver is executed successfully.
