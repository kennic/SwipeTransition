BackSwipeable
===

[![Carthage compatible](https://img.shields.io/badge/Carthage-compatible-4BC51D.svg?style=flat)](https://github.com/Carthage/Carthage)
[![Swift Version](https://img.shields.io/badge/Swift-4-F16D39.svg)](https://developer.apple.com/swift)

BackSwipeable allows swipe back anywhere.

# Usage

Just use SwipeBackableNavigationController instead of UINavigationController. Of course, you can set it with Interface Builder.

```swift
let viewController = UIViewController()
let navigationController = SwipeBackableNavigationController(rootViewControlelr: viewController)
````

`S protocol is also available.

# Installation

## Carthage

```ruby
github "tattn/BackSwipeable"
```


# Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

# License

BackSwipeable is released under the MIT license. See LICENSE for details.