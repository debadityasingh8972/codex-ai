# Codex-ai
## Codex is a coding buddy created using OpenAIs davinchi-003 model. 

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
npm start
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

