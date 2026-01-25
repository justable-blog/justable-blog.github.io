---
title: "Icons"
date: 2020-08-14
lastmod: 2022-03-09
draft: false
description: "Icon support in Blowfish."
slug: "icons"
tags: ["icons", "sample", "shortcodes"]
type: 'sample'
---

Blowfish has built-in support for a number of [FontAwesome 6](https://fontawesome.com/icons) icons. These can be included in your website through either the [icon partial]() or [icon shortcode]().

Additionally, custom icons are also fully supported. Simply provide your own SVG icon assets by placing them in the `assets/icons/` directory in the root of your project. Any icons in the icons directory will then be available to use throughout the theme. In order to achieve automatic color filling, every SVG path needs the `fill="currentColor"` XML attribute.

The full list of built-in icons and their corresponding names can referenced below.
| Icon name            | Code                                  | Preview                          |
| -------------------- | ------------------------------------- |--------------------------------- |
| amazon               | {{</* icon amazon  */>}}              |{{< icon amazon >}}               |
| apple                | {{</* icon apple */>}}                |{{< icon apple >}}                |
| bars                 | {{</* icon bars */>}}                 |{{< icon bars >}}                 |
| bell                 | {{</* icon bell */>}}                 |{{< icon bell >}}                 |
| blogger              | {{</* icon blogger */>}}              |{{< icon blogger >}}              |
| bluesky              | {{</* icon bluesky */>}}              |{{< icon bluesky >}}              |
| bomb                 | {{</* icon bomb */>}}                 |{{< icon bomb >}}                 |
| bug                  | {{</* icon bug */>}}                  |{{< icon bug >}}                  |
| check                | {{</* icon check */>}}                |{{< icon check >}}                |
| circle-info          | {{</* icon circle-info */>}}          |{{< icon circle-info >}}          |
| code                 | {{</* icon code */>}}                 |{{< icon code >}}                 |
| codeberg             | {{</* icon codeberg */>}}             |{{< icon codeberg >}}             |
| codepen              | {{</* icon codepen */>}}              |{{< icon codepen >}}              |
| comment              | {{</* icon comment */>}}              |{{< icon comment >}}              |
| dev                  | {{</* icon dev */>}}                  |{{< icon dev >}}                  |
| discourse            | {{</* icon discourse */>}}            |{{< icon discourse >}}            |
| docker               | {{</* icon docker */>}}               |{{< icon docker >}}               |
| download             | {{</* icon download */>}}             |{{< icon download >}}             |
| dribbble             | {{</* icon dribbble */>}}             |{{< icon dribbble >}}             |
| edit                 | {{</* icon edit */>}}                 |{{< icon edit >}}                 |
| email                | {{</* icon email */>}}                |{{< icon email >}}                |
| envelope             | {{</* icon envelope */>}}             |{{< icon envelope >}}             |
| expand               | {{</* icon expand */>}}               |{{< icon expand >}}               |
| eye                  | {{</* icon eye */>}}                  |{{< icon eye >}}                  |
| facebook             | {{</* icon facebook */>}}             |{{< icon facebook >}}             |
| fire                 | {{</* icon fire */>}}                 |{{< icon fire >}}                 |
| flickr               | {{</* icon flickr */>}}               |{{< icon flickr >}}               |
| fork                 | {{</* icon fork */>}}                 |{{< icon fork >}}                 |
| foursquare           | {{</* icon foursquare */>}}           |{{< icon foursquare >}}           |
| ghost                | {{</* icon ghost */>}}                |{{< icon ghost >}}                |
| github               | {{</* icon github */>}}               |{{< icon github >}}               |
| gitlab               | {{</* icon gitlab */>}}               |{{< icon gitlab >}}               |
| globe                | {{</* icon globe */>}}                |{{< icon globe >}}                |
| goodreads            | {{</* icon goodreads */>}}            |{{< icon goodreads >}}            |
| google               | {{</* icon google */>}}               |{{< icon google >}}               |
| graduation-cap       | {{</* icon graduation-cap */>}}       |{{< icon graduation-cap >}}       |
| hackernews           | {{</* icon hackernews */>}}           |{{< icon hackernews >}}           |
| hashnode             | {{</* icon hashnode */>}}             |{{< icon hashnode >}}             |
| heart-empty          | {{</* icon heart-empty */>}}          |{{< icon heart-empty >}}          |
| heart                | {{</* icon heart */>}}                |{{< icon heart >}}                |
| image                | {{</* icon image */>}}                |{{< icon image >}}                |
| instagram            | {{</* icon instagram */>}}            |{{< icon instagram >}}            |
| itch-io              | {{</* icon itch-io */>}}              |{{< icon itch-io >}}              |
| keybase              | {{</* icon keybase */>}}              |{{< icon keybase >}}              |
| kickstarter          | {{</* icon kickstarter */>}}          |{{< icon kickstarter >}}          |
| ko-fi                | {{</* icon ko-fi */>}}                |{{< icon ko-fi >}}                |
| language             | {{</* icon language */>}}             |{{< icon language >}}             |
| lastfm               | {{</* icon lastfm */>}}               |{{< icon lastfm >}}               |
| lightbulb            | {{</* icon lightbulb */>}}            |{{< icon lightbulb >}}            |
| line                 | {{</* icon line */>}}                 |{{< icon line >}}                 |
| link                 | {{</* icon link */>}}                 |{{< icon link >}}                 |
| linkedin             | {{</* icon linkedin */>}}             |{{< icon linkedin >}}             |
| list                 | {{</* icon list */>}}                 |{{< icon list >}}                 |
| location-dot         | {{</* icon location-dot */>}}         |{{< icon location-dot >}}         |
| lock                 | {{</* icon lock */>}}                 |{{< icon lock >}}                 |
| mastodon             | {{</* icon mastodon */>}}             |{{< icon mastodon >}}             |
| medium               | {{</* icon medium */>}}               |{{< icon medium >}}               |
| microsoft            | {{</* icon microsoft */>}}            |{{< icon microsoft >}}            |
| moon                 | {{</* icon moon */>}}                 |{{< icon moon >}}                 |
| mug-hot              | {{</* icon mug-hot */>}}              |{{< icon mug-hot >}}              |
| music                | {{</* icon music */>}}                |{{< icon music >}}                |
| orcid                | {{</* icon orcid */>}}                |{{< icon orcid >}}                |
| patreon              | {{</* icon patreon */>}}              |{{< icon patreon >}}              |
| paypal               | {{</* icon paypal */>}}               |{{< icon paypal >}}               |
| peertube             | {{</* icon peertube */>}}             |{{< icon peertube >}}             |
| pencil               | {{</* icon pencil */>}}               |{{< icon pencil >}}               |
| pgpkey               | {{</* icon pgpkey */>}}               |{{< icon pgpkey >}}               |
| phone                | {{</* icon phone */>}}                |{{< icon phone >}}                |
| pinterest            | {{</* icon pinterest */>}}            |{{< icon pinterest >}}            |
| pixelfed             | {{</* icon pixelfed */>}}             |{{< icon pixelfed >}}             |
| poo                  | {{</* icon poo */>}}                  |{{< icon poo >}}                  |
| reddit               | {{</* icon reddit */>}}               |{{< icon reddit >}}               |
| researchgate         | {{</* icon researchgate */>}}         |{{< icon researchgate >}}         |
| rss                  | {{</* icon rss */>}}                  |{{< icon rss >}}                  |
| rss-square           | {{</* icon rss-square */>}}           |{{< icon rss-square >}}           |
| scale-balanced       | {{</* icon scale-balanced */>}}       |{{< icon scale-balanced >}}       |
| search               | {{</* icon search */>}}               |{{< icon search >}}               |
| shield               | {{</* icon shield */>}}               |{{< icon shield >}}               |
| skull-crossbones     | {{</* icon skull-crossbones */>}}     |{{< icon skull-crossbones >}}     |
| slack                | {{</* icon slack */>}}                |{{< icon slack >}}                |
| snapchat             | {{</* icon snapchat */>}}             |{{< icon snapchat >}}             |
| soundcloud           | {{</* icon soundcloud */>}}           |{{< icon soundcloud >}}           |
| spotify              | {{</* icon spotify */>}}              |{{< icon spotify >}}              |
| stack-overflow       | {{</* icon stack-overflow */>}}       |{{< icon stack-overflow >}}       |
| star                 | {{</* icon star */>}}                 |{{< icon star >}}                 |
| steam                | {{</* icon steam */>}}                |{{< icon steam >}}                |
| stripe               | {{</* icon stripe */>}}               |{{< icon stripe >}}               |
| substack             | {{</* icon substack */>}}             |{{< icon substack >}}             |
| sun                  | {{</* icon sun */>}}                  |{{< icon sun >}}                  |
| tag                  | {{</* icon tag */>}}                  |{{< icon tag >}}                  |
| telegram             | {{</* icon telegram */>}}             |{{< icon telegram >}}             |
| threads              | {{</* icon threads */>}}              |{{< icon threads >}}              |
| tiktok               | {{</* icon tiktok */>}}               |{{< icon tiktok >}}               |
| triangle-exclamation | {{</* icon triangle-exclamation */>}} |{{< icon triangle-exclamation >}} |
| tumblr               | {{</* icon tumblr */>}}               |{{< icon tumblr >}}               |
| twitch               | {{</* icon twitch */>}}               |{{< icon twitch >}}               |
| twitter              | {{</* icon twitter */>}}              |{{< icon twitter >}}              |
| wand-magic-sparkles  | {{</* icon wand-magic-sparkles */>}}  |{{< icon wand-magic-sparkles >}}  |
| whatsapp             | {{</* icon whatsapp */>}}             |{{< icon whatsapp >}}             |
| worktree             | {{</* icon worktree */>}}             |{{< icon worktree >}}             |
| x-twitter            | {{</* icon x-twitter */>}}            |{{< icon x-twitter >}}            |
| xing                 | {{</* icon xing */>}}                 |{{< icon xing >}}                 |
| xmark                | {{</* icon xmark */>}}                |{{< icon xmark >}}                |
| youtube              | {{</* icon youtube */>}}              |{{< icon youtube >}}              |

Coustom Icon
| Icon name            | Code                                  | Preview                          |
| -------------------- | ------------------------------------- |--------------------------------- |
| kakaotalk            | {{</* icon kakaotalk  */>}}           |{{< icon kakaotalk >}}            |