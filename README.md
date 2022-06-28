# Client for riksmote.se
[Staging](https://staging.riksmote.se)
[Dev](https://riksmote.github.io/client)
[API](https://riksmote.herokuapp.com)
[Swagger](https://riksmote.herokuapp.com/swagger)
## Start working
- Node.js installed.
- Then run `npm install -g typescript` to install typescript.
```bash
# clone repo
$ git clone https://github.com/riksmote/client.git

# install packages
$ yarn

# start
$ npm run start
```
## Deploy Dev
```bash
# before commit (creates /docs for ghpages)
$ npm run build:ghpages

# stage changes (don't forget /docs files)
$ git add index.html css/styles.css

# commit changes
$ git commit -m "Change titles and styling on homepage" 

# push
$ git push
```
## Deploy Staging
```bash
# Staging is not configured yet
```
## Features
- Login
- Register
- Google Login
- Facebook Login
- Apple Login
- WebSockets authentication
- Http authentication
- Websockets real-time chat.
- Rooms chats
- Private DMs
