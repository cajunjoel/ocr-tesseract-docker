# OCR Tesseract Docker
Allows upload of an image for OCR using Tesseract and deployed using Docker.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

You will need Docker installed on your system and a command line editor.

```
Docker
Git Bash (on Windows)
Terminal (Linux or Mac)
```

### Installing

You can clone this repository or download a zip file, build and run the Docker image.
```
$ docker build -t ocr-tesseract-docker .
$ docker run -d -p 5000:5000 ocr-tesseract-docker

```

OR you can pull and/or run the Docker image from my repository on Docker Hub

```
docker pull ricktorzynski/ocr-tesseract-docker
docker run ricktorzynski/ocr-tesseract-docker

```
Then open up browser to http://localhost:5000

I have also deployed it to Heroku, but free account only allows 512MB of memory and this can be exceeded by the app.  But here is a URL:
[Heroku](https://floating-castle-16480.herokuapp.com/)