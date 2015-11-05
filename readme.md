Tool List
---

All tools are public Github repositories

Repo                                                |Type              |Dependencies
----------------------------------------------------|------------------|----------------
Khan/tota11y                                        |in-page function  |JQuery
GoogleChrome/accessibility-developer-tools          |local Node service|Node
GoogleChrome/accessibility-developer-tools-extension|browser addon     |Closure Compiler
A11yance/a11y-core                                  |local Node service|Node/Grunt
prettydiff/semanticText                             |in-page function  |-
prettydiff/colorContrast                            |stand-alone page  |-
adobe-accessibility/Accessible-Mega-Menu            |web component     |JQuery
yargalot/grunt-accessibility                        |CLI               |Node/Grunt
nature/pa11y                                        |CLI               |Node/PhantonJS

My purpose in making such a list is that I want to be aware of what things are being evaluated so that I can get an idea of what things aren't being evaluated.  Accessibility is hard, and since many commercial sites don't produce high quality HTML accessibility is much harder than it should be.  Making accessibility easier to implement and understand is absolutely important.  Good tools help with this.

Sometimes the biggest problem with accessibility is that we know what to check for (most of the time), but we don't always know what grading aspects we are missing.  Examples include color contrast problems over gradient backgrounds and improper use of the `title` attribute.  Sometimes we also don't realize how the dynamic interactions we introduce with JavaScript alienate segments of our audience.

Accessibility advocates typically suggest having at least 3 accessibility tools frequently used, because they each are better in different particular areas.  An awareness of the tools available benefits everybody whether or not you intend to make accessibility tools.  Please submit pull requests with additional tools.
