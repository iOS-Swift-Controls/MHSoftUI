# MHSoftUI

[![CI Status](https://img.shields.io/travis/Mumtaz Hussain/MHSoftUI.svg?style=flat)](https://travis-ci.org/Mumtaz Hussain/MHSoftUI)
[![Version](https://img.shields.io/cocoapods/v/MHSoftUI.svg?style=flat)](https://cocoapods.org/pods/MHSoftUI)
[![License](https://img.shields.io/cocoapods/l/MHSoftUI.svg?style=flat)](https://cocoapods.org/pods/MHSoftUI)
[![Platform](https://img.shields.io/cocoapods/p/MHSoftUI.svg?style=flat)](https://cocoapods.org/pods/MHSoftUI)

## Example

To run the example project, clone the repo, and run `pod install` from the Example directory first.

## Installation

MHSoftUI is available through [CocoaPods](https://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'MHSoftUI'
```


## Requirements

It is prefered to choose a very light color for your controller's background and the same color to your UI components, for example:
`self.view.backgroundColor = UIColor(red: 241/255, green: 243/255, blue: 246/255, alpha: 1.0)`

## Useage

#### For UIView: ####
Simply call this method with your view object for standard SoftUI Effect:

`myView.addSoftUIEffectForView()`

#### For UIButton: ####

`myButton.addSoftUIEffectForButton()`

## Cutomization ##

There are parameters to each method that will let you customize the effect of SoftUI:

`someButton.addSoftUIEffectForButton(cornerRadius: someButton.bounds.height/2, themeColor: UIColor(red: 241/255, green: 243/255, blue: 246/255, alpha: 1.0))`


## Author

Mumtaz Hussain, mumtaz_hussain13@yahoo.com

## License

MHSoftUI is available under the MIT license. See the LICENSE file for more info.
