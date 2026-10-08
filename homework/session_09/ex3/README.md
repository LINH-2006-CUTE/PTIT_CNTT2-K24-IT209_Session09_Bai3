# Docker HTML App - Session 09 - Bài 3

## Build image

docker build -t my-html-app:v1 .

## Run container

docker run -d -p 8081:80 --name html-app my-html-app:v1

## Test

curl.exe http://localhost:8081
