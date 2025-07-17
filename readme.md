# CS2 RCON Web Panel

## Usage (Using Docker)
- Run `docker-compose up` to start the container
- Navigate to localhost:3000 to start using the panel
- Default login credentials can be changed via [environment variables](https://github.com/l4rm4nd/cs2-rcon-panel/blob/master/docker-compose.yaml#L8-L10).

## Usage (Without Docker)
- Install NodeJS 18.0 or higher
- Run `npm install` in the root project folder
- Run `npm install -g nodemon` to install nodemon
- Run `nodemon app.js` in the root project folder
- Default login credentials can be changed via environment variables `USERNAME` and `PASSWORD` or directly in `db.js`.

## Abilities 

- Setup Competitive/Wingman gamemodes
- Pause/Unpause/Restart match
- List and restore round backups
- Start Knife/Warmup/Live rounds (CFGs are in cfg folder, sent via RCON)
- Send RCON Commands to the server

## Screenshot

![Screenshot](https://github.com/shobhit-pathak/cs2-rcon-panel/blob/master/panel_screenshot.PNG)

## Limitations

- Cannot get logs, feeds (log_address is not present in CS2 as of now)

## License

MIT
