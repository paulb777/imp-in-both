# imp-in-both

## Example

- git clone git@github.com:paulb777/iid-modular-header-bug.git
- cd imp-in-both/Example/
- pod update
- open imp-in-both.xcworkspace/
- Command-U to run unit tests
- Notice the top of the Xcode log:

```
objc[42576]: Class PodsDummy_GoogleToolboxForMac is implemented in both /Users/paulbeusterien/Library/Developer/CoreSimulator/Devices/672B8E49-CA5F-43C5-BC66-5F8FC451D677/data/Containers/Bundle/Application/9D3FF006-692D-4621-8397-0CDB6AFAC15F/imp-in-both_Example.app/imp-in-both_Example (0x107ef3350) and /Users/paulbeusterien/Library/Developer/Xcode/DerivedData/imp-in-both-cofvyqfvbkjbeuabqmlwgyviabun/Build/Products/Debug-iphonesimulator/imp-in-both_Example.app/PlugIns/imp-in-both_Tests.xctest/imp-in-both_Tests (0x121aa1a18). One of the two will be used. Which one is undefined.
objc[42576]: Class PodsDummy_imp_in_both is implemented in both /Users/paulbeusterien/Library/Developer/CoreSimulator/Devices/672B8E49-CA5F-43C5-BC66-5F8FC451D677/data/Containers/Bundle/Application/9D3FF006-692D-4621-8397-0CDB6AFAC15F/imp-in-both_Example.app/imp-in-both_Example (0x107ef33a0) and /Users/paulbeusterien/Library/Developer/Xcode/DerivedData/imp-in-both-cofvyqfvbkjbeuabqmlwgyviabun/Build/Products/Debug-iphonesimulator/imp-in-both_Example.app/PlugIns/imp-in-both_Tests.xctest/imp-in-both_Tests (0x121aa1a68). One of the two will be used. Which one is undefined.
```


## Requirements

## Installation

imp-in-both is available through [CocoaPods](http://cocoapods.org). To install
it, simply add the following line to your Podfile:

```ruby
pod 'imp-in-both'
```

## Author

Paul Beusterien, paulbeusterien@google.com

## License

imp-in-both is available under the MIT license. See the LICENSE file for more info.
