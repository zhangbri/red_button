## Lab #4: Red Button

### Overview

Congratulations! 🎉 You have been selected by your dream company to participate in a debugging challenge that was designed to find the best talents in Android Development. The winners of this challenge will be granted a full-time offer in the company's Mobile Software Engineering department - this is a once in a lifetime opportunity!

### 🎯 Goals

By the end of this lab you will be able to...
- [X] Debug an app using Android Studio
- [X] Understand Views and view hierarchies
- [X] Understand interaction through click listeners
- [X] Understand View type casting

### Resources

- [Debugging in Android Studio](https://developer.android.com/studio/debug)
- [Debug your Layout with Layout Inspector](https://developer.android.com/studio/debug/layout-inspector) 
- [Write and View Logs with Logcat](https://developer.android.com/studio/debug/am-logcat)

## Lab Instructions

### Lab Setup

Before diving into the challenge, we need to clone the starter version of the app:

`https://github.com/driuft/redbutton-debugging-challenge.git`

### Challenges

#### Step 0: App Crashes

In this step, the app crashes automatically when launching.

- [X] Check `Logcat` for crash-related errors - are there any blue hyperlinks pointing to specific lines of code?
- [X] Make necessary changes in the code to allow the app to run

#### Step 1: Something Is Preventing Clicks

The app should now launch successfully, but there is something preventing interaction with the Blue button. Usually there is a [Ripple Animation](https://guides.codepath.com/android/ripple-animation) that occurs when the button is clicked, but nothing seems to be happening.

- [X] Open `activity_main.xml`
- [X] Find any View that might be obstructing our Button from being clicked and **modify/delete** it
- [X] Re-run the app

#### Step 2: A Wild Blue Button Appeared!

The blue button decided to celebrate Halloween early this year with a costume of the red button. It is telling us to check our layout file. Let's try to change the `visibility` of the blue button.

- [X] Open `activity_main.xml`
- [X] Change the visibility of the Button with id `blue_button` to `gone`
- [X] Re-run the app

#### Step 3: That Is One Tiny Yellow Button

There is now a tiny yellow button shown. It's a bit small to be interacted with, so let's try to increase its size.

💡 PRO TIP: Press and hold the _tiny_ button if you are feeling lucky today

- [X] Open `activity_main.xml`
- [X] Find the Button with id `tiny_yellow_button`
- [X] Change its size to allow easier interactivity
- [X] Re-run the app
- [X] Press and hold the Button to trigger its `longClickListener()`

#### Step 4: The Red Button

Is this the **real** red button? Has our journey finally come to an end? Only one way to find out.

- [X] Tap the red button

## Video Demo

Here's a video / GIF that demos all of the app's implemented features:

<p align="center">
  <img src='https://imgur.com/725ms3l.gif' title='Video Demo' width='' alt='Video Demo' />
</p>

GIF created with **ScreentoGif**

🎉 Congratulations, you've successfully completed the challenge! 🎉
You have shown that you are more than capable as an Engineer, and the company will be extending an offer. Now go change the world! 🚀
