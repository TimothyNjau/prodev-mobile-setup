# Introuduction to Mobile development with React Native, TypeScript, NativeWindCSS
This repo is a demonstration of how to setup and use React Native in mobile development. We shall be using a combination of different tools to achieve mobile app development. The tools are React Native, TypeScript, NativeWindCSS, and Expo framework.

## React Native
This is an open-source framework for building cross-platform mobile applications using JavaScript and React. 
It allows developers to write code once and deploy it on both iOS and Android platforms.
React Native uses native components under the hood, ensuring that the apps look and feel like native applications.

## TypeScript
This is a strongly typed superset of JavaScript that adds optional static typing to the language. By using TypeScript in your React Native projects, you can:

1. Catch errors during development (rather than at runtime).
2. Improve code readability and maintainability.
3. Enhance developer productivity with better tooling and autocompletion.
4. Scale your application more effectively as it grows in complexity.

## NativeWindCSS
This is a **utility-first CSS framework** tailored for React Native. It allows you to style your components using a set of pre-defined utility classes, similar to TailwindCSS.
It allows you to: 
1. Write styles directly in JSX using class names.
2. Maintain consistent design system acroos application.
3. Reduce need to write custom CSS.
4. Leverage responsive design and dark mode support effortlessly.

## Expo framework
This is a framework and platform built on top of React Native that simplifies the development process. It provides a set of tools and services that make it easier to build, deploy, and manage React Native applications.
Its benefits include: 
1. **Quick setup**: Expo handles the complex configuration of native code, so you can focus on building your app.
2. **Expo Go**: A development client that allows you to test your app on physical devices without needing to build it.
3. **Pre-built components**: Access to a wide range of pre-built UI components and APIs (e.g., camera, maps, notifications).
4. **Over-the-air updates**: Push updates to your app without going through the app store approval process.

# Set Up Development Environment
Before we start, we neeed to ensure that we have the foolwoing installed: 
* Node.js (v16 or higher)
* Expo CLI (_npx create-expo-app_)
* Code editor (VS Code)
## Create a New Expo Project
To create a new Expo project with TypeScript, run the following command in your project directory: `npx create-expo-app AppName`.
This creates a local Expo CLI in each project, which is smaller, lighter and faster version. 

## Run Your App
To start the app and load it on the development server, use the command: `npx expo start` or `npx expo`