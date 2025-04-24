# Valorant Tournament Overlay System

> This is made by the community and is not affiliated with Riot Games and/or VALORANT.

## Deployment on Render

1. Fork this repository to your GitHub account
2. Sign up for [Render](https://render.com/)
3. Create a new Web Service
4. Connect your GitHub repository
5. The service will automatically deploy using the configuration in `render.yaml`

## Configuration

- Default admin password is in `config/appConfig.json`
- Player tokens are in `config/players.json`
- Game state configuration is in `config/gameState.json`

## Local Development

```bash
# Install dependencies
npm install

# Start the server
npm start
```

The server will start on port 25565 by default (or the PORT environment variable if set).

## Usage

- Access the admin panel at `/admin`
- Players need to install the Overwolf client application and connect using their tokens
- Each overlay is available at its respective URL (e.g., `/map_picks/`, `/player_stats/`, etc.) 