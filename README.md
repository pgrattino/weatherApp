# Weather App
By: Peyton Grattino
## Description
The goal is to use React Native to build a weather app on desktop and mobile. I am treating this as a way of learning how to integrate an API and make API calls.

## Setting up the dev environment
Using the Dockerfile in /weatherApp the app should build and run with the necessary dependencies.
```
$ docker build -t weatherapp .
$ docker run -it -p 19000:19000 -p 19001:19001 -p 19002:19002 weatherapp
```
