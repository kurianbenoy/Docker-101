# Deriving the base image from latest Ubuntu version:18.04
FROM ubuntu:latest
# set maintainer
LABEL MAINTAINER='Kurian Benoy'
# Running system Update and installing python packages
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
# Copy the entire source code in . ie this folder and move to location file called app
COPY . /app
# Set /app inside docker as working directory
WORKDIR /app
# Run command pip install -r requirements.txt
RUN pip install -r requirements.txt
# does python app.py
ENTRYPOINT ["python"]
CMD ["app.py"]
