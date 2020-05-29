<!-- El README está muy chévere y bastante completo, el código en general de proyecto está muy bien estructurado -->

# AmaSync Extension 🍿🎬☁️

## Authors:

- [Sara Bejarano](https://sarabepu.github.io/website) 👩‍💻💃
- [Mariana Rodriguez](https://mrodriguez21.github.io) 👩‍💻🤘

## Description:

AmaSync is a chrome extension for watching Amazon Prime Video remotely with your friends.
It has the following functionalities:

- Create rooms
- Join your friend's room
- Real time synchronization of movies/series
- Chats in room
- Cutomizable name of users

# Instructions 💻:

If you downloaded the zip skip to section **Add Extension**

## Prerequisites:

Nodejs >= 10, npm, react

## Local deployment:

- Clone this repo
- Run the following commands

  ```bash
  cd amasync
  cd chrome-extension
  npm install
  npm run build
  ```

# Add Extension

- Open google chrome and write `chrome://extensions` in the navegation bar
- Enable developer mode and click LOAD UNPACKED
  ![tutorial extension](https://developer.chrome.com/static/images/get_started/load_extension.png)
- Select the unziped folder if you downloaded it from our landing page or `amasync/chrome-extension/build` if you cloned it

# How to use ✅

_Note: Your friends must have an PrimeVideo account_

Log into your PrimeVideo account

## Create a room

- Go to a movie/Serie you want to watch with your friends and open the description
- ⚠️**Click on the extension's icon**⚠️
- Click on Anonymous if you want to create a temporary room or LogIn for a recurrent one
- Click on _Create room_ and share the link with your friends

## Join a room

- Go to the link your friend shared with you
- Click on the play button
- ⚠️**Click on the extension's icon**⚠️
- Select a name and click on _Join_

You're all set 😉

## License

This project is licensed by the MIT [License](https://raw.githubusercontent.com/mrodriguez21/amasync/master/LICENSE).
