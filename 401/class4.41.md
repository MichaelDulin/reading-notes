# Class 4.1 Reading Assignment

[Back to main](https://michaeldulin.github.io/reading-notes)

**Resources from Class 1**
- [getting started with react native](https://facebook.github.io/react-native/docs/getting-started)
- [expo](https://expo.io/)
- [expo snack](https://snack.expo.io/)
- [ejecting](https://docs.expo.io/versions/latest/expokit/eject)
- [react native basics](https://facebook.github.io/react-native/docs/tutorial)
- [react native](https://facebook.github.io/react-native/)

****

**Getting Started With React Native**
1. Name three Core Components of React Native and describe what they do.
  - View:
    - This is the fundamental component for building a user interface in React Native. It's similar to a div in HTML and is used for grouping other components.
  - Text:
    - This is the basic component for displaying text. It is similar to the span or p in HTML.
  - Stylesheet:
    - It's a component used for defining styles in React Native. It allows you to create an object that contains styles you can apply to your components.
2. What problem does React Native solve (why call it native)?
  - React Native solves the problem of writing multiple codebases for different platforms (iOS, Android). Instead, you write one codebase in JavaScript and React. The "native" part refers to React Native's ability to generate components that use native platform UI, not WebView-based UI, providing better performance and a look-and-feel consistent with other apps on the platform.
3. What are the building blocks of a React Native app? How does that compare to a React app?
  - The building blocks of a React Native app are components, which are JavaScript classes or functions that optionally accept inputs (called "props") and return a React element that describes how a section of the UI should appear. The core components include View, Text, Image, ScrollView, and StyleSheet, among others. This is similar to a React app where components are also the building blocks, but instead of rendering to native components, they render to web components like divs, spans, etc.

****

  
**Expo**
1. What solution does expo provide?
  - Expo provides a solution that simplifies the process of developing, building, deploying, and iterating on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.
2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the ____ workflow.
  - Managed
3. What is the difference between React Native and Expo?
  - The main difference between React Native and Expo is that while React Native is a framework for building native apps using JavaScript and React, Expo is a set of tools and services built around React Native, aiming to simplify the development process. Expo includes a CLI, APIs, and a web-based GUI, making it easier to start a project, handle dependencies, and bundle your app.

****

**Expo-Snack**
1. Checkout this tool. What does snack allow you to do?
  - Expo Snack is an online tool that allows you to write and run complete React Native projects in your browser without needing to set up a development environment or even download anything. It's like a "code sandbox" for React Native. You can experiment with different Expo APIs, share your projects, and even open them directly on a phone or emulator. It's a fantastic tool for learning React Native and for rapidly prototyping ideas.
  
****
  
**Ejecting**
1. What does “eject” mean within the context of Expo?
  - Ejecting refers to the process of transitioning your Expo-managed project to a bare React Native project. It provides more control over the native side of your application, allowing you to include custom native modules which are not supported by Expo.
2. When should you not eject?
  - You should not eject if you want to continue taking advantage of Expo's simplified build process, OTA updates, and the other built-in Expo services, or if your app doesn't require any custom native code or specific native APIs outside of what Expo provides.
3. Why might you choose to eject?
  - You might choose to eject if you need more flexibility and control over your project, specifically when you need to use custom native modules or native APIs that are not included in the Expo managed workflow

****


## Things I want to know more about
