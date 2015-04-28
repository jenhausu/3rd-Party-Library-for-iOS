# 3rd Party Library Collection for iOS
這是我收集了一些第三方的 Library，大部份都還沒用過Orz，只是這樣整理以後要用到的時候會比較好找到。

- [UI](#ui)
	- [UI Design](#ui-design)
	- [alertView](#alertview)
	- [Menu（選單）](#menu)
	- [Side ViewController](#side-viewcontroller)
	- [UICollectionView](#uicollectionview)
	- [Segment Control](#segment-control)
	- [Others](#others-ui)
- [動畫](#animation)
- [影像特效](#effect)
	- [模糊、毛玻璃效果（Blur）](#blur)
- [畫面轉換](#transition)
- [各種統計圖表](#chart)
	- [Line](#line)
	- [Bar](#bar)
	- [Pie](#pie)
	- [Others](#others-chart)
- [Pull To ReFresh](#pull-to-refresh)
- [Notification](#notification)
- [Auto Layout](#auto-layout)
- [Data Storage](#data-storage)
- [Tools](#tools)
- [Snippets](#snippets)
- [Message](#message)
- [Encryption](#encryption)
- [Payment](#payment)
- [Custom datePicker](#custom-datepicker)
- [Others](#others)

## UI
[awesome-ios-ui](https://github.com/cjwirth/awesome-ios-ui) : A curated list of awesome iOS UI/UX libraries.
### UI Design
* [PrettyKit](https://github.com/vicpenap/PrettyKit) : PrettyKit for iOS is a small set of new widgets and UIKit subclasses that gives you a deeper UIKit customization. You will be able to change their background color, add gradients, shadows, etc.
* [Chameleon](https://github.com/VAlexander/Chameleon) : Chameleon is the first and only color framework on the market that focuses its full attention and efforts on "flat colors". With Chameleon, you can easily forget about UIColor RGB values, wasting hours figuring out the right color combinations to use in your app, and worrying about whether your text will be readable on the various background colors of your app.
* [Colours](https://github.com/bennyguitar/Colours) : A beautiful set of predefined colors and a set of color methods to make your iOS/OSX development life easier.

### alertView
* [SIAlertView](https://github.com/Sumi-Interactive/SIAlertView) : An UIAlertView replacement with block syntax and fancy transition styles.
* [Swift-Prompts](https://github.com/GabrielAlva/Swift-Prompts) : A Swift library to design custom prompts with a great scope of options to choose from.
* [BlockAlertsAnd-ActionSheets](https://github.com/gpambrozio/BlockAlertsAnd-ActionSheets) : Beautifully done UIAlertView and UIActionSheet replacements inspired by TweetBot.
* [SCLAlertView](https://github.com/dogo/SCLAlertView)
* [SCLAlertView-Swift](https://github.com/vikmeup/SCLAlertView-Swift)
* [PermissionScope](https://github.com/nickoneill/PermissionScope) : A Periscope-inspired way to ask for iOS permissions

### Menu
* [GuillotineMenu](https://github.com/Yalantis/GuillotineMenu) : Our Guillotine Menu Transitioning Animation implemented in Swift reminds a bit of a notorious killing machine.
* [RNFrostedSidebar](https://github.com/rnystrom/RNFrostedSidebar) : A Control Center-esque control with blurred background and toggle animations.
* [AwesomeMenu](https://github.com/levey/AwesomeMenu) : AwesomeMenu is a menu with the same look as the story menu of Path.
* [PopMenu](https://github.com/xhzengAIB/PopMenu) : PopMenu is pop animation menu inspired by Sina weibo / NetEase app.
* [KYGooeyMenu](https://github.com/KittenYang/KYGooeyMenu) : Gooey Effects 带粘性的扇形菜单
* [DOPDropDownMenu](https://github.com/dopcn/DOPDropDownMenu) : Drop down menu like we see on website for iPhone

### Side ViewController
* [MSDynamicsDrawerViewController](https://github.com/erichoracek/MSDynamicsDrawerViewController) : Container view controller that leverages UIKit Dynamics to provide a realistic drawer navigation paradigm.
* [RESideMenu](https://github.com/romaonthego/RESideMenu) : iOS 7/8 style side menu with parallax effect.
* [ECSlidingViewController](https://github.com/ECSlidingViewController/ECSlidingViewController) : Customizable sliding view controller container. Supports all screen sizes and orientations.
* [MMDrawerController](https://github.com/mutualmobile/MMDrawerController) : A lightweight, easy to use, Side Drawer Navigation Controller.
* [ViewDeck](https://github.com/Inferis/ViewDeck) : An implementation of the sliding functionality found in the Path 2.0 or Facebook iOS apps.
* [SwiftSideslipLikeQQ](https://github.com/johnlui/SwiftSideslipLikeQQ) : 再造 “手机QQ” 侧滑菜单
* [YRSideViewController](https://github.com/YueRuo/YRSideViewController) : Simple side viewController for iOS
* [SWRevealViewController](https://github.com/John-Lluch/SWRevealViewController) : A UIViewController subclass for presenting side view controllers inspired on the FaceBook and Wunderlist apps, done right !
* [KGFloatingDrawer](https://github.com/KyleGoddard/KGFloatingDrawer) : A floating navigation drawer with an interesting animated presentation written in Swift.

### UICollectionView
* [ARCollectionViewMasonryLayout](https://github.com/ashfurrow/ARCollectionViewMasonryLayout) : ARCollectionViewMasonryLayout is a UICollectionViewLayout subclass for creating flow-like layouts with dynamic widths or heights.
* [CHTCollectionViewWaterfallLayout](https://github.com/chiahsien/CHTCollectionViewWaterfallLayout) : The waterfall (i.e., Pinterest-like) layout for UICollectionView.

### Segment Control
* [HMSegmentedControl](https://github.com/HeshamMegid/HMSegmentedControl) : A drop-in replacement for UISegmentedControl mimicking the style of the segmented control used in Google Currents and various other Google products.

### Others UI
* [CMPopTipView](https://github.com/chrismiles/CMPopTipView) : Custom UIView for iOS that pops up an animated "bubble" pointing at a button or other view. Useful for popup tips.
* [VBFPopFlatButton](https://github.com/victorBaro/VBFPopFlatButton) : Flat button with 9 different states using POP.
* [GMGridView](https://github.com/gmoledina/GMGridView) : A performant Grid-View for iOS (iPhone/iPad) that allows sorting of views with gestures (the user can move the items with his finger to sort them) and pinching/rotating/panning gestures allow the user to play with the view and toggle from the cellview to a fullsize display.
* [FoldingTabBar.iOS](https://github.com/Yalantis/FoldingTabBar.iOS) : Folding Tab Bar and Tab Bar Controller
* [YIPopupTextView](https://github.com/inamiy/YIPopupTextView) : facebook's post-like input text view for iOS.
* [KNSemiModalViewController](https://github.com/kentnguyen/KNSemiModalViewController) : UIViewController+KNSemiModal is an effort to make a replica of semi-modal view with pushed-back stacked animation found in the beautiful Park Guides by National Geographic app. 


## Animation
* [pop](https://github.com/facebook/pop) : An extensible iOS and OS X animation library, useful for physics-based interactions.
* [Canvas](https://github.com/CanvasPod/Canvas) : Animate in Xcode without code

## Effect
* [Shimmer](https://github.com/facebook/Shimmer) : An easy way to add a simple, shimmering effect to any view in an iOS app.

### Blur
* [UIImage-BlurredFrame](https://github.com/Adrian2112/UIImage-BlurredFrame) : UIImage category that blurs an specified frame of a UIImage
* [SABlurImageView](https://github.com/szk-atmosphere/SABlurImageView) : You can use blur effect and it's animation easily to call only two methods.
* [DynamicBlurView](https://github.com/KyoheiG3/DynamicBlurView) : DynamicBlurView is a dynamic and high performance UIView subclass for Blur.
* [FXBlurView](https://github.com/nicklockwood/FXBlurView) : UIView subclass that replicates the iOS 7 realtime background blur effect, but works on iOS 5 and above.

## Transition
* [VCTransitionsLibrary](https://github.com/ColinEberhardt/VCTransitionsLibrary) : A collection of iOS 7 animation controllers and interaction controllers, providing flip, fold and all kinds of other transitions.
* [AnimatedTransitionGallery](https://github.com/shu223/AnimatedTransitionGallery) : Collection of iOS 7 custom animated transitions using UIViewControllerAnimatedTransitioning protocol.
* [PaperFold-for-iOS](https://github.com/honcheng/PaperFold-for-iOS) : Paper folding animation for iOS.

## Chart
### Line
* [BEMSimpleLineGraph](https://github.com/Boris-Em/BEMSimpleLineGraph) : Elegant Line Graphs for iOS.

### Bar
* [BarChart](https://github.com/KirillM/BarChart) : Bar Chart Standalone Component with Animation for IOS.

### Pie
* [XYPieChart](https://github.com/xyfeng/XYPieChart) : A simple and animated Pie Chart for your iOS app.
2. [MDRotatingPieChart](https://github.com/maxday/MDRotatingPieChart) : An iOS library to draw beautiful pie charts
3. [VBPieChart](https://github.com/sakrist/VBPieChart) : Pie Chart iOS control with different animations to present.
4. [CSCoverageChart](https://github.com/common-sense/CSCoverageChart) : Pie chart with multiple slices at even angles, each slice can have different radius. Useful when displaying coverage data.

### Others Chart
* [JBChartView](https://github.com/Jawbone/JBChartView) : iOS-based charting library for both line and bar graphs.
* [ios-charts](https://github.com/danielgindi/ios-charts) : An iOS port of the beautiful MPAndroidChart. - Beautiful charts for iOS apps!

## Pull To Refresh
* [MJRefresh](https://github.com/CoderMJLee/MJRefresh) : The easiest way to use pull-to-refresh.
* [XHRefreshControl](https://github.com/xhzengAIB/XHRefreshControl) : XHRefreshControl 是一款高扩展性、低耦合度的下拉刷新、上提加载更多的组件。

## Notification
* [CRToast](https://github.com/cruffenach/CRToast) : CRToast is a library that allows you to easily create notifications that appear on top of or by pushing out the status bar or navigation bar.
2. [TWMessageBarManager](https://github.com/terryworona/TWMessageBarManager) : An iOS manager for presenting system-wide notifications via a dropdown message bar.
3. [YRDropdownView](https://github.com/onemightyroar/YRDropdownView) : iOS view library for displaying stylish alerts, warnings, & errors.
4. [JDStatusBarNotification](https://github.com/jaydee3/JDStatusBarNotification) : Easy, customizable notifications displayed on top of the statusbar.

## Auto Layout
* [FLKAutoLayout](https://github.com/floriankugler/FLKAutoLayout) : UIView category which makes it easy to create layout constraints in code
2. [PureLayout](https://github.com/smileyborg/PureLayout) : The ultimate API for iOS & OS X Auto Layout — impressively simple, immensely powerful. Objective-C and Swift compatible.
3. [Cartography](https://github.com/robb/Cartography) : Set up your Auto Layout constraints declaratively and without any stringly typing!
4. [SnapKit](https://github.com/SnapKit/SnapKit) : SnapKit is a DSL to make Auto Layout easy on both iOS and OS X.
5. [UITableView-FDTemplateLayoutCell](https://github.com/forkingdog/UITableView-FDTemplateLayoutCell) : Template auto layout cell for automatically UITableViewCell height calculating

## Data Storage
* [YapDatabase](https://github.com/yapstudios/YapDatabase) : YapDatabase is an extensible database for iOS & Mac.
2. [fmdb](https://github.com/ccgus/fmdb) : A Cocoa / Objective-C wrapper around SQLite.
3. [TMCache](https://github.com/tumblr/TMCache) : Fast parallel object cache for iOS and OS X.
4. [Sync](https://github.com/hyperoslo/Sync) : Modern JSON synchronization to Core Data

## Tools
* [VVDocumenter-Xcode](https://github.com/onevcat/VVDocumenter-Xcode) : Xcode plug-in which helps you write Javadoc style documents easier.
2. [Nimbus](https://github.com/jverkoey/nimbus) : Nimbus is a toolkit for experienced iOS software designers. It provides well-documented, modular components that solve a number of common iOS software requirements. This includes: a rich text label with hyperlinks; a web view controller; a simple approach to table models, radio groups, and table actions; standardized interapp communication, and powerful debugging tools, amongst many other features.
3. [FLEX](https://github.com/Flipboard/FLEX) : FLEX (Flipboard Explorer) is a set of in-app debugging and exploration tools for iOS development. 
4. [Tweaks](https://github.com/facebook/Tweaks) : An easy way to fine-tune, and adjust parameters for iOS apps in development.
5. [JSONKit](https://github.com/johnezang/JSONKit) : (warning! This project hasn't update for three years. So I'm not sure this is a good library or not.)

## Snippets
* [XcodeSwiftSnippets](https://github.com/burczyk/XcodeSwiftSnippets) : Swift code snippets for Xcode
2. [Fucking-Block-Syntax-Autocompletion](https://github.com/schukin/Fucking-Block-Syntax-Autocompletion) : Xcode snippets for fucking block syntax

## Message
* [JSQMessagesViewController](https://github.com/jessesquires/JSQMessagesViewController) : 這應該是做 Messages 最大的 Library
2. [SOMessaging](https://github.com/SocialObjects-Software/SOMessaging) : This is a simple library to easily create a messaging app with smooth animations.
3. [MessageDisplayKit](https://github.com/xhzengAIB/MessageDisplayKit) : An IM App like WeChat App has to send text, pictures, audio, video, location messaging, managing local address book, share a circle of friends, drifting friends, shake a fun and more interesting features.
4. [SlackTextViewController](https://github.com/slackhq/SlackTextViewController) : A drop-in UIViewController subclass with a growing text input view and other useful messaging features.
5. [Atlas-iOS](https://github.com/layerhq/Atlas-iOS) : Atlas is a library of native iOS communications user interface components for Layer.

## Encryption
* [RNCryptor](https://github.com/RNCryptor/RNCryptor) : CCCryptor (AES encryption) wrappers for iOS and Mac.

## Payment
* [PaymentKit](https://github.com/stripe/PaymentKit) : Easily accept payments on iOS
2. [stripe-ios](https://github.com/stripe/stripe-ios) : The Stripe iOS SDK make it easy to collect your users' credit card details inside your iOS app.

## Custom datePicker
* [MWDatePicker](https://github.com/mwermuth/MWDatePicker) : Customize the good ol' UIDatePicker
2. [FlatDatePicker](https://github.com/syshen/FlatDatePicker):
3. [Asich/AADatePicker](https://github.com/Asich/AADatePicker)
4. [attias/AACustomDatePicker](https://github.com/attias/AACustomDatePicker)

## Others
* [AMScrollingNavbar](https://github.com/andreamazz/AMScrollingNavbar) : Scrollable UINavigationBar that follows the scrolling of a UIScrollView.
2. [TPKeyboardAvoiding](https://github.com/michaeltyson/TPKeyboardAvoiding) : A drop-in universal solution for moving text fields out of the way of the keyboard in iOS.
3. [WobbleView](https://github.com/inFullMobile/WobbleView)
4. [RichEditorView](https://github.com/cjwirth/RichEditorView) : RichEditorView is a simple, modular, drop-in UIView subclass for Rich Text Editing.
