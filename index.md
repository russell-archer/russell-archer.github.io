---
layout: page
title: Russell Archer
subtitle: Portfolio for Russell Archer
bigimg: /img/notebook-886532_1920.jpg
---

I'm a software developer based in London and Sevenoaks, UK, where I'm currently creating iOS apps with Swift.
I have over 30 years experience in the industry in many different roles and with a range of technologies.

<p align="center">
    <img src="./img/designCons-2.png" />
</p>

<p align="center">
    Contact me for availability for iOS app development projects and contracts:
</p>

<p align="center">
	<a href="https://github.com/russell-archer">
		<img src="https://img.shields.io/static/v1?style=flat-square&logo=GitHub&label=GitHub&message=Russell%20Archer&color=lightgray">
	</a>
    <a href="https://twitter.com/Russell_Archer">
		<img src="https://img.shields.io/static/v1?style=flat-square&logo=Twitter&label=Twitter&message=Russell%20Archer&color=00ACEE">
	</a>
	<a href="mailto:russell.archer@mac.com">
		<img src="https://img.shields.io/static/v1?style=flat-square&logo=Apple&label=Email&message=Russell%20Archer&color=F76831">
	</a>
	<a href="./russell-archer-cv-short.pdf">
		<img src="https://img.shields.io/static/v1?style=flat-square&logo=Adobe-Acrobat-Reader&label=CV&message=PDF&color=green">
	</a>
</p>

<hr />
<h1 align="center">Recent App Store Projects</h1>
<p>&nbsp;</p>

<p align="center">
    <img src="./img/writerly-icon-rounded.png" />
</p>
<h2 align="center">
    <a href="https://russell-archer.github.io/Writerly/">Writerly</a>
</h2>

<p align="center">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=Apple&label=Platform&message=iOS&color=green">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=Swift&label=Language&message=Swift&color=FA7343">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=Firebase&label=Analytics&message=Firebase&color=FFCA28">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=UIKit&label=Framework&message=UIKit&color=2396F3">
    <img src="https://img.shields.io/static/v1?label=Framework&message=StoreKit&color=941100">
    <img src="https://img.shields.io/static/v1?label=Framework&message=MapKit&color=942192">
</p>

<h3 align="center"><em>Inspiration for Writers</em></h3>

**Writerly** is an iOS app designed to help users improve their creative writing through a series of techniques, tools, exercises,
and quests. It includes a number of "generators" that are used to create random *characters*, *moods*, *scenarios*, *locations*,
writing *prompts*, etc. I developed the app in cooperation with an award-winning creative writing tutor and author.

In-app purchases allow the user to add functionality related to specific creative writing concepts, such as character development.
However, the app has been designed to provide real benefits to the user without cost. The free app isn't merely a vehicle for in-app
purchases.

Technically, the main features of the app are:

* Developed in *Swift* (currently Swift 5)

* A *UISplitViewController* allows selection of topic in the left (master) pane, with the a page of content shown in the right (detail) pane

* Content is broken into *modules*, *topics*, *sub-topics* and *pages*, with the entire structure of the app's content defined as a collection of dictionaries in a *.plist* file, allowing for easy changes and additions

* Navigation between *pages* uses a *UISwipeGestureRecognizer* to support swipe-left to advance to the next topic and swipe-right to go to the previous topic

* Many exercises are timed and *notifications* are used to alert the user when their time is up

* To enable easy changes and additions, text content is defined as *HTML/Javascript* and hosted in a *WKWebView*

* Two-way message interop between the iOS core of the app and Javascript uses *WebKit*'s ability to evaluate JavaScript statements and handle in-coming messages from Javascript (*WKScriptMessageHandler*)

* In-app purchases are made and restored using *StoreKit* and receipts validated using *OpenSSL*

* Analytics was initially done via *Fabric Crashlytics and Answers* (now moved to *Google Firebase*)

<p align="center">
    <img src="./img/writerly-ad1.png" />  
</p>

<p align="center">
    <img src="./img/writerly-ss1.png" />
    <img src="./img/writerly-ss4.png" />    
    <img src="./img/writerly-ss5.png" />    
</p>

<hr />

<p align="center">
    <img src="./img/retreev-icon-rounded.png" />
</p>
<h2 align="center">
    <a href="https://russell-archer.github.io/Retreev/">Retreev</a>
</h2>

Repo: **Private**<br/>
Documentation: [Public documentation available](https://russell-archer.github.io/Retreev/)<br/>

<p align="center">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=Apple&label=Platform&message=iOS&color=green">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=Swift&label=Language&message=Swift&color=FA7343">
    <img src="https://img.shields.io/static/v1?style=flat-square&logo=UIKit&label=Framework&message=UIKit&color=2396F3">
    <img src="https://img.shields.io/static/v1?label=Framework&message=MapKit&color=942192">
</p>

*When you really need a ride home.*

**Retreev** was developed in reponse to a simple, but common problem: how to request a ride home from a parent or friend
and let them know exactly where you are!

<p align="center">
    <img src="./img/retreev-quote-big.jpg" />
</p>

<p align="center">
    <img src="./img/retreev-ss1.png" />
    <img src="./img/retreev-ss2.png" />    
    <img src="./img/retreev-ss3.png" />    
</p>

<hr />
<h2 align="center">Recent Projects</h2>

[Sign in with Apple](https://github.com/russell-archer/AppleSignInDemo)<br/>
How to use the new Sign in with Apple service in a UIKit and iOS 13 app.

[Speech Dictation Demo](https://github.com/russell-archer/SpeechDictationDemo)<br/>
An iOS speech recognition demo that transcribes live speech.

[Dark Mode. Updating an existing App Store app](https://github.com/russell-archer/DarkModeDemo-UIKit)<br/>
Preparing for iOS 13 Dark Mode.

[iOS 13 Modal Styles Demo](https://github.com/russell-archer/ModalStylesDemo)<br/>
Exploring the differences between presentViewController and pushViewController with new iOS 13 modal presentation styles.

[Context Menu Demo](https://github.com/russell-archer/ContextMenuDemo)<br/>
How to display a context menu in iOS 13.

[Image API Alamofire](https://github.com/russell-archer/ImageApiAlamofire)<br/>
Alamofire Pixabay Image API Demo with Swift Package Manager.

[SwiftUI and Combine Notifications](https://github.com/russell-archer/SwiftUI-Combine-NotificationDemo)<br/>
Using SwiftUI and Combine extensions to NotificationCenter.

[SwiftUI Hosting UIKit Views](https://github.com/russell-archer/SwiftUI-SwiftUIHostingUIKit)<br/>
How to use UIKit UIView and UIViewController in SwiftUI.

[Hosting SwiftUI Views in UIKit](https://github.com/russell-archer/SwiftUI-UIKitHostingSwiftUI)<br/>
Using UIHostingController to display a SwiftUI View in a UIKit app.

[SwiftUI State](https://github.com/russell-archer/SwiftUI-StateDemo)<br/>
Using state and binding to create a UI that responds to user input to modify internal state.

[SwiftUI Navigation Bar](https://github.com/russell-archer/SwiftUI-NavBarDemo)<br/>
How to select either large navigation bar (the default) or a small, inline bar.

[SwiftUI List](https://github.com/russell-archer/SwiftUI-ListDemo)<br/>
Creating an editable list with SwiftUI with support for navigation.

[SwiftUI Image API](https://github.com/russell-archer/SwiftUI-ImageAPIDemo)<br/>
Using SwiftUI to consume REST API with image data.

[SwiftUI Alert](https://github.com/russell-archer/SwiftUI-AlertDemo)<br/>
Using SwiftUI to display alerts, actionsheets and popovers.

[Hangman Game](https://github.com/russell-archer/Hangman)<br/>
Simple, non-graphical Hangman game.

[Siri Shortcuts. Show Random Color Demo](https://github.com/russell-archer/ShowRandomColor)<br/>
Demo of Siri shortcuts for iOS 12 using Intents.

[Siri Shortcuts. PicSearch](https://github.com/russell-archer/PicSearch)<br/>
Demo of Siri shortcuts for iOS 12 using NSUserActivity.

[Pixabay Image API Demo](https://github.com/russell-archer/ImageApiDemo)<br/>
App that requests image data using the Pixabay API.

[Cal Demo](https://github.com/russell-archer/CalDemo)<br/>
Demo for getting events from iOS calendars.
