# Steps for Deploying a Static HTML Site 
# with Docker and Nginx
Currently in this repo there is only simple index.html file, but this repo is for simple testing and training purposes.

## Step 1 - Create a Directory for the Website
Make sure that you have your HTML files already in the current directory.

## Step 2 - Create a file called Dockerfile
Place the following contents into the Dockerfile

```bash
FROM nginx:alpine
COPY . /usr/share/nginx/html
```

These lines of code represent the image we're going to use along with copying the contents of the current directory into the container.
