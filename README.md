> A star ⭐ from you means a lot to us!

Telegram bot to rename documents and videos with custom thumbnail.

[![Open Source Love svg1](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://github.com/ellerbrock/open-source-badges/)

## Usage

### Deploy to Heroku

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/filmygod/strkrename)

1. Tap on above button and fill `API_ID`, `API_HASH`, `BOT_TOKEN` and `MUST_JOIN`.
2. Then tap "Deploy App" below it. Wait till deploying is complete (will take atmost 2 minutes).
3. After deploying is complete, tap on "Manage App"
4. Check the logs to see if your bot is ready!

### Local Deploying

1. Clone the repo
   ```markdown
   git clone https://github.com/filmygod/strkrename
   ```
   
2. Get a DATABASE_URL. If you don't know how, deploy using Heroku Button only or delete database things as it's not a compulsion.
   
3. Edit `Config.py` and fill the needed variables

4. Enter the directory
   ```markdown
   cd RenameBot
   ```
5. Run the file
   ```markdown
   python3 rename.py
   ```

## Environment Variables

#### Mandatory Vars

- `API_ID` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `API_HASH` - Get this from [my.telegram.org](https://my.telegram.org/auth)
- `BOT_TOKEN` - Get this from [@BotFather](https://t.me/BotFather)
- `DATABASE_URL` - Will be automatically added by Heroku.
- `MUST_JOIN` - Username/ID of your telegram channel/group.

## Functions

> More features soon, this is a minimal example :)

1) Rename documents and videos
2) Custom Thumbnail Support
3) Upload video as video or document

## To-Do

> That's on you mainly...

[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

## Credits

- [Dan Tès](https://github.com/delivrance) for his [Pyrogram](https://docs.pyrogram.org) Library

## Support

Channel :- [@FilmygodHindiHDMovie](https://t.me/FilmygodHindiHDMovie)

Group Chat :- [@FilmygodHindiHDMovie](https://t.me/FilmygodHindiHDMovie)
