# codex-ai
# Codex is a coding buddy created using OpenAIs davinchi-003 model. 

## If you find this project helpful, you can buy me a coffee here
<a href="https://www.buymeacoffee.com/eyuel" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" alt="Buy Me A Coffee" style="height: 60px !important;width: 217px !important;" ></a>

## install

### client
```bash
cd client && npm i
```
### server
```bash
cd server && npm i
```

## Configuration
### Server
1. obtain your openai api key from [here](https://openai.com)
2. `cd server`
3. copy `.env.example` to `.env`
4. add your openai api key inside `.env`
5. make sure you have added `.env` to your `.gitignore` file

### Client
1. `cd client`
2. copy `.env.example` to `.env`
3. add your fiirebase config and server url
4. make sure you have added `.env` to your `.gitignore` file

## run
### to run client and server concurrently
```bash
cd client
npm run dev
```
### to run client only
```bash
cd client
npm run dev
```
### to run server only
```bash
cd server
npm run server
```

***Tech used***
  - openai API
  - vite
  - vanilla
  - node.js
  - express


## credits
- [OpenAI](https://openai.com) for creating [ChatGPT](https://chat.openai.com/chat)
