# anova-react-native-guide
Just my compilation to start react native project

## Project creation
You can use either the [create-react-native-app](https://facebook.github.io/react-native/docs/getting-started.html) (CRNA) that will be run from Expo XDE, or using the react-native init.

## Development environment
We can use the traditional run on the device/simulator from the react-native run-android/run-ios. But now there is [Expo XDE](https://expo.io/). This is a multi-platform development solution, so you can test on both android or ios.

## Built-in database
Several built-in database are commonly used for react native:
1. [Realm](https://blog.realm.io/introducing-realm-react-native/). Its getting famous now because of the speed. 
2. We can use the out-of-the-box solution from react native, using [AsyncStorage](https://facebook.github.io/react-native/docs/asyncstorage.html). It will use RocksDB or SQLite on what is available.

## Redux related library
In react, state management is important, thats why we use redux. These are the needed library for that:
1. [redux](https://github.com/reactjs/redux)
2. [react-redux](https://github.com/reactjs/react-redux)
3. [redux-promise](https://github.com/acdlite/redux-promise) 

## Form validation
Still research for this

## Request or post to API
We can use the new fetch() method (https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch). But I think [axios](https://github.com/axios/axios) is doing nice job.

## Login and authentication
Read this nice [article](https://medium.com/the-many/adding-login-and-authentication-sections-to-your-react-or-react-native-app-7767fd251bd1) on how implement login and authentication, and it works with react-router.

## React routing
There's no doubt you need to have [react-router](https://github.com/ReactTraining/react-router) for your routing needs, it has routing support for react native as well. Read the article [here](https://medium.com/@pshrmn/a-simple-react-router-v4-tutorial-7f23ff27adf)

## UI purposes (CSS frameworks)
Its a bit tricky for react-native, but i manage to compose a list for react-native UI kit:
1. [Native Base](http://nativebase.io/)
2. [UI Kitten](https://akveo.github.io/react-native-ui-kitten/#/home), note: you cannot use the example on Expo XDE due to the usage or realm.
3. [Nachos UI Kit](https://avocode.com/nachos-ui#get-started)

## Code convention
I think the Airbnb code convention are nice to follow (https://github.com/airbnb/javascript/tree/master/react).

## Google maps component
Use [this](https://github.com/tomchentw/react-google-maps) component, its the most complete for now
