# Class 43 Reading: React Native

## Resources

- [Getting Started With React Native](https://reactnative.dev/docs/getting-started)
- [Expo](https://expo.dev/)
- [Expo Snack](https://snack.expo.dev/)
- [Ejecting](https://docs.expo.dev/archive/glossary/#eject?redirected)

## Getting Started With React Native

1. Name three core components of React Native and describe what they do.

    - [ ] Core Component 1: `<View>` - A container that supports layout with flexbox, style, some touch handling, and accessibility controls. `<View>` maps directly to the native view equivalent on whatever platform React Native is running on, whether that is a `UIView`, `<div>`, `android.view`, etc.
    - [ ] Core Component 2: `<Text>` - A React component for displaying text which supports nesting, styling, and touch handling. `<Text>` maps directly to the native text equivalent on whatever platform React Native is running on, whether that is a `UITextView`, `<p>`, `android.widget.TextView`, etc.
    - [ ] Core Component 3: `<Image>` - A React component for displaying different types of images, including network images, static resources, temporary local images, and images from local disk, such as the camera roll. `<Image>` maps directly to the native image equivalent on whatever platform React Native is running on, whether that is a `UIImageView`, `<img>`, `android.widget.ImageView`, etc.

2. What problem does React Native solve (why call it native)?

    - React Native allows you to build mobile apps using only JavaScript. It uses the same design as React, letting you compose a rich mobile UI from declarative components. It solves the problem of having to learn multiple languages and frameworks to build apps across different platforms. It's called native because it uses the same fundamental UI building blocks as regular iOS and Android apps.

3. What are the building blocks of a React Native app? How does that compare to a React app?

    - The building blocks of a React Native app are the same as a React app. The main difference is that React Native does not use HTML. Instead, it uses components that are similar to HTML elements. For example, `<View>` is similar to `<div>` and `<Text>` is similar to `<p>`.

## Expo

1. What solution does expo provide?

    - Expo is a framework and a platform for universal React applications. It is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

2. Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the _______ workflow.

    - Expo tries to manage as much of the complexity of building apps as possible, which is why we call it the "unimodular" workflow.

3. What is the difference between React Native and Expo?

    - React Native is a framework for building native apps using React. Expo is a set of tools and services built around React Native and native platforms that help you develop, build, deploy, and quickly iterate on iOS, Android, and web apps from the same JavaScript/TypeScript codebase.

## Expo Snack

1. Checkout this tool. What does snack allow you to do?

    - Expo Snack allows you to try React Native in your browser. It's an online editor that lets you code in React Native, instantly previewing your changes.

## Ejecting

1. What does "eject" mean within the context of Expo?

    - Ejecting means that you are opting out of Expo's build process and going back to using React Native's build tools.

2. When should you NOT eject?

    - You should not eject if you don't have a good reason to. Ejecting is permanent and cannot be undone. It's a one-way operation. If you are unsure, it's best to not eject.

3. Why might you choose to eject?

    - You might choose to eject if you need to add custom native functionality. For example, if you need to add a custom native module, you will need to eject.

### Tutorial

- [React Native Basics](https://reactnative.dev/docs/tutorial)

### Bookmark and Review

- [React Native](https://reactnative.dev/)

### Reflection

- [Class README](https://codefellows.github.io/code-401-javascript-guide/curriculum/class-41/)

1. What are your learning goals after reading and reviewing the class README?

    - [ ] Goal 1: Create a quality mobile application using React Native.

#### Things I Want to Know More About

1. Using React Native both solo an in a team setting.

![GIF](https://media.giphy.com/media/4tRr2ULBwiIA8/giphy.gif)
