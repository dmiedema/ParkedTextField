# ParkedTextField
[![Version](https://img.shields.io/cocoapods/v/ParkedTextField.svg?style=flat)](http://cocoapods.org/pods/ParkedTextField)
[![License](https://img.shields.io/cocoapods/l/ParkedTextField.svg?style=flat)](http://cocoapods.org/pods/ParkedTextField)
[![Platform](https://img.shields.io/cocoapods/p/ParkedTextField.svg?style=flat)](http://cocoapods.org/pods/ParkedTextField)

A text field subclass with a constant text in the end. 

Main functionality works. It is still under development.

## Screenshot

![ParkedTextField.gif](https://raw.githubusercontent.com/gmertk/ParkedTextField/master/Screenshots/ParkedTextField.gif)


## Usage

ParkedTextField is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following lines to your Podfile:

```ruby
use_frameworks!
pod "ParkedTextField"
```
	
## Setup

If you want to use storyboards, just drop a TextField into your storyboard and set its class to `ParkedTextField`. Then customize through the attributes inspector or code. Otherwise, you can write the code to initialize with frame and set the properties.

## Properties
```swift
/// Constant text. Defaults to "".
var parkedText: String = ".slack.com" 

/// Placeholder next to parkedText. Defaults to "".
var placeholderText: String = "yourteam" 

/// Variable part of the text. Defaults to "".
var typedText: String

/// Font of parkedText. Defaults to bold version of the text field's font if it exists. If not, defaults to the font of the text field.
var parkedTextFont: UIFont!

/// Color of parkedText. Defaults the font's color.
var parkedTextColor: UIColor! 


```
## Development
* [ ] Instead of subclassing UITextField, investigate making a UITextField extension.
* [ ] Test setting placeholder and text. In some cases it breaks the parkedText.

## Author

Günay Mert Karadoğan, mertkaradogan@gmail.com

## License

ParkedTextField is available under the MIT license. See the LICENSE file for more info.


