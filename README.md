#Mastering iOS 10 Programming
This is the code repository for [Mastering iOS 10 Programming](https://www.packtpub.com/application-development/mastering-ios-10-programming?utm_source=github&utm_medium=repository&utm_campaign=9781786469359), published by [Packt](www.packtpub.com). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
With usage of apps growing rapidly, mobile application development has become the most sought-after skill set. Within the mobile market, iOS commands a massive presence and is a highly lucrative platform. The goal of our book is to help you become a professional developer by unleashing the full potential of iOS 10 to build applications.

Written with the latest Swift version and following the latest Swift API design guidelines, you won’t just learn how to program for iOS 10—you’ll also learn how to write beautiful, readable, and maintainable Swift code that’s in line with the industry’s best-practices. The progression of the book reflects the real-world development flow: it will quickly brush on the essentials at the beginning and then move on to the advanced concepts crucial to building powerful applications.

Within the book, you will build a couple of small applications that resemble applications you might want to build in the real world. You will be reading a mix of thorough background information and practical examples, so you’ll know how to make use of a certain technique right away while you also get a great understanding of the how and why.
##Instructions and Navigations
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.



The code will look like the following:
```
class ViewController: UIViewController {
override func viewDidLoad() {
super.viewDidLoad()
let store = CNContactStore()
if CNContactStore.authorizationStatus(for: .contacts) ==
.notDetermined {
store.requestAccess(for: .contacts, completionHandler: {[weak
self]
authorized, error in
if authorized {
self?.retrieveContacts(fromStore: store)
}
```

All code samples are written in Swift 3.0 with Xcode 8. You’ll need a Mac that can run
Xcode 8. In order to test all of the code samples in this book, you'll need an iOS device that
runs iOS 10 and a paid subscription to Apple's developer program.

##Related Products
* [iOS 10 Programming Cookbook](https://www.packtpub.com/application-development/ios-10-programming-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781786460981)

* [iOS 10 Programming for Beginners](https://www.packtpub.com/application-development/ios-10-programming-beginners?utm_source=github&utm_medium=repository&utm_campaign=9781786464507)

* [Learning iOS Penetration Testing](https://www.packtpub.com/networking-and-servers/learning-ios-penetration-testing?utm_source=github&utm_medium=repository&utm_campaign=9781785883255)
###Suggestions and Feedback
[Click here](https://docs.google.com/forms/d/e/1FAIpQLSe5qwunkGf6PUvzPirPDtuy1Du5Rlzew23UBp2S-P3wB-GcwQ/viewform) if you have any feedback or suggestions.
