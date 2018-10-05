# React Native PoC

## Install

Check install documentation on docs directory

## Install resume

- verify jdk8 installation
- verify nodejs and npm installation
- install chocolatey ...installed
- install python2 ...installed
- configure python2 with python3 ...configured
- install react-native-cli ...installed
- install android studio ...installed
- Execute Set-ExecutionPolicy Restricted ... done

## Common comands


- $ react-native init <project_name>
- $ react-native run-android // to create a bundle and with new native code
- $ react-native start // after first execution of run-android

bundler is responsible to package the app

run-android need executed into project folder

before run, open the android emulator

## Common react components

- $ npm install react-navigation
- $ npm install axios // api access

## Throubleshooting

### Python 3.0 installed

React Native needs python 2.7. If you have python 3.0 installed, rename python 3 executable to python3.exe and update path variable. Instal python 2.7 and test python and python3 commands.

### Babel

Babel would be throw an error: https://github.com/facebook/react-native/issues/21310

To fix babel, execute this steps:

- $ npm add @babel/runtime
- $ npm install (optional)
- $ react-native start
