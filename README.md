# CPU Performance in cross platform mobile development

Here you will find all the resources implemented on our research.

If you like to replicate the scenarios, please follow the steps below.

## Installation and run

The next steps should work only on ANDROID 📱.

1) First of all, you need to clone the repositories listed below.

[React Native John Conway's Game of Life implementation](https://github.com/radiumrocketapps/RN-Mobile-Performance)

[Ionic Framework John Conway's Game of Life implementation](https://github.com/radiumrocketapps/Ionic-Mobile-Performance)

[PWA John Conway's Game of Life implementation](https://github.com/radiumrocketapps/PWA-Mobile-Performance)

2) Then install the dependencies of each project and generate the APKs.

3) Then move the APKs to your mobile phone.

4) Connect your mobile device to your computer, and check if it is visible using the following command on your terminal

```
$ adb devices
```

The output should look like this

```bash
List of attached devices
335646534d473098     device
```

If you don't find your device listed, please check if the Developer mode is activated on your settings.

5) Clone and install the dependencies of the following repo.

[Read CPU script](https://github.com/radiumrocketapps/read-cpu-script)

6) Go to the Read CPU script directory and run

``` bash
$ npm start
```

## Configs

If you'd like to update the experiment params, go to the `src/constants/params.js` and update them.
