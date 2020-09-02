# digibyte-docker-source
Run DigiByte easily from within a Docker image, built completely from source

Simply run:
<pre>git clone https://github.com/DigiByte-Core/digibyte-docker-source
cd digibyte-docker-source
docker build -t digibyte-source:latest .
docker run digibyte-source:latest</pre>

This will download the latest release specified in the file (which can easily be tweaked manually) and get it all spun up and running, built from source on Ubuntu 20.04.
It's also very easy to run it on testnet etc by tweaking the variables at the top of the Dockerfile
