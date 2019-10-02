## Python/Tornado Web API Example

To leverage this code, download or clone from github to a local project
Create a virtualenv for the project and activate
Install Tornado:  pip install tornado
run api.py
test using http request on port 8888 i.e. http://localhost:8888 as follows

Add a book:
http://yourserver:8888/v1/addbook?title="Creating Microservices with Python/Tornado"&author="William Collins"

List all books:
http://yourserver:8888/v1/getbooks

Delete same book:
http://yourserver:8888/v1/delbook?title="Creating Microservices with Python/Tornado"

Tornado (about):
http://tornadoweb.org. 
Tornado is a scalable, non-blocking web server and web application framework written in Python. It was developed for use by FriendFeed; 
the company was acquired by Facebook in 2009 and Tornado was open-sourced soon after.
By using non-blocking network I/O, Tornado can scale to tens of thousands of open connections, making it ideal for long polling, 
WebSockets, and other applications that require a long-lived connection to each user.

Type: Web server
Original author(s): FriendFeed
Tornado (web server) - Wikipedia
https://en.wikipedia.org › wiki › Tornado_(web_server)

Tornado Web Server — Tornado 6.0.3 documentation
https://www.tornadoweb.org
Tornado is a Python web framework and asynchronous networking library, originally developed ... Here is a simple “Hello, world” example web app for Tornado:.
‎Introduction · ‎Structure of a Tornado web · ‎Tornado.ioloop · ‎RequestHandler

### 
