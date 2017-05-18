# 5-18-17 Meetup

### Server-side Swift With Perfect
Matt started us out with a shallow dive into [Perfect](http://perfect.org/), a server implementation written in Swift. The talk took a lot of inspiration from a [presentation by Ray Wenderlich](https://videos.raywenderlich.com/courses/81-rwdevcon-2017-vault-tutorials/lessons/15) at RWDevCon. Ray's tutorial dives a lot deeper into the power of Perfect as a server solution, so please check it out if you want to learn more. 

We used the [Swift Package Manager](https://github.com/apple/swift-package-manager) to generate the project and pull down our dependencies and we used [Postman](https://www.getpostman.com/) to test our endpoints.

Matt has also made [his code available](https://github.com/chordsNcode/PerfectServerDemo/blob/master/webroot/perfect.png) if you want to clone his repo and build your own endpoints.

### Test Driving Your Network Layer
Next, Sean presented a brief introduction to [Test Driven Development](http://agiledata.org/essays/tdd.html) focusing on how to test networking code. Sean described to us how, by using the [Quick](https://github.com/Quick/Quick) and [Nimble](https://github.com/Quick/Nimble) frameworks, we can make really human readable tests. Sean pointed out the importance of using [test doubles](https://marcosantadev.com/test-doubles-swift/) to make sure our tests are more reliable. Sean even suggested a [good place to look to](http://masilotti.com/) when learning testing in iOS.

If you want to check out Sean's code, all you need to do it check out his [Github repo](https://github.com/SeanROlszewski/Testing-Your-Network-Layer-with-Swift). Note, you will need to install [Carthage](https://github.com/Carthage/Carthage) (a package manager)
