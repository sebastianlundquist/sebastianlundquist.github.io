# The Complete Android Oreo Developer Course
In October 2019 I [completed](https://udemy-certificate.s3.amazonaws.com/pdf/UC-S3HAZ49R.pdf) this course in native Android development with Java and Kotlin, and became a certified[[1]](CCA-Certificate-Java-Level-2-Sebastian-Lundquist.pdf)[[2]](CCA-Certificate-Java-Level-2-Sebastian-Lundquist.pdf) Java developer in the process! The course was taught by Rob Percival and Nick Walter. This post showcases the projects developed alongside the course.

## Snapchat Clone
This app was written entirely in Kotlin and uses Firebase to store and send photos and messages between registered users. The photos and messages get automatically deleted when they are opened.

[View on GitHub](https://github.com/sebastianlundquist/snapshot)

### What This Project Taught Me
* How to authenticate, sign in and out users in Firebase with Kotlin
* How to upload images to Firebase
* How to use the Firebase realtime database
* How to create bitmaps and image views with a 1:1 aspect ratio
* How to use UUID to create unique strings
* How to clear the back button history
* How to use Kotlin nullable and non-nullable shorthands

### Snapshot in Action
![Snapshot gif](https://raw.github.com/sebastianlundquist/snapshot/master/snapshot.gif)

## Uber Clone
This app allows the user to login as either a rider to request for an Џвєг or a driver to accept nearby requests. The rider gets notified when their request has been accepted and can follow the driver on the map. The driver sees where the rider is on the map, and gets directions when the request is accepted. This app expands upon many concepts previously taught in the course, focusing on Google Maps functionality and Parse server storage and authentication.

[View on GitHub](https://github.com/sebastianlundquist/uber)

### What This Project Taught Me
* How to login anonymously with Parse
* How to manipulate a Google Maps activity

### The Driver's View
![Uber Driver gif](https://raw.github.com/sebastianlundquist/uber/master/uber-driver.gif)

### The Rider's View
![Uber Rider gif](https://raw.github.com/sebastianlundquist/uber/master/uber-rider.gif)

## Flappy Bird and Super Mario Run Clones
These games were developed using the java library libGDX.

[View Floppy Birb on GitHub](https://github.com/sebastianlundquist/floppy-birb)

[View Coin Man on GitHub](https://github.com/sebastianlundquist/coin-man)

### What These Projects Taught Me
* How to develop mobile games with libGDX

### Floppy Birb in Action
![Floppy Birb gif](https://raw.github.com/sebastianlundquist/floppy-birb/master/floppy-birb.gif)

### Coin Man in Action
![Coin Man gif](https://raw.github.com/sebastianlundquist/coin-man/master/coin-man.gif)

## Twitter Clone
This app uses Parse to allow users to post "tweets" and view tweets from the users they decide to follow.

[View on GitHub](https://github.com/sebastianlundquist/twotter)

### What This Project Taught Me
* How to use multiple choice lists
* How to build custom list views

### Twotter in Action
![Twotter gif](https://raw.github.com/sebastianlundquist/twotter/master/twotter.gif)

## WhatsApp Clone
This messenger app uses Parse to send messages between registered users.

[View on GitHub](https://github.com/sebastianlundquist/wazzapp)

### What This Project Taught Me
* How to merge multiple Parse queries into one
* How to auto-scroll a list view

### WazzApp in Action
![Wazzapp gif](https://raw.github.com/sebastianlundquist/wazzapp/master/wazzapp.gif)

## Instagram Clone
This app uses Parse server to allow users to upload photos and view the feeds of other users.

[View on GitHub](https://github.com/sebastianlundquist/instagran)

### What This Project Taught Me
* How to setup a Parse server
* How to authenticate users with Parse
* How to upload photos to Parse
* How to work with Parse queries
* How to wait for a result from a started activity
* How to set layout parameters programmatically
* How to override key events

### Instagran in Action
![Instagran gif](https://raw.github.com/sebastianlundquist/instagran/master/instagran-compressed.gif)

## Android Wear Counter App
This simple app runs on your smartwatch and counts people (or anything, really).

[View on GitHub](https://github.com/sebastianlundquist/people-counter)

### What This Android Wear Mini Course Taught Me
* How to setup an Android Wear project
* How to accommodate for both round and square watch faces
* How to recognize speech input
* How to connect the watch to a smartphone
* How to get notifications in the watch
* How to build custom watch faces

### People Counter in Action
![People Counter gif](https://raw.github.com/sebastianlundquist/people-counter/master/people-counter.gif)

## Bluetooth Discovery
This app lists nearby Bluetooth devices.

[View on GitHub](https://github.com/sebastianlundquist/bluetooth-discovery)

### What This Project Taught Me
* How to use BroadcastReceivers, BluetoothDevices and BluetoothAdapters
* How to work with IntentFilters

### Bluetooth Discovery in Action
![Bluetooth Discovery gif](https://raw.github.com/sebastianlundquist/bluetooth-discovery/master/bluetooth-discovery.gif)

## Hacker News
This app allows the user to read news articles from Hacker News.

[View on GitHub](https://github.com/sebastianlundquist/hacker-news)

### What This Project Taught Me
* How to setup and query SQLite databases in Android
* How to use WebViews

### Hacker News in Action
![Hacker News gif](https://raw.github.com/sebastianlundquist/hacker-news/master/hacker-news.gif)

## Notes
This app allows the user to take notes and save them to their device.

[View on GitHub](https://github.com/sebastianlundquist/notes)

### What This Project Taught Me
* How to save user data to and read from SharedPreferences
* How to customize the action bar and add menus
* How to use Alert Dialogs

### Notes in Action
![Notes gif](https://raw.github.com/sebastianlundquist/notes/master/notes.gif)

## Memorable Places
This app allows the user to put markers on a map for places they've been to and want to remember.

[View on GitHub](https://github.com/sebastianlundquist/memorable-places)

### What This Project Taught Me
* How to integrate Google Maps in your Android app
* How to customize the appearance of the map
* How to show the user's location on the map
* How to use Intents to pass information and start new Activities

### Memorable Places in Action
![Memorable Places gif](https://raw.github.com/sebastianlundquist/memorable-places/master/memorable-places.gif)

## Hiker's Watch
This app shows exactly where you are in the world. Useful if you ever get lost.

[View on GitHub](https://github.com/sebastianlundquist/hikers-watch)

### What This Project Taught Me
* How to request for user permissions and handle when they are given
* How to get the current and last known location of the device
* How to use GeoCoder to get the address from the device's coordinates
* How to hide the app bar
* How to execute different code for different Android versions

### Hiker's Watch in Action
![Hiker's Watch](https://raw.github.com/sebastianlundquist/hikers-watch/master/hikers-watch.png)

## What's the Weather?
This weather app uses the OpenWeatherMap API to display the weather conditions of a chosen location.

[View on GitHub](https://github.com/sebastianlundquist/whats-the-weather)

### What This Project Taught Me
* How to process JSON in Java
* Regex in Java
* How to select multiple layout elements and edit all their properties at once!

### What's the Weather? in Action
![What's the Weather? gif](https://raw.github.com/sebastianlundquist/whats-the-weather/master/whats-the-weather.gif)

## Guess the Celebrity
This game shows pictures of celebrities (dogs) and challenges the player to guess who it is. The project teaches how you can download and parse HTML in your Android app, but probably shouldn't.

[View on GitHub](https://github.com/sebastianlundquist/guess-the-celebrity)

### What This Project Taught Me
* How to download and parse HTML pages
* Advanced string manipulation in Java

### Guess the Celebrity in Action
![Guess the Celebrity gif](https://raw.github.com/sebastianlundquist/guess-the-celebrity/master/guess-the-celebrity.gif)

## Brain Trainer
This game challenges the player to answer as many simple math questions as possible before the time runs out.

[View on GitHub](https://github.com/sebastianlundquist/brain-trainer)

### What This Project Taught Me
* How to toggle visibility of elements

### Brain Trainer in Action
![Brain Trainer gif](https://raw.github.com/sebastianlundquist/brain-trainer/master/brain-trainer.gif)

## Egg Timer
This project introduces timers and plays a sound when the time runs out.

[View on GitHub](https://github.com/sebastianlundquist/egg-timer)

### What This Project Taught Me
* How to use Handlers, Runnables and CountDownTimers
* How to update the state of UI components programmatically

### Egg Timer in Action
![Egg Timer gif](https://raw.github.com/sebastianlundquist/egg-timer/master/egg-timer.gif)

## Multiplication Tables
This app uses a list view and a slider to display the different multiplication tables.

[View on GitHub](https://github.com/sebastianlundquist/multiplication-tables)

### What This Project Taught Me
* How to use list views and adapters
* How to use different types of list items
* How to use sliders

### Multiplication Tables in Action
![Multiplication Tables gif](https://raw.github.com/sebastianlundquist/multiplication-tables/master/multiplication-tables.gif)

## Basic Phrases
This app plays audio recordings of simple phrases in French.

[View on GitHub](https://github.com/sebastianlundquist/basic-phrases)

### What This Project Taught Me
* How to add audio assets to Android projects
* How to use the media player
* How to control audio and volume

### Basic Phrases in Action
![Basic Phrases](https://raw.github.com/sebastianlundquist/basic-phrases/master/basic-phrases.png)

## Connect Three
This tic-tac-toe style game uses animations to become a little more exciting.

[View on GitHub](https://github.com/sebastianlundquist/connect-three)

### What This Project Taught Me
* How to implement different kinds of animations
* How to combine several animations into one
* How to use tags

### Connect Three in Action
![Connect Three gif](https://raw.github.com/sebastianlundquist/connect-three/master/connect-three.gif)

## Higher or Lower? and Number Shapes
These simple projects teach the fundamentals of Java Android development.

[View Higher or Lower? on GitHub](https://github.com/sebastianlundquist/higher-or-lower)

[View Number Shapes on GitHub](https://github.com/sebastianlundquist/number-shapes)

### What These Projects Taught Me
* Java syntax and fundamentals

### Higher or Lower? in Action
![Higher or Lower? gif](https://raw.github.com/sebastianlundquist/higher-or-lower/master/higher-or-lower.gif)

### Number Shapes in Action
![Currency Converter gif](https://raw.github.com/sebastianlundquist/number-shapes/master/number-shapes.gif)

## Currency Converter
This is the first app developed in the course and the project teaches the basics of setting up Android Studio projects, Android concepts and terminology, creating activities and editing layouts.

[View on GitHub](https://github.com/sebastianlundquist/currency-converter)

### What This Project Taught Me
* How to edit layout XML files in Android Studio
* How different layout constraints work
* How to use gravity to align elements
* How to use savedInstanceState
* How to debug in Android Studio
* How to use different types of text input
* How to display Toast messages
* How to use sp for accessibility scaling

### Currency Converter in Action
![Currency Converter gif](https://raw.github.com/sebastianlundquist/currency-converter/master/currency-converter.gif)

## Extras
These are other things I learned that are not associated with a specific app:
* How to use adaptive icons
* How to use custom fonts
* How to play video
* How to use autofill and autocomplete
* How to use PictureInPicture mode
* How to setup AR Core projects
* How to Daydream VR projects
