# Telegram bot for Creating, Reading and Deleting username and email

This is a simple telegram bot that is used to create, read and delete usernames and emails.

## Developer manual

Environmental variables to setup:

- `BOT_TOKEN` : The bot token got from the https://t.me/botfather (@BotFather)
- `DB_URI` : The URI of the MongoDB database server (include the database name also). (eg: `mongodb://localhost:27017/testdb`)

### Installation

```bash
$ npm install
```

Or

```bash
$ npm install -D typescript @types/node
$ npm install --save dotenv grammy mongoose
```

### Build and run commands:

```bash
$ npm start
```

Or:

```bash
$ npx tsc
$ node index.js
```

## User manual

Commands:

- `/start` - Start the bot
- `/save username email@example.com` - Save a record
- `/delete email@example.com` - Delete a record by the email
- `/getall` - See all data in the database

## More info

Developed by Usitha Indeewara. (Under GNU GPL v3)

    Copyright (C) 2023  Usitha Indeewara

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.
