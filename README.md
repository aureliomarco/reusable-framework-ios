# How to create Reusable Frameworks
How to make a Swift-based camera library that you can drag and drop into any iOS application, and save time and energy re-writing code.

:spiral_notepad: :pencil2: Notes during the course, can be viewed [HERE](https://marcoaurelio.slite.com/api/s/note/54yBhZU416YDjfxH6wb2HY/Writing-Reusable-Frameworks)

:desktop_computer:  Link for the [course](https://www.linkedin.com/learning/swift-writing-reusable-frameworks/set-up-your-sample-app-and-workflow?u=26137906)

### Setup
- IDE: `Xcode 11.1` (Version of the Xcode where the project was builded)
- Swift Version: `5.1`
- iOS Target: `11.0`

1. Clone or download the project
```
git clone git@github.com:aureliomarco/reusable-framework-ios.git
```
2. Go to the directory where the project was cloned or downloaded.
3. Open the project file
```
open CameraFramework.xcodeproj
```

## 1. Let's Make It Work
- [Create your first build](https://github.com/aureliomarco/alura-ios-teste-com-mocks/commit/09c68f1b5dc300387af7bff1dc9723c6365e8be1) - commit [09c68f1b5dc300387af7bff1dc9723c6365e8be1]
- Set up your sample app and workflow
- Make the camera work: Part 1
- Make the camera work: Part 2

## 2. Let's Keep It Clean
- Application vs. interface development
- Swift frameworks and access control
- Refactoring your camera
- Using extensions to organize your code
- Creating a framework delegate
- Implementing your framework delegate
- Handling rotation

## 3. Putting It All Together
- Add media assets to your framework
- Set up camera for image capture
- Capturing a still image
- Implement AVFoundation delegates
- Normalizing your image data
- Correcting still image orientation
- Refactoring your sample application
- Checking for leaks

## 4. Track It
- Semantic versioning and future roadmapping
- Tagging releases in Git
