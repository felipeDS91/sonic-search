## 👨🏻‍💻 About the project

This project is a little example to how use sonic to improve your node backend searches.

## 🚀 Technologies

Technologies that I used to develop this api

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [Sonic](https://github.com/valeriansaliou/sonic)

## 💻 Getting started

Import the `Insomnia.json` on Insomnia App or click on [Run in Insomnia](#insomniaButton) button

### Requirements

- [Docker](https://www.docker.com/)
- [Node](https://nodejs.org/en/download/)
- [Yarn](https://classic.yarnpkg.com/en/docs/install#windows-stable)

**Clone the project and access the folder**

```bash
$ git clone https://github.com/felipeDS91/sonic-search.git && cd sonic-search
```

**Follow the steps below**

```bash
# Install the dependencies
$ yarn

# Download the sonic image from Docker Hub
$ docker pull valeriansaliou/sonic:v1.3.0

# Creates a docker container of sonic
$ docker run -p 1491:1491 -v /path/to/your/sonic/config.cfg:/etc/sonic.cfg -v /path/to/your/sonic/store/:/var/lib/sonic/store/ valeriansaliou/sonic:v1.3.0
Example (Windows)
$ docker run -p 1491:1491 -v D:\sonic-search\sonic\sonic.cfg:/etc/sonic.cfg -v D:\sonic-search\sonic\store:/var/lib/sonic/store/ -d valeriansaliou/sonic:v1.3.0

# Run this command to start the server in development mode
$ yarn dev

# Well done, project is started!
```

Made with 💜&nbsp; by Felipe Douglas 👋 [See my linkedin](https://www.linkedin.com/in/felipe-douglas-dev/)
