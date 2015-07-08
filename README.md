# Spiel
Spiel: The game of clever merchants selling creative products to unique customers

A peer-to-peer [Snake Oil][cah] game for iOS, written with Multipeer Connectivity in Swift.

![](http://pics.jpsim.com/objcio-mpc/demo.gif)

## Libraries

This project uses the following libraries:

* [PeerKit](https://github.com/jpsim/PeerKit) for event-driven, zero-config Multipeer Connectivity
* [Cartography](https://github.com/robb/Cartography) for layout
* [SVProgressHUD](https://github.com/TransitApp/SVProgressHUD) for HUDs

## Offensive Content

Running this game from source will use a small, very mild, impossible to offend subset of the Snake Oil cards.

However, simply set `let pg13 = false` in [CardManager.swift](https://github.com/jpsim/CardsAgainst/blob/master/CardsAgainst/Controllers/CardManager.swift#L11) to gain access to the entirety of the card collection.

## License

This project is under the MIT license.

Thanks to [Snake Oil][cah] for this great CC-BY-NC-SA 2.0 game! This project is unaffiliated with the good people behind Snake Oil. You should buy their game!

Thanks to [Hangouts Against Humanity](https://github.com/samurailink3/hangouts-against-humanity) for the cards!

While it is not strictly forbidden by the license, I would greatly appreciate it if you didn't redistribute this app exactly the way it is in the App Store. There's nothing stopping you, but please don't be a jerk.

[cah]: http://amzn.com/B00AEB1R66