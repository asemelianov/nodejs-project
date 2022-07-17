# Build and Run a NodeJS app with Docker & GitHub Actions

    1. npm init
    2. npm install express
    3. npm install babel-cli
    4. npm install babel-preset
    5. npm install babel-preset-env
    6. npm install jest
    7. npm install
    8. npm test
    9. npm start

## 2. Setup Docker - Build NodeJS app Docker Image

    1. Edit .dockerignore
    2. Edit Dockerfile
    3. docker build . -t emelianovas/nodejs-project
    4. docker run --name nodejs-project -it -d -p 3000:3000 emelianovas/nodejs-project
