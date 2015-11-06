Tool List
---

All tools are public Github repositories primary written in HTML and/or JavaScript

Repo                                                                                                                           |Type              |Purpose          |Dependencies
-------------------------------------------------------------------------------------------------------------------------------|------------------|-----------------|------------
[Khan/tota11y](https://github.com/Khan/tota11y)                                                                                |in-page function  |semantic analysis|JQuery
[GoogleChrome/accessibility-developer-tools](https://github.com/GoogleChrome/accessibility-developer-tools)                    |local Node service|code audit       |Node
[GoogleChrome/accessibility-developer-tools-extension](https://github.com/GoogleChrome/accessibility-developer-tools-extension)|browser addon     |code audit       |Closure Compiler
[A11yance/a11y-core](https://github.com/A11yance/a11y-core)                                                                    |local Node service|?                |Node/Grunt
[prettydiff/semanticText](https://github.com/prettydiff/semanticText)                                                          |in-page function  |semantic analysis|-
[prettydiff/colorContrast](https://github.com/prettydiff/colorContrast)                                                        |stand-alone page  |color contrast   |-
[adobe-accessibility/Accessible-Mega-Menu](https://github.com/adobe-accessibility/Accessible-Mega-Menu)                        |web component     |web component    |JQuery
[yargalot/grunt-accessibility](https://github.com/yargalot/grunt-accessibility)                                                |CLI               |code audit       |Node/Grunt
[nature/pa11y](https://github.com/nature/pa11y)                                                                                |CLI               |code audit       |Node/PhantonJS
[nature/pa11y-dashboard](https://github.com/nature/pa11y-dashboard)                                                            |stand-alone page  |reporting        |Node/PhantomJS
[rackt/react-a11y](https://github.com/rackt/react-a11y)                                                                        |React Component   |code audit       |React
[a11yproject/a11yproject.com](https://github.com/a11yproject/a11yproject.com)                                                  |stand-alone page  |informational    |Ruby
[jxnblk/colorable](https://github.com/jxnblk/colorable)                                                                        |stand-alone page  |color contrast   |-
[LeaVerou/contrast-ratio](https://github.com/LeaVerou/contrast-ratio)                                                          |stand-alone page  |color contrast   |-
[squizlabs/HTML_CodeSniffer](https://github.com/squizlabs/HTML_CodeSniffer)                                                    |stand-alone page  |code audit       |-
[wesbos/keycodes](https://github.com/wesbos/keycodes)                                                                          |stand-alone page  |keyboard keycodes|-
[howlowck/Akbar](https://github.com/howlowck/Akbar)                                                                            |bookmarklet       |vision simulation|-


My purpose in making such a list is that I want to be aware of what things are being evaluated so that I can get an idea of what things aren't being evaluated.  Accessibility is hard, and since many commercial sites don't produce high quality HTML accessibility is much harder than it should be.  Making accessibility easier to implement and understand is absolutely important.  Good tools help with this.

Sometimes the biggest problem with accessibility is that we know what to check for (most of the time), but we don't always know what grading aspects we are missing.  Examples include color contrast problems over gradient backgrounds and improper use of the `title` attribute.  Sometimes we also don't realize how the dynamic interactions we introduce with JavaScript alienate segments of our audience.

Accessibility advocates typically suggest having at least 3 accessibility tools frequently used, because they each are better in different particular areas.  An awareness of the tools available benefits everybody whether or not you intend to make accessibility tools.  Please submit pull requests with additional tools.
