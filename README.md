# 📦 Android Room Database Example

This is a simple example of using **Room Database** in an Android app using **Kotlin**.
You can use it as a boilerplate to start your own offline-first Android apps.

## 🛠️ Tech Stack

- Kotlin
- Room Persistence Library

## 📲 Features

- Insert notes into local Room DB
- View all saved notes
- Delete notes

## 🧠 Project Structure



🔧 Dependencies (in build.gradle)
Make sure to add these in your app-level build.gradle:
// Room components
implementation "androidx.room:room-runtime:2.6.1"
kapt "androidx.room:room-compiler:2.6.1"


Also, enable kapt at the top:
apply plugin: 'kotlin-kapt'
