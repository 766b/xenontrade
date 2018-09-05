
# XenonTrade
XenonTrade is a Path of Exile trading app based on electron that was initially developed specifically for Linux users. While Path of Exiles performance on Linux distributions has drastically increased in the past few months, there are barely any trading companions available for Linux. And thus, this app was created. Currently, it is only used as an overlay for checking prices, but soon it'll receive a trade whisper helper as well.

Works on Linux and on Windows 🎉

![](https://i.imgur.com/4Yvnygy.png) | ![](https://i.imgur.com/84B7eTl.png) | ![](https://i.imgur.com/0l2mRgv.png)
:---:|:---:|:---:

## Wiki

- [Installation](https://github.com/klayveR/xenontrade/wiki/Installation)
- [Build it yourself](https://github.com/klayveR/xenontrade/wiki/Build-it-yourself)
- [Button functions](https://github.com/klayveR/xenontrade/wiki/Buttons)
- [Known bugs](https://github.com/klayveR/xenontrade/wiki/Known-bugs)

## Features
- Press `CTRL+C` while hovering over an item to get the price data in the overlay immediately
- Price checks can be automatically closed after a certain period of time, configurable via the settings menu
- Arrow colors indicates the confidence in the accuracy of the price
  - Green indicates high confidence, yellow is average and red is low or very low

##### Item features
- See the price trend graph by clicking the trend button next to the item name
- Switch between value in Chaos Orbs and Exalted Orbs
- The tool automatically detects almost every unique item variant (see [Item variant support](https://github.com/klayveR/xenontrade/wiki/Item-variant-support)) as well as 5 and 6 links

##### Currency features
- See the price trend graph by clicking the trend button next to the currency name
- Switch between seeing how many Chaos Orbs you'd receive for the currency and how many Chaos Orbs you'd have to pay for your currency
- Check the value of your whole currency stack (available after clicking on the expand button)
- Compare the actual price you'd have to pay for your currency to the calculated price based on how much you'd receive (available after clicking on the expand button)
