## React-videocall with video-sync
Videocall + videosync app: https://react-video-sync.herokuapp.com/

Forked from https://github.com/nguymin4/react-videocall

<img align="right" width="420" src="https://raw.githubusercontent.com/nguymin4/react-videocall/master/screenshots/1.png"  alt =" " style="border: solid 1px #d4d4d4" />
  
Video call to your friend without registering. 
Simply send your friend your auto-generated unique ID to make the call.  
Everytime you open a new tab, the server gives you a totally different unique ID.

### Development

```
# Install dependencies
yarn install

# Run server
yarn watch:server

# Run webpack-dev-server
yarn watch:client
```


### Deployment

**Custom**
```
# Install dependencies
yarn install

# Build front-end assets
yarn build

# Run server
yarn start
```
