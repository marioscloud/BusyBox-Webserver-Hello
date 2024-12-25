# BusyBox Webserver Hello

## Project Overview
This project demonstrates how to set up a web server using BusyBox and bash script. It creates an HTTP server that serves a basic "Hello, World" page. The repository includes a straightforward bash script to automate the process. This project is ideal for those learning about lightweight web servers, embedded systems, or quick web service setups.

## Prerequisites
- Linux environment with BusyBox installed.
- Knowledge shell scripting.

## Contact
If you have any questions, feel free to reach out at marioscloud@duck.com

## Usage
1. **Clone the repository**:
   ```sh
   git clone https://github.com/marioscloud/BusyBox-Webserver-Hello
Navigate to the project directory:

sh
cd project_01

Make executable the file webserver_hello.sh and execute the provided bash script:

sh
chmod + ./webserver_hello.sh

./webserver_hello.sh

Access the web server: Open your web browser and navigate to http://localhost:8080 to see the "Hello, World" message.

Stop the server: To stop the server, find the process ID (PID) and kill it:

sh
ps aux | grep busybox
sudo kill -9 <PID>

This README provides clear instructions on how to set up and run your BusyBox web server. Feel free to adjust any details to better suit your project's specifics. Thanks for reading.
