# Simple-Puppeteer-Docker-Example
Are you struggling to run Puppeteer in a Docker container because of its complex dependencies? This repository provides a minimalistic example project to help you get started.
## Usage
### Building the image
To build the Docker image, run:
```docker build --platform linux/amd64 -t example-puppeteer-app .```
### Running the container
Once the image has been built, you can run the Docker container with the following command:
```docker run --rm example-puppeteer-app```
This command will start the container and execute the example Puppeteer script included in the project.