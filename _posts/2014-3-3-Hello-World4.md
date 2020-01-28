---
layout: post
title: How to use Native Android functions in React Native (ie. Native Bridging)
---
Hello guys Today we will discuss how we can expose Android Native functions for React Native. Regardless of a lot of theories  
we will discuss only os steps--

## Follow Bellow Steps to expose a function for Java Script

1. Open Android project in android studio
2. Create a Function Container Java Class with he help of ReactContextBaseJavaModule Class in your Android Package
3. Create React Package with he help of ReactPackage Class in your Android Package
4. Register your package

### Lets discuss each step one by one

#### 1. Open Android project in android studio

#### Follow these steps
a. Simply open android Studio
b. Click on File Menu 
c. Click on Open 
d. Open android folder of your React Native Project
