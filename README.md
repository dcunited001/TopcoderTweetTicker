Topcoder Tweet Ticker
=====================

Basically, a simple iOS app written in swift with a stock-ticker style
widget at the bottom that lists the most recent tweets from @topcoder.

## Overview

I used `Alamofire` to make network requests to the Twitter API 
and `SwiftyJSON` to parse the responses.  Pretty simple.  

## Getting Started

Make sure you open the `.xcworkspace` and not the project file.  

### Download Dependencies with Carthage

I'm using `Carthage` to manage dependencies, so run 
`carthage update --platforms iOS --use-submodules` to checkout and build 
dependencies into the `./Carthage/` folder.  Once carthage builds the frameworks 
into this folder, the links should resolve in the `.xcworkspace` and `.xcodeproj` 
config files, so everything should build.  Just hit run.

### Testing with Quick/Nimble

I've configured targets for Unit tests and UI tests, though I'm not sure how 
much testing i'll do in a project this size.  I mostly set it up to 
demonstrate the configuration for testing in a Swift iOS project using 
`Quick` and `Nimble`.  As above, once you've used carthage to checkout and 
build the dependencies, then the tests should run as well.

