

Create a new file config.js and Copy the config.example.js file's data to config.js file

Update the TOKEN in `config.js` file.Token would be generated from dashboard `https://app.videosdk.live/dashboard`

   ```
   TOKEN="Your Token Here"
   ```

If one doesn't want to give their token then they can generate token using AUTH_URL of their own in `config.js` file

   ```
   AUTH_URL=one's auth url
   ```

Run the app

   ```sh
   npm install -g live-server
   live-server --port=8000
   ```
