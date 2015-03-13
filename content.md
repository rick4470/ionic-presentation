### Ionic: Advanced HTML5 Hybrid Mobile apps
Building a mobile app, can be a challenge to build if you decide to build a native application. Not only do you have to maintain code bases for each of the platforms you have to develop for you also have to deal with platform specific bugs and quirks. In the past years developing your application using HTML5 was frowned upon from developers to users, no one enjoyed having to maintain or create one. But as with any web technology this is quickly changing, with standards being completed and browsers starting to agree on common grown on issues we are seeing amazing advancement happening in this space.

For example on 28 October 2014, HTML5 was released as a stable W3C recommended standard. But it does not end their, more and more releases are being added to both CSS3 and JS, as of August 2014, ECMAScript 6 is already feature frozen meaning that we are in the last parts of the software development cycle for ECMAScript 6.

What does all this mean? it means as developers we can start putting to use some of our existing knowledge about the web development to start developing mobile applications that can have a competitive edge against the native counter parts. With shorter development life cycles, and with speed that will have you thinking twice if it was native or an HTML5 application. Allowing you to quickly develop and test your applications.

## Ionic what it is and why you should care
There are many frameworks out there to start developing you application just to name a few [Sencha](http://www.sencha.com/),[jQuery Mobile](http://jquerymobile.com/). Ionic differentiates it's self from this frameworks by being performance, native focused and provide the tools and support for developers to get started with HTML5 application.

But the question is why do we even need ionic start with? Well in order to understand why ionic is important we have to understand how mobile applications are built. If you ever developed a mobile application on a native device like android or ios you by default get a native SDK that you can work with. This SDK provides you with useful components that your application requires, some of them are animations, models, transitions, lists, buttons, tabs, navigation and scrolling just to name a few.

If you decide to use HTML5 to develop your application then you have to understand what is your targeted platform and for this case it's going to be the web-view, for those that are not familiar with a web-view it's a class that Java and objective c provides. Take a look at the [android web-view](http://developer.android.com/reference/android/webkit/WebView.html) and [UIWebView](https://developer.apple.com/library/ios/documentation/UIKit/Reference/UIWebView_Class/) make sure you take a second and look over each of the methods, you wont be calling any of this methods from your application but it helps to know that you are in essence working with a browser. 

The project [apache cordova](http://cordova.apache.org/) as an abstraction tool that takes you away from the native code so you can start developing your application in  HTML, CSS and JavaScript and then provides you the tools to build for multiple platforms not just android and IOS.

That sounds GREAT! why even bother with ionic? All I have to say about this is one word SPA(Single Page Application), according to the documentation from cordova they recommend you to use a SPA design for your application. Then you can just use your favorite front end development framework for example angular, backbone, spine, coffee script, and many more to name. But more then likely you want to bet on the winning horse according to Google angular is that very horse.

Now we need a tool to put all this together for us, this is where IONIC comes in adding yet another layer of abstraction to developing mobile applications. Ionic provides an SDK for your application to use, this includes documentation, directives, CLI, Java script Components and many more tools.

Ionic goes even a step further then this they implemented even more abstraction on there views. For example in android you are used to seeing the tab navigation on the top and in IOS you are used to seeing it at the bottom. Ionic takes care of this subtle changes for you, but not only that they give you the power to detect what platform your application is going to be running on and adjusting correctly to it by applying custom css or javascript code.

Hold the phone, it does not end there! The ionic team is hard at work with there [1 million dollar investment](http://techcrunch.com/2014/03/10/drifty-makers-of-the-ionic-mobile-framework-raise-1-million/), to bring to market even more amazing tools!


## Tips and tricks
Here is a quick guide for any of you advance developers.

If you want to debug an android application that is running on a emulator you can do this via chrome.

```bash
chrome://inspect
```

For those of you that want the maximum speed from your application that have to support android devices 4.0 or earlier then I would recommend to check out webview+ by ludie. You can find out the [github project](https://github.com/ludei/webview-plus/) it's not perfect make sure you read the documentation.

The last trick that I have for you advance users is to start getting involved in the community in one way or another, one of the best ways to acomplish this is to take a look at the [trello board](https://trello.com/b/nNk2Yq1k/ionic-framework) and see if you can implement one of the features.

