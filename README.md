<h1 align=center>Flutter ❤</h1>

## What is Flutter?

- Flutter is a cross platform MAD framework that makes it easy for the developers to build beautiful apps for all screen sizes and devices.

- It comes with pre-built widgets that makes it easy to layout the apps.

## Why to choose Flutter?

- One codebase for android, iOS, Web, iot devices, web, etc.
- simple and flexible layout system
- Hot reload
- Open Source
- by Google
- for more [refer this](https://github.com/Rahullkumr/excelrflutter/blob/main/Notes/day1.md)

## Why Dart was selected for Flutter?

- Smooth transition animations at 60 fps (best for game dev)
- Automatically does Garbage Collection
- Compilation and Execution in Dart:
  - uses JIT and AOT compilation
  - JIT used during development (Hot Reload) and AOT (during release build) which compiles Dart code to Native machine code
- HOT RELOAD 
  - uses JIT compilation and builds the app within a second
- Easy syntax similar to c++ and java

```diff
- Almost all Modern programming languages can do these, what's special about Dart?

+ It's capability to transpile dart code that can target different architectures(runtimes) and hardwares
+ including x86(Desktop/laptops), ARM (Mobile devices) to even JavaScript Engines(Browsers)
```
- ARM = Advanced RISC(Reduced Instruction Set Computing) Machine

## flutter-00-helloWorld

```dart
import 'package:flutter/material.dart';

void main() {
  runApp(
    const MaterialApp(
      home: Center(
        child: Text("Hello World"),
      ),
    ),
  );
}
```
## The App
![](./helloWorld.jpg)

-----

Run any Flutter repository on Zapp website: <a href="https://zapp.run/assets/homepage/import-github.gif">refer this link </a>

List of all Flutter apps: <a href="https://github.com/Rahullkumr/Flutter-Projects-List">click here</a>
