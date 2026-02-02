# FateRobot

A Discord bot for Fate-series RPG/gacha.

## Installation
1. Clone the repository.
2. Install dependencies with `npm install`.
3. Configure your `.env` file.

## Configuration
Copy `.env.example` to `.env` and fill in your credentials:
- DISCORD_TOKEN: Your bot token
- MONGO_URI: MongoDB connection string
- CLIENT_ID: Discord application id
- GUILD_ID: Discord server id
- PREFIX: Command prefix

## Running the Bot
You can run the bot either using Docker or npm:
### Docker
Run with Docker:
```bash
docker-compose up
```
### npm
Run with npm:
```bash
npm start
```

## Seeding Database
To seed the database, run:
```bash
npm run seed
```

## Adding Images and Character Data
You can update the seed data in `seed/characters.seed.json`. Make sure to use placeholder images links.
