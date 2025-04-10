# E-commerce-ReactNative
react-native installation -> npx create-expo-app <appname>
cd <appname>
npm start
__________________________________________________________________________________________________________________

-> For reloading app, press 'r'
__________________________________________________________________________________________________________________

For installing navinagtion -> First stop running server - npm install @react-navigation/native
npx expo install react-native-screens react-native-safe-area-context
npm install @react-navigation/native-stack

-> Check in package.json{
    "@react-navigation/native": "^7.1.6",
    "@react-navigation/native-stack": "^7.3.10",
    "react-native-safe-area-context": "4.12.0",
    "react-native-screens": "~4.4.0"
}

-> https://reactnavigation.org/docs/hello-react-navigation

-> In App.js,
import { NavigationContainer } from "@react-navigation/native";
import { createNativeStackNavigator } from "@react-navigation/native-stack";
__________________________________________________________________________________________________________________

ShortCut - rnfe
__________________________________________________________________________________________________________________

For Icons -> First stop running server - npm install --save react-native-vector-icons

-> Check in package.json{
    "react-native-vector-icons": "^10.2.0"
}

-> https://www.npmjs.com/package/react-native-vector-icons

-> In respective js/jsx file,
import FontAwesome from 'react-native-vector-icons/FontAwesome';
