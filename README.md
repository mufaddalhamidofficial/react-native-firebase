<p align="center">
  <a href="https://rnfirebase.io">
    <img width="160px" src="https://i.imgur.com/JIyBtKW.png"><br/>
  </a>
  <h2 align="center">React Native Firebase</h2>
</p>

<p align="center">
  <a href="https://www.npmjs.com/package/@react-native-firebase/app"><img src="https://img.shields.io/npm/dm/@react-native-firebase/app.svg?style=flat-square" alt="NPM downloads"></a>
  <a href="https://www.npmjs.com/package/@react-native-firebase/app"><img src="https://img.shields.io/npm/v/@react-native-firebase/app.svg?style=flat-square" alt="NPM version"></a>
  <a href="/LICENSE"><img src="https://img.shields.io/npm/l/@react-native-firebase/app.svg?style=flat-square" alt="License"></a>
  <a href="https://lerna.js.org/"><img src="https://img.shields.io/badge/maintained%20with-lerna-cc00ff.svg?style=flat-square" alt="Maintained with Lerna"></a>
</p>

<p align="center">
  <a href="https://invertase.link/discord"><img src="https://img.shields.io/discord/295953187817521152.svg?style=flat-square&colorA=7289da&label=Chat%20on%20Discord" alt="Chat on Discord"></a>
  <a href="https://twitter.com/rnfirebase"><img src="https://img.shields.io/twitter/follow/rnfirebase.svg?style=flat-square&colorA=1da1f2&colorB=&label=Follow%20on%20Twitter" alt="Follow on Twitter"></a>
  <a href="https://www.facebook.com/groups/rnfirebase"><img src="https://img.shields.io/badge/Follow%20on%20Facebook-4172B8?logo=facebook&style=flat-square&logoColor=fff" alt="Follow on Facebook"></a>
</p>

---

**React Native Firebase** is a collection of official React Native modules connecting you to Firebase services; each module is a light-weight JavaScript layer connecting you to the native Firebase SDKs for both iOS and Android.

React Native Firebase is built with four key principals in mind;

- ๐งช **Well tested**
  - every module is extensively tested to >95% coverage
- ๐ **Well typed**
  - first class support for Typescript included
- ๐ **Well documented**
  - full reference & installation documentation alongside detailed guides and FAQs
- ๐ฅ **Mirrors official Firebase Web SDK**
  - functions as a drop-in replacement for the Firebase Web SDK in React Native
  - maximizes cross-platform code re-usability e.g. re-using code on web platforms

## Firebase Modules

This is the root of the mono-repo for React Native Firebase, if you're looking for a specific package please select the package link from below.

The main package that you interface with is `App` (`@react-native-firebase/app`)

| Name                                                     | Downloads                                                                                                                                                                                       |                                                                                        
| -------------------------------------------------------- | :---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------: | 
| [AdMob](/packages/admob)                                 |               [![badge](https://img.shields.io/npm/dm/@react-native-firebase/admob.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/admob)               |
| [Analytics](/packages/analytics)                         |           [![badge](https://img.shields.io/npm/dm/@react-native-firebase/analytics.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/analytics)           |
| [App](/packages/app)                                     |                 [![badge](https://img.shields.io/npm/dm/@react-native-firebase/app.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/app)                 |
| [Authentication](/packages/auth)                         |                [![badge](https://img.shields.io/npm/dm/@react-native-firebase/auth.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/auth)                |
| [Cloud Firestore](/packages/firestore)                   |           [![badge](https://img.shields.io/npm/dm/@react-native-firebase/firestore.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/firestore)           |
| [Cloud Functions](/packages/functions)                   |           [![badge](https://img.shields.io/npm/dm/@react-native-firebase/functions.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/functions)           |
| [Cloud Messaging](/packages/messaging)                   |           [![badge](https://img.shields.io/npm/dm/@react-native-firebase/messaging.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/messaging)           |
| [Cloud Storage](/packages/storage)                       |             [![badge](https://img.shields.io/npm/dm/@react-native-firebase/storage.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/storage)             |
| [Crashlytics](/packages/crashlytics)                     |         [![badge](https://img.shields.io/npm/dm/@react-native-firebase/crashlytics.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/crashlytics)         |
| [Dynamic Links](/packages/dynamic-links)                 |       [![badge](https://img.shields.io/npm/dm/@react-native-firebase/dynamic-links.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/dynamic-links)       |
| [In-app Messaging](/packages/in-app-messaging)           |    [![badge](https://img.shields.io/npm/dm/@react-native-firebase/in-app-messaging.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/in-app-messaging)    |
| [Instance ID](/packages/iid)                             |                 [![badge](https://img.shields.io/npm/dm/@react-native-firebase/iid.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/iid)                 |
| [ML Kit Natural Language](/packages/ml-natural-language) | [![badge](https://img.shields.io/npm/dm/@react-native-firebase/ml-natural-language.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/ml-natural-language) |
| [ML Kit Vision](/packages/ml-vision)                     |           [![badge](https://img.shields.io/npm/dm/@react-native-firebase/ml-vision.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/ml-vision)           |
| [Performance Monitoring](/packages/perf)                 |                [![badge](https://img.shields.io/npm/dm/@react-native-firebase/perf.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/perf)                |
| [Realtime Database](/packages/database)                  |            [![badge](https://img.shields.io/npm/dm/@react-native-firebase/database.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/database)            |
| [Remote Config](/packages/remote-config)                 |       [![badge](https://img.shields.io/npm/dm/@react-native-firebase/remote-config.svg?style=for-the-badge&logo=npm)](https://www.npmjs.com/package/@react-native-firebase/remote-config)       |

## Documentation

- [Quick Start](https://rnfirebase.io/)
- [Reference API](https://rnfirebase.io/reference)

Looking for the Version 5 documentation? [View legacy documentation](https://v5.rnfirebase.io).

## Contributing

- [Overview](https://rnfirebase.io/contributing)
- [Issues & PRs](https://rnfirebase.io/contributing#issues--prs)
- [Documentation](https://rnfirebase.io/contributing#documentation)
- [Community](https://rnfirebase.io/contributing#community)
- [Code of Conduct](/CODE_OF_CONDUCT.md)

## License

- See [LICENSE](/LICENSE)

---

<p>
  <img align="left" width="75px" src="https://static.invertase.io/assets/invertase-logo-small.png">
  <p align="left">
    Built and maintained with ๐ by <a href="https://invertase.io">Invertase</a>.
  </p>
</p>

---
