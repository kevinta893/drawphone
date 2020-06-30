<div align="center">
  <img src="http://i.imgur.com/detQDdM.png"/>
  <br>
  <h2>
    Play now at: <a href="http://drawphone.tannerkrewson.com/">drawphone.tannerkrewson.com</a>
  </h2>
  <br>
  <img src="https://i.imgur.com/RA5HwjB.png" width="222"/><img src="https://i.imgur.com/JgFvlRb.png" width="222"/><img src="https://i.imgur.com/nVdQccl.png" width="222"/><img src="https://i.imgur.com/VlfnAvL.png" width="222"/>
</div>
<br>

# About

Drawphone was inspired by [Spyfall](https://github.com/evanbrumley/spyfall) and [Telestrations](http://telestrations.com/).

# Development

#### Instructions

1. Clone the repo to get started
2. Fork and create any pull requests against the `dev` branch
3. Run `npm install`, then `npm start` to launch the server
4. Go to `localhost:3000` in your browser

#### Setting up HTTPS

This step is optional for development.

1. Create a certificate and private key files and place them in the `bin` folder
2. Name these files `server.crt` and `server.key` respectively

You may want to generate a certificate using [Certbot](https://certbot.eff.org/) from Let's Encrypt.

#### Tips

-   To change the default port, set the `PORT` environment variable
-   If you set the `NODE_ENV` environment variable to `development`, you can use the link `localhost:3000/dev` to automatically join game `ffff`. This is helpful for speeding up debugging.
