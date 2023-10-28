# skribbl_rs

skribbl_rs is our attempt at building a clone of the web-based drawing and guessing game [skribbl.io](https://skribbl.io).

To play a game: [https://skribbl.io/](https://skribbl.io/)

> It might take a few seconds to respond due to inactivity.

The site does not collect any user data or display ads.

## Hosted game URL

https://skribbl-multiplayer-cf4b28d28f83.herokuapp.com/

## Local setup

The project requires Node.js to be installed on your system. To run the project locally:

```bash
git clone https://github.com/Teja-11/skribbl_rs.git
cd skribbl_rs
npm i
npm run start
```

The app will run by default on port 3000. Open your browser and go to [http://localhost:3000](http://localhost:3000).

## Screenshots

| ![Landing page][landing]  | ![Landing page][settings] |
|:-------------------------:|:-------------------------:|
|  ![Landing page][game]    |  ![Landing page][scores]  |

## Technologies used

1. Back End
    - [Node.js](https://github.com/nodejs/node)
    - [Socket.io](https://github.com/socketio/socket.io)
    - [Express](https://github.com/expressjs/express)
    - [Chance](https://github.com/chancejs/chancejs)
    - [Leven](https://github.com/sindresorhus/leven)
    - [Nanoid](https://github.com/ai/nanoid)

2. Front End
    - [Socket.io client](https://github.com/socketio/socket.io-client)
    - [EJS](https://github.com/mde/ejs)
    - [Animate.css](https://github.com/animate-css/animate.css)
    - [Howler.js](https://github.com/goldfire/howler.js)
    - [DiceBear Avatars](https://github.com/DiceBear/avatars)
    - [Bootstrap](https://github.com/twbs/bootstrap)
    - [Varnam Transliteration API](https://github.com/varnamproject)


## Credits

1. Feature ideas: [https://github.com/scribble-rs/scribble.rs](https://github.com/scribble-rs/scribble.rs)
2. Sounds: [https://freesound.org/](https://freesound.org/)


[landing]: ./public/images/screenshots/landing.png
[settings]: ./public/images/screenshots/settings.png
[game]: ./public/images/screenshots/game.png
[scores]: ./public/images/screenshots/scores.png


## Reflection

The journey of developing Skribbl_rs was a rewarding experience characterized by collaboration and learning. Our team encountered various challenges, celebrated victories, and learned invaluable lessons throughout the process of crafting this engaging game.

Challenges:
Defining the core concept of the game was our initial hurdle. As the project progressed, technical challenges surfaced. Integrating real-time communication and synchronizing the backend with the frontend demanded meticulous coding. Balancing task estimations and harmonizing functionality with design presented ongoing challenges.

Successes:
Our structured project management approach, complemented by an agile mindset, played a pivotal role in our success. Assigning tasks based on individual strengths and maintaining open communication were instrumental in our achievements. Leveraging collaboration tools such as Git and GitHub facilitated seamless teamwork. Our tech stack, encompassing Node.js, Socket.io, Express, EJS, Bootstrap, and other libraries, empowered our development process.

