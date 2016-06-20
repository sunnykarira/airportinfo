# Airport-status

An Alexa app based on *[ASK] Alexa Skills Kit that adds up an Alexa Skill onto Amazon devices (Echo, Echo Dot, Fire TV ) to utter current status of airport and their weather.

# Pre-Requisites

- NodeJS

```bash
	sudo apt-get install nodejs
```
- Alexa App Server

```bash
	git clone https://github.com/matt-kruse/alexa-app-server.git
```bash

# Installation

## Alexa App Server and App installation

- Change Directory to Alexa App Server

```bash
	cd alexa-app-server
```bash

- Do an npm install

```bash
	npm install
```bash

- Copy the app ("airportinfo") into examples/apps folder

- Run the file server.js in examples folder

```bash
	node server.js
```bash

- The utterances acan be seen on port 8080 in web browser.

```bash
	http://localhost:8080/alexa/airportinfo
```bash




# Features

- Simplified handling of requests and generating responses
- Asynchronous handlers supported
- Returns Airport status with weather

