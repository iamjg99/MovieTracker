<p align="center">
  <h3 align="center">MovieTracker: The Movie Guide</h3>
</p>

---

[![supports iOS](https://img.shields.io/badge/iOS-4630EB.svg?style=flat-square&logo=APPLE&labelColor=999999&logoColor=fff)](https://expo.io/@murillo94/cine-the-movie-guide)
[![supports Android](https://img.shields.io/badge/Android-4630EB.svg?style=flat-square&logo=ANDROID&labelColor=A4C639&logoColor=fff)](https://expo.io/@murillo94/cine-the-movie-guide)
[![supports web](https://img.shields.io/badge/web-4630EB.svg?style=flat-square&logo=GOOGLE-CHROME&labelColor=4285F4&logoColor=fff)](https://cine-the-guide-movie.vercel.app/)

MovieTracker is your movie guide. The fastest and easiest way to find Movies, Actors and Series on your device. Know about ratings and reviews from The Movie Database (TMDb).

![MovieTracker: The Movie Guide](./resources/demo.png)

## Architecture

MovieTracker was built to run on iOS, Android, Web and PWA. It uses [Expo](https://expo.io/) as a core lib to build and distribute to all the platforms.

### Libs

- [react-navigation](https://github.com/react-navigation/react-navigation)
- [react-native-modalize](https://github.com/jeremybarbet/react-native-modalize)
- [react-native-web](https://github.com/necolas/react-native-web)
- [react-native-image-viewing](https://github.com/jobtoday/react-native-image-viewing)
- [react-native-responsive-dimensions](https://github.com/react-native-toolkit/react-native-responsive-dimensions#readme)

### APIs

- [TMDb](https://developers.themoviedb.org/3/getting-started/introduction)


## Testing on your phone

You can download the app on Expo App or scan the below QR code to open the project on Android and iOS if you already have the Expo app:

<img alt="Cine: The Movie Guide" src="./resources/qrcode.png" height="150" width="150" />

## Running locally

As others projects, you will need some requirements to run:

#### Requirements

- [Node.js](https://nodejs.org/) (latest)
- [Expo](https://expo.io/) (latest)
- [Yarn](https://yarnpkg.com/) (latest)

#### How to run

- `git clone git@github.com:murillo94/cine-the-guide-movie.git`
- `yarn install`

Now, you can choose a command to run the project:

- `yarn ios` to run on iOS simulator
- `yarn android` to run on Android simulator
- `yarn web` to run on web browser

## Deploying

Expo provides simple ways to build and deploy your app with singles commands:

### iOS and Android

The app deploy runs on CI and the commands are scopped on a `yaml` file check it [here](./.github/workflows/publish.yml)


