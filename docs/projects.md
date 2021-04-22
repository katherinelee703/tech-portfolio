---
id: projects
title: Projects
---

## Shelter in Pets

During the COVID-19 pandemic, the various social distancing protocols are preventing many people from visiting shelters to adopt pets.

Our smart mobile app solves this problem by letting users search for adoptable dogs from the comfort and safety of their homes.

It matches user-uploaded dog images to similar adoptable dogs, allows a user to conduct filtered searches based on desired traits,

and even recommends adoptable dogs based on the user’s in-app activity.

### For Android users:

Visit [Shelter-In-Pets](https://expo.io/@shelterinpets/ShelterInPets?release-channel=prod) to demo our app!

### For iPhone users:

Please refer to both "Getting Started" sections below to learn how you can try our app on your local machine!

### Table of Contents

- [Team](#Team)

- [Getting Started - Front End](#Getting-Started)

* [Getting Started - Back End](#Getting-Started)

- [Visual Tutorial](#Visual-Tutorial)

- [Tech Stack - Front End](#Tech-Stack---Front-End)
  - [React Native](#React-Native)
  - [Redux](#Redux)
  - [Expo](#Expo)
  - [Clarifai API](#Clarifai-API)

* [Tech Stack - Back End](#Tech-Stack---Back-End)
  - [Node.js](#Node.js)
  - [Express](#Express)
  - [PostgreSQL](#PostgreSQL)
  - [Petfinder API](#Petfinder-API)
  - [Heroku](#Heroku)

## Team

#### Kate Lee (that's me!)

> Github: https://github.com/katherinelee703
>
> LinkedIn: https://www.linkedin.com/in/katherinelee703/

#### Sonia Susanto

> Github: https://github.com/soniasusanto
>
> LinkedIn: https://www.linkedin.com/in/soniasusanto/

#### Angela Vuong

> Github: https://github.com/avuong12
>
> LinkedIn: https://www.linkedin.com/in/avuong12/

#### Laura Armfield-Perez

> Github: https://github.com/Larmfieldperez
>
> LinkedIn: https://www.linkedin.com/in/laura-armfield-perez/

## Getting Started - Front End

#### Note: This is the client side! You must clone the shelter-in-pets-server repo and follow the directions in the README.md https://github.com/sense-5/shelter-in-pets-server or see Getting Started #2 below!

To install Expo CLI:

```
npm install -g expo-cli
```

In one terminal:

```
cd <directory you want to download to>

git clone https://github.com/sense-5/shelter-in-pets.git

npm install

expo start
```

Go to http://localhost:19002/ to use Shelter in Pets!

## Getting Started - Back End

#### Note: This is the server side! You must clone the shelter-in-pets repo and follow the directions in the README.md https://github.com/sense-5/shelter-in-pets or see Getting Started #1 above!

```
In a separate terminal:

cd <directory you want to download to>

git clone https://github.com/sense-5/shelter-in-pets-server.git

npm install

npm start
```

## Visual Tutorial

After logging in, you can start by scrolling through all the dogs available for adoption. Upload a picture of a dog you want to search for. Select a sub-breed. Click on a dog and you will see more information.

![browseAndSelect](./assets/browseAndSelect.gif)

Use the filtered search feature to selected your desired dog attributes.

![filterSearchAndLike](./assets/filterSearchAndLike.gif)

Like a dog and you will see it on your list of Favorite Dogs.

![likeAndFavorites](./assets/likeAndFavorites.gif)

Click on "recommendations" and you can swipe through dogs recommended to you base on your view and like history. Once you have found your dog, you can contact the shelter via email, phone, or get the shelter location.

![recAndFinalPick](./assets/recAndFinalPick.gif)

## Tech Stack - Front End

### React Native

https://react-native.org/

- React Native is a JavaScript library for building mobile applications.

- React Native's framework that allows components to be built on top of other components with their own state.

### Redux

https://redux.js.org/

- Redux is a JavaScript library that allows for state management.

- Redux works with React Native and Node.js to build user interfaces by retrieving data from the database and manages state in the client side.

### Expo

https://expo.io/

- Expo is an open-source platform for developing and publishing native apps for Android, iOS, and web browser.

### Clarifai API

https://www.clarifai.com/

- Clarifai API is an image recognition service.

- Clarifai's predict API is called by passing in an image input. It will respond with a list of concepts and their corresponding probability scores. The probability score is the likelihood that the concepts are present within the image.

## Tech Stack - Back End

### Node.js

https://nodejs.org/en/

- Node.js is a Javascript runtime environment that is built on Chrome's V8 JavaScript engine

### Express

https://expressjs.com/

- Express is a web framework for Node.js with HTTP utility methods and middleware.

### PostgreSQL

https://www.postgresql.org/

- PostgreSQL is an open source object-relational database system that uses the SQL language.

### Petfinder API

https://www.petfinder.com/developers/

- Petfinder API allows access to Petfinder's database of adoptable pets and animal welfare organizations.

### Heroku

https://www.heroku.com/what

- Heroku is a cloud platform as a service that allows developers to build and deploy their applications.

## "[Cutest-Coffee-Clicker](https://0lxgcxllm9.execute-api.us-east-1.amazonaws.com/CoffeeClicker)"

### About

an homage to the 2013 hit game "Cookie Clicker"

In a single evening in August 2013, French web developer Julien "Orteil" Thiennot coded a simple browser-based game called "[Cookie Clicker](https://orteil.dashnet.org/cookieclicker/)", hoping to direct some traffic to his personal website while also having some fun. Overnight, the game attracted some 50,000 players. Within several months it was garnering 1.5 million page views per day. What began as a one-night project — and something of a joke — is now considered to be a founding entry in the genre of ["idle" or "incremental" games](https://en.wikipedia.org/wiki/Incremental_game), which account for a not insignificant percentage of the \$550 million in revenue generated annually by casual, mobile video games.

## [my-bias-book.com](https://github.com/mybiasbook/mbb#readme)

### About

Do you love following your favorite KPOP groups on SNS but wish there was a better way to share, organize, upvote, and comment on fan photos?

> Scouring places like Reddit, Twitter, Instagram, and Discord can take ages.

> My Bias Book is meant to sovle this problem by providing a comprehensive space for KPOP fan photograhpy.

> This gallery-style photo submission and upvoting site helps fan photographers showcase their skills and provide great content for their fanbases.

Who's your bias? Share with us @ [my-bias-book.com](https://www.my-bias-book.com)!

### Preview

Site currently under construction - please enjoy the preview before it goes live!

![site-preview-img](https://user-images.githubusercontent.com/58742933/112384428-69b2d500-8cbc-11eb-93e0-ef91f53dff92.jpg)
