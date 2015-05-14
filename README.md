# DKAnimationKit(Swift)

DKAnimationKit is a DSL to make animation easy on iOS with **Swift**. This is a swift port to JHChainableAnimations.

![language](https://img.shields.io/badge/language-swift-orange.svg)
![Version](https://img.shields.io/badge/Pod-%20v0.1.0%20-or.svg)
![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)
![MIT License](https://img.shields.io/github/license/mashape/apistatus.svg)
![Platform](https://img.shields.io/badge/platform-%20iOS%20-lightgrey.svg)

**If you app is written in Objective-C, you should use [JHChainableAnimations](https://github.com/jhurray/JHChainableAnimations) instead.**

## With JHChainableAnimations

```
view.makeScale()(2.0).spring().animate()(1.0)
```

## With DKAnimationKit

```
view.animation.makeScale(2.0).spring.animate(1.0)
```

# Installation with CocoaPods

[CocoaPods](https://cocoapods.org/) is a dependency manager for Objective-C, which automates and simplifies the process of using 3rd-party libraries like DKNightVersion in your projects. See the [Get Started section](https://cocoapods.org/#get_started) for more details.

## Podfile

```
pod "DKAnimationKit", "~> 0.1.0"
```

# License

DKAnimationKit is available under the MIT license. See the LICENSE file for more info.

