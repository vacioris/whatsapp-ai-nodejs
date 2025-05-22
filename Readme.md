# WhatsApp AI Lite

WhatsApp AI Lite is a simplified version of a WhatsApp bot that utilizes AI to automate message replies.

## Requirements

- **Processor**: Atleast Core i5 8 Gen or later
- **RAM**: 8 GB OR Above
- **GPU**: It requires atleast 4GB GPU 1050 or Above
- **NodeJs**: Nodejs LTS Version 20 or later
- **Ollama**: Ollama is required to be installed and running. You can run the following command to install the required model:

```ollama run llama2```

## Installation

To install WhatsApp AI Lite, follow these steps:

- **1. Install the required npm packages**:

```npm i whatsapp-web.js```

```npm install qrcode-terminal```

```npm install axios```

IF NPM < 14.0 run
Install NVM (Node Version Manager)

```curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.3/install.sh | bash```
Load NVM in Current Terminal

```source ~/.nvm/nvm.sh```
(Close/reopen your terminal if nvm isn't recognized afterward.)

Install Node.js v22 (LTS)

```nvm install 22```
Verify Versions

```node -v ``` # v22.x.x
```npm -v```   # 10.x.x
Install Puppeteer

```npm install puppeteer```



- **2. Navigate to the puppeteer directory and install the required dependencies**:

```cd ./node_modules/puppeteer```

```npm install```

```cd ..```


- **3. Install WhatsApp Web.js**:

```npm install github:pedroslopez/whatsapp-web.js```

```npm install github:pedroslopez/whatsapp-web.js#webpack-exodus```

- **4. Fix any audit issues**:

```npm audit fix```

- **5. Create Cache Folder**:
 
If ```.wwebjs_cache``` not exist create manually.

## Usage

To run WhatsApp AI Lite, execute the following command:

```node index.js```

## How It Works

WhatsApp AI Lite listens for incoming messages and automatically generates replies using an AI model. It fetches responses from an external API and sends them back to the user.
