---
title: Getting Started - New World of SwiftUI
author: Rahul R
date: 2020-04-20 10:00:00 +0530
categories: [Blogging,IOS,SwiftUI]
tags: [swiftui,ios]     # TAG names should always be lowercase
---

SwiftUI is a user interface toolkit that lets us design apps in a declarative way. That’s a fancy way of saying that we tell SwiftUI how we want our UI to look and work, and it figures out how to make that happen as the user interacts with it.

Declarative UI is best understood in comparison to imperative UI, which is what iOS developers were doing before iOS 13. In an imperative user interface we might make a function be called when a button was clicked, and inside the function we’d read a value and show a label – we regularly modify the way the user interface looks and works based on what’s happening.
### Declarative Syntax

SwiftUI uses a declarative syntax so you can simply state what your user interface should do. For example, you can write that you want a list of items consisting of text fields, then describe alignment, font, and color for each field. Your code is simpler and easier to read than ever before, saving you time and maintenance.
![example-syntax-light-small_2x](https://developer.apple.com/xcode/swiftui/images/example-syntax-light-small_2x.jpg)

### Design Tools
Xcode 11 includes intuitive new design tools that make building interfaces with SwiftUI as easy as dragging and dropping. As you work in the design canvas, everything you edit is completely in sync with the code in the adjoining editor. Code is instantly visible as a preview as you type, and any change you make to that preview immediately appears in your code. Xcode recompiles your changes instantly and inserts them into a running version of your app, visible, and editable at all times.

![example-design-medium_2x](https://developer.apple.com/xcode/swiftui/images/example-design-medium_2x.jpg)

Drag and drop. Arrange components within your user interface by simply dragging controls on the canvas. Click to open an inspector to select font, color, alignment, and other design options, and easily re-arrange controls with your cursor. Many of these visual editors are also available within the code editor, so you can use inspectors to discover new modifiers for each control, even if you prefer hand-coding parts of your interface. You can also drag controls from your library and drop them on the design canvas or directly on the code.

Dynamic replacement. The Swift compiler and runtime are fully embedded throughout Xcode, so your app is constantly being built and run. The design canvas you see isn’t just an approximation of your user interface — it’s your live app. And Xcode can swap edited code directly in your live app with “dynamic replacement”, a new feature in Swift.

Previews. You can now create one or many previews of any SwiftUI views to get sample data, and configure almost anything your users might see, such as large fonts, localizations, or Dark Mode. Previews can also display your UI in any device and any orientation.
