### Hi there 👋

Hi, I'm Billy Chan, a skilled Software Engineer living in Canada 🇨🇦 

I have experience in Web Development(React.js, Vue.js), App Development(iOS, Android) and Python.

Dedicated to crafting applications with good user experience.

Here's my Linkedin: [billycychan](https://www.linkedin.com/in/billycychan/), feel free to send me a linkedin message!

## Table of Contents
  - [Web Development](#web-development)
  - [App Development](#app-development)
  - [Python](#python)
  - [More](#more)


### Web Development 📄

#### React Food Order  🧩
This is a simple food order app implemented in React. The app allows users to fetch meals, view meals and place orders.

<img src="./Assets/Screenshots/react-food-order.png" width="400"/>

[Soure Code](https://github.com/billycychan/react-food-order)

#### Vue Expense Tracker  🧩
This is a simple Expense Tracker implemented in Vue. The app allows users to add and remove incomes and expenses. The data is stored in localStorage.

<img src="./Assets/Screenshots/vue-expense-tracker.gif" width="400"/>

[Soure Code](https://github.com/billycychan/vue-expense-tracker)

#### Vue Flag Defence  📷
This is a WebAR Game "Flag Defence". The webpage can render 3D models on the marker using marker-based AR technology. 

<img src="./Assets/Screenshots/vue-flag-defence.gif" width="400"/>

[Soure Code](https://github.com/bill0930/flag-defense-vue)


### App Development 📂

#### BinTo: Waste Management Tool for Toronto  ♻️
"BinTo is your essential companion for eco-friendly living in the city. Seamlessly sort your waste with the Waste Wizard feature, ensuring you contribute to a cleaner environment. Stay informed about your next waste collection schedule effortlessly. Simplify your eco-conscious journey with BinTo."

- Created a swift and user-friendly search tool that guides users on the proper sorting of over 2,500 items for the City of Toronto
- Introduced the Collection Schedule feature, enabling residents to stay informed about the pick up schedule
- Showcased clothing donation locations on a map, motivating residents to contribute their unused garments

<div style="display: flex; flex-direction: row;">
    <img src="./Assets/Screenshots/BinTo/binto-001-waste-wizard.png" width="150" />
    <img src="./Assets/Screenshots/BinTo/binto-002-waste-detail.png" width="150" />
    <img src="./Assets/Screenshots/BinTo/binto-003-waste-schedule.png" width="150" />
    <img src="./Assets/Screenshots/BinTo/binto-004-location-confirm.png" width="150" />
</div>
<br>

[![name](./Assets/download-on-app-store.svg)](https://apps.apple.com/app/id6475327288)
<br>
<br>


#### TipTap: Quick Tip Calculator 🧾
[TipTap](https://apps.apple.com/us/app/tiptap-quick-tip-calculator/id6466767815): Your fast and easy tipping solution! Say goodbye to math hassles and hello to effortless tipping. Download now!

- Developed an intuitive and responsive tipping calculator app, enhancing user experience
- Designed a versatile color scheme system, supporting seamless transitions between dark and light modes
- Inspected app performance and app management with App Store Connect, achieving 5/5-star review

<div style="display: flex; flex-direction: row; justify-content: space-around;">
    <img src="./Assets/Screenshots/TipTap/tiptap-appstore-001.png" width="150" />
    <img src="./Assets/Screenshots/TipTap/tiptap-appstore-002.png" width="150" />
    <img src="./Assets/Screenshots/TipTap/tiptap-appstore-003.png" width="150" />
    <img src="./Assets/Screenshots/TipTap/tiptap-appstore-004.png" width="150" />
</div>
<br>

[![name](./Assets/download-on-app-store.svg)](https://apps.apple.com/us/app/tiptap-quick-tip-calculator/id6466767815)
<br>
<br>


#### GHFollowers 🫙

GHFollowers is an iOS app that allows a user to search for GitHub users, and browse their followers.

It was originally a [take home project](https://seanallen.teachable.com/p/take-home) from Sean Allen, I added additional features and refactored the project.  

- Architected with MVVM-C, using Combine to bind between View and ViewModel
- Developed listing, searching and filtering followers features within the view
- Implemented remote image caching natively with NSCache for SwiftUI Image to save network resources
- Adopted Swift Concurrency (async/await) pattern for asynchronous event handling


<div style="display: flex; flex-direction: row;">
    <img src="./Assets/Screenshots/GHFollowers/ghfollowers-001-search.png" width="150" />
    <img src="./Assets/Screenshots/GHFollowers/ghfollowers-002-listing.png" width="150" />
    <img src="./Assets/Screenshots/GHFollowers/ghfollowers-003-favorites.png" width="150"/>
    <img src="./Assets/Screenshots/GHFollowers/ghfollowers-004-userinfo.png" width="150" />
</div>
<br>

Special thanks to Sean Allen again for providing this free tutorial again.

<br>
<br>


#### Coinmama 💳
[Coinmama](https://www.coinmama.com/) is the leading cryptocurrency exchange platform to buy & sell crypto with credit card, debit card or bank transfer. It supports Tether (USDT), USD Coin (USDC), Bitcoin (BTC), and Ethereum (ETH).

- Delivered the web3 wallet app in MVVM-C and SwiftUI Architecture
- Led integration of analytic services with Firebase and Appsflyer
- Streamlined codebase using the Combine framework, integrating it to the network layer
- Performed Unit test with XCTest framework
- Implemented QR Scanner feature for Wallet Connect
- Designed the Feature Flag System (local/remote) with Firebase Remote Config

<div style="display: flex; flex-direction: row;">
    <img src="./Assets/Screenshots/Coinmama/coinmama-001-home.png" width = "160" />
    <img src="./Assets/Screenshots/Coinmama/coinmama-002-market-list.png" width="160" />
    <img src="./Assets/Screenshots/Coinmama/coinmama-003-market-detail.png" width="160" />
    <img src="./Assets/Screenshots/Coinmama/coinmama-004-recovery.png" width="160" />
</div>
<br>

[![name](./Assets/download-on-app-store.svg)](https://apps.apple.com/us/app/coinmama-crypto-wallet-app/id6443739884)

<br>
<br>

#### Lalamove 🚚

[Lalamove](https://www.lalamove.com/), the go-to app on the App Store, revolutionizes delivery and logistics. Instantly book on-demand delivery services, whether it's packages, documents, or larger items. Enjoy reliable, efficient, and cost-effective deliveries with a vast network of drivers. Simplify your logistics needs with Lalamove's user-friendly platform.

- Built with VIPER architecture, Swift, Objective-C and UIKit
- Handled order status change events with Push Notification
- Integrated Proxyman for efficient 30% reduction network debugging
- Monitored the crash-free rate with Crashlytics, up to 99%
- Integrated deeplinks for marketing purposes 
- Implemented AB Testing with Firebase 
- Realized Multi-language Localization with [Crowdin](https://crowdin.com/)
- Refactored Network Module with [Network Layer Demo](https://github.com/billycychan/ios-network-layer-demo) 
- Utilized pipelines through Fastlane in conjunction with GitLab's CI/CD

<div style="display: flex; flex-direction: row;">
    <img src="./Assets/Screenshots/Lalamove/lalamove-001-home.png" width="160" />
    <img src="./Assets/Screenshots/Lalamove/lalamove-002-vehicle-selection.png" width="160" />
    <img src="./Assets/Screenshots/Lalamove/lalamove-003-order-placing.png" width="160" />
    <img src="./Assets/Screenshots/Lalamove/lalamove-004-finding-driver.png" width="160" />
</div>
<br>

[![name](./Assets/download-on-app-store.svg)](https://apps.apple.com/us/app/lalamove-deliver-faster/id735701965)
<br>
<br>

#### SwiftUICrypto 🪙

[SwiftUICrypto](https://github.com/billycychan/SwiftUICrypto) is a cryptocurrency app that downloads live price data from an API and saves the current user's portfolio.

- SwiftUI, Combine, CoreData, MVVM, Animation, GCD

<div style="display: flex; flex-direction: row;">
    <img src="./Assets/Screenshots/SwiftUICrypto/swiftui-crypto-001-live-price.png" width="160" />
    <img src="./Assets/Screenshots/SwiftUICrypto/swiftui-crypto-002-portfolio.png" width="160" />
    <img src="./Assets/Screenshots/SwiftUICrypto/swiftui-crypto-003-detail.png" width="160" />
    <img src="./Assets/Screenshots/SwiftUICrypto/swiftui-crypto-004-edit-portfolio.png" width="160" />
</div>
<br>

Special thanks to Nick Sarno at [Swiftful Thinking](https://www.swiftful-thinking.com/) for providing this production quality [tutorial](https://www.youtube.com/playlist?list=PLwvDm4Vfkdphbc3bgy_LpLRQ9DDfFGcFu). 

<br>

#### Scrumdinger ⌛

Scrumdinger is an app that manages daily meetings.

- SwiftUI essentials, Views, Navigation and modal presentation, Passing data, State management, Persistence and concurrency, Drawing shapes with SwiftUI geometry tools, Recording audio


<div style="display: flex; flex-direction: row;">
    <img src="./Assets/Screenshots/Scrumdinger/scrumdinger-001-list.png" width="160" />
    <img src="./Assets/Screenshots/Scrumdinger/scrumdinger-002-detail.png" width="160" />
    <img src="./Assets/Screenshots/Scrumdinger/scrumdinger-003-edit.png" width="160" />
    <img src="./Assets/Screenshots/Scrumdinger/scrumdinger-004-timer.png" width="160" />
</div>
<br>

Special thanks to Apple for providing this [iOS App Dev Tutorials](https://developer.apple.com/tutorials/app-dev-training). 

### Python 🐍
#### TicTacToe  🧩
This is a simple Tic-Tac-Toe game implemented in Python using the tkinter library for the GUI. The game allows two players to take turns marking the spaces in a 3x3 grid to try and get three of their marks in a row, column, or diagonal.

<img src="./Assets/Screenshots/python-tictactoe.gif" width="400"/>

[Soure Code](https://github.com/billycychan/python-tictactoe)

#### More
- [TwitterClone](https://github.com/billycychan/TwitterTutorial) 🤖
- [NetworkLayer](https://github.com/billycychan/ios-network-layer-demo) 🛜
- [GithubPlayground](https://github.com/bill0930/ios-GithubPlayground) 🛝
- [ObjectiveC-notes](https://github.com/bill0930/BNR-Objective-C-Programming) 📚