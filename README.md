# PlayZone — Game Hub

A responsive website for saving game URLs and opening each game in a new browser tab.

## Features
- Add a game name and URL
- Launch games in a new tab
- Remove saved games
- Saves the list in the current browser using local storage
- Responsive dark-purple layout

## Run locally
Requires Node.js 18 or newer.

```bash
npm start
```

Open `http://localhost:10000`.

## Deploy to Render
1. Push all project files to a GitHub repository.
2. In Render, choose **New → Web Service**.
3. Connect the repository.
4. Render can use the included `render.yaml` configuration.
5. Deploy the service.

Game websites open on their original domains. Some sites may block being embedded, but PlayZone opens them in a separate tab.
