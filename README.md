# Unified codbase for all web and mobile apps

Test UI library: https://www.npmjs.com/package/ayocodes_ui_library

If we install this package into any expo app and it will work as expected automatically.

If we install this package into react based web apps i.e vite, next.js etc... They will need to be configured to use react-native-dom instead of react-dom. We have a working example with vite in this repo.

1. test_ui_library is a vite web app for testing ui components and if the package works as expected. via ``npm link``
- npm link use-case: https://dev.to/dailydevtips1/how-to-test-your-npm-package-locally-2b6

2. a basic expo app

3. a vite app configured to use react-native-dom instead of react dom

4. ui library, which would exist along with the test ui library project in a different repo going forward.

Note: the package is currently public so anyone can techncally use it, however there are options to create private packages. 
