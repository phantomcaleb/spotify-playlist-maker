## Getting started

### Server

#### Pre-requisites

- Python 3

#### Installation

```
pip install pipenv
cd server
pipenv install
```

#### Running the server

```
pipenv shell
python app.py
```

### Android Client

#### Pre-requisities

- Node.JS
- [Expo Client](https://play.google.com/store/apps/details?id=host.exp.exponent&hl=en)
- [adb](https://android.gadgethacks.com/how-to/android-basics-install-adb-fastboot-mac-linux-windows-0164225/)

#### Installation

```
cd client
npm install
```

Enable USB Debugging on your Android device.

#### Running the app

1. Plug in Android device via USB
2. [Connect to the local server](https://facebook.github.io/react-native/docs/running-on-device#method-1-using-adb-reverse-recommended)
3. `npm start`
4. Select `Run on Android device/emulator`
