# Docker Testing for Jiang

This is a "Hello world" app for Docker testing.
Here is using Python and Flask.


## Usage


### Run it in Docker
If you installed docker already, you can run the following commands and see a result.

$ docker run -p 8000:8000 teddy-wizard/hello-world



### Run it locally

$ git clone https://github.com/teddy-wizard/hello-world.git

$ cd hello-world

$ python3 -m venv venv

$ ./venv/bin/pip install -qr requirements.txt

$ ./venv/bin/python3 server.py
