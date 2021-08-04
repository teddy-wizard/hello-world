# Docker Testing for Jiang

This is a "Hello world" app for Docker testing.
Here is using Python and Flask.


## Usage

### Run it locally

$ python3 -m venv venv

$ ./venv/bin/pip install -qr requirements.txt

$ ./venv/bin/python3 server.py





### Run it in Docker

$ docker run -p 8000:8000 teddy-wizard/hello-world
