# HelpBridge

HelpBridge is a ticket support bot for Discord built with TypeScript, using discord.js v14 and Prisma. This project includes Docker Compose setup for local development with PostgreSQL.

## Setup Steps

1. Clone the repository:
   ```bash
   git clone https://github.com/758gianni/HelpBridge.git
   cd HelpBridge
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Set up your `.env` file based on `.env.example`:
   ```bash
   cp .env.example .env
   ```

4. Run Docker for PostgreSQL:
   ```bash
   docker-compose up
   ```

5. Run the bot:
   ```bash
   npm run start
   ```

## Commands
- `/ticket open`: Opens a new ticket.
- `/ticket close`: Closes an existing ticket.
- `/ticket add`: Adds a user to the ticket.
- `/ticket remove`: Removes a user from the ticket.
- `/ticket claim`: Claims the ticket.
- `/ticket transcript`: Provides a transcript of the ticket.
- `/setup`: Sets up the guild for the bot.