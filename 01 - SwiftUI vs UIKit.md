# SwiftUI vs UIKit



In 2019 Apple introduced ***SwiftUI***, which is the fancy new way to create user interfaces in Swift.

SwiftUI is that your user interfaces are created completely in code, but while you’re coding you can see a dynamic preview of this code in **SwiftUI’s** canvas editor.

And you have a choice - you can either code the user interface yourself, or you can use Swift UI’s canvas editor to code it on your behalf.

You can also use something called **UIKit**, which is the framework that iOS developers had to use before **SwiftUI** was released. I want to point out that **UIKit** is still a valid way to make iOS apps. In fact, I’d say there are still probably more developers using **UIKit** than **SwiftUI**.

If **SwiftUI** is so great, why is that?

- **SwiftUI** only works on iOS 13 or later. Even though iOS 16 is out now, some companies need to support **earlier** version of iOS and are just getting to a place where they can start switching to SwiftUI.
- **SwiftUI** is still not as mature as **UIKit**. Think about it: **UIKit** has been out for 12 years, and in fact it was based on a macOS framework called **AppKit** which had even more history, so there was a lot of time to get things right. But **SwiftUI** is much younger. This means there are still some missing features and a rough edges. Some companies still want to give **SwiftUI** a little more time to catch up, or they’ll have to use *some* **UIKit** to account for missing features.
- Many companies have already written their apps using **UIKit**. It can be a ton of work to rewrite an entire app in **SwiftUI**! So, a lot of that old UIKit legacy code will remain for quite some time.

Next Learning Paths: iOS User Interfaces with SwiftUI, iOS Data and Networking, and iOS IDEs and Tools

