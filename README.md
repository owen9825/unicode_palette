# Unicode Palette
Please include some useful symbols here so that your typing can be more concise and expressive.

| Symbol  | Name  | Notes |
|:--------|:-----|:-----|
| ❓  | BLACK QUESTION MARK ORNAMENT |  |
| 🚢  | SHIP  |  |
| ⛲  | FOUNTAIN  |  |
| 🔮  | CRYSTAL BALL |  |
| 🌀  | CYCLONE  |  |
| 🍷  | WINE GLASS  |  |
| 🎵  | MUSICAL NOTE |  |
| 🎶 | MULTIPLE MUSICAL NOTES | |
| 🎰  | SLOT MACHINE  |  |
| 🕵 | SLEUTH OR SPY | |
| ∀   | FOR ALL  |  |
| ∃   | THERE EXISTS  |  |
| ↦   | RIGHTWARDS ARROW FROM BAR  |  |
| ∝   | PROPORTIONAL TO  |  |
| ∞   | INFINITY  |  |
| ∧   | LOGICAL AND  | [🔗](https://en.wikipedia.org/wiki/List_of_logic_symbols) |
| ∨   | LOGICAL OR  |  |
| ¬   | NOT SIGN   |  |
| ∩   | INTERSECTION  |  |
| ∪   | UNION  |  |
| ≍   | EQUIVALENT TO  |  |
| ≡   | IDENTICAL TO |  |
| ≣   | STRICTLY EQUIVALENT TO |  |
| ≔   | COLON EQUALS  |  |
| ⇔   | LEFT RIGHT DOUBLE ARROW  |  |
| ⇒   | RIGHTWARDS DOUBLE ARROW  | Implies |
| ⊃   | SUPERSET OF  |  |

## Timing and Measuring
| Symbol  | Name  | Notes |
|:--------|:-----|:-----|
| ⚖   | SCALES  | |
| 🔬  | MICROSCOPE  |  |
| ⏰  | ALARM CLOCK |  |
| ⏱  | STOPWATCH  |  |
| ⏲  | TIMER CLOCK  |  |
| ⏳  | HOURGLASS WITH FLOWING SAND  |  |
| ⏿  | OBSERVER EYE SYMBOL |  |
| 🔎 | RIGHT-POINTING MAGNIFYING GLASS |  |

## Electrical State
| Symbol  | Name  | Notes |
|:--------|:------|:------|
| ⏻  | POWER SYMBOL |  |
| ⏽  | POWER ON SYMBOL | Power On |
| ⭘  | HEAVY CIRCLE  | Power off |
| ⏾  | POWER SLEEP SYMBOL | Sleep |

[Release notes](https://unicodepowersymbol.com/we-did-it-how-a-comment-on-hackernews-lead-to-4-%c2%bd-new-unicode-characters/); [compatible font](https://github.com/jloughry/Unicode)

## Pointers
| Symbol  | Name  | Notes  |
|:-----|:----|:----|
| ← | LEFTWARDS ARROW | |
| → | RIGHTWARDS ARROW | |
| ↑ | UPWARDS ARROW | |
| ↓ | DOWNWARDS ARROW | |
| ‹ | SINGLE LEFT-POINTING ANGLE QUOTATION MARK | |
| › | SINGLE RIGHT-POINTING ANGLE QUOTATION MARK | |

## Emoji that should have been on the keyboard
| Symbol  | Name  | Notes |
|:--------|:-----|:-----|
| 😱 | FACE SCREAMING IN FEAR | |
| 🙈 | SEE-NO-EVIL MONKEY | |
| 🙉 | HEAR-NO-EVIL MONKEY | |
| 🙊 | SPEAK-NO-EVIL MONKEY | |
| 👋 | WAVING HAND SIGN | |
| 👍 | THUMBS UP SIGN | |
| 🙌 | RAISING HANDS | Hallelujah |
| 👌 | OK HAND SIGN | Parfait |


## Phrases
These achieve the same goals of conciseness and expressivity, but are not recognised as individual characters.

* ¯\\_(ツ)_/¯
* (V)(°,,,,°)(V)

## Tools
* [Underlining](http://thejh.net/misc/unicode-underline)

## Font Support
* Ubuntu 19 with Pycharm 2019.2 causes Unicode glyphs to be invisible, with 0 width. To get around this, I followed the advice [here](https://youtrack.jetbrains.com/issue/IDEA-192107):
	```shell script
	sudo apt-get install -y fonts-symbola
	fc-cache --force --verbose
	echo "Restart the IDE now"
	```
