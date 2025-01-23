This repository contains a simple example of a TypeError in React Native. The error occurs when a component expects a number but receives a string. The solution is to convert the string to a number before passing it to the component. 

## Steps to reproduce

1. Clone the repository
2. Run `npm install`
3. Run `react-native run-android` or `react-native run-ios`
4. Observe the error message in the console

## Solution

The solution is to convert the string to a number before passing it to the component. This can be done using the `parseInt()` function.