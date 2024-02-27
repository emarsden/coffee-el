# coffee.el -- Submit a BREW request to an RFC2324-compliant coffee device

[![License: GPL v2](https://img.shields.io/badge/License-GPL%20v2-blue.svg)](https://www.gnu.org/licenses/old-licenses/gpl-2.0)


This Emacs Lisp library allows Emacs users to submit a BREW request to an RFC2324-compliant coffee
device (implementing the [Hyper Text Coffee Pot Control
Protocol](https://en.wikipedia.org/wiki/Hyper_Text_Coffee_Pot_Control_Protocol), or HTCPCP). It
prompts the user for the different additives, then issues a HTCPCP BREW request to the coffee
device.

You can probably guess how coffee.el came about …yadda yadda everything but make coffee …yadda
yadda…

coffee.el requires a special BREW-capable version of Emacs/W3 to be installed.


## References

See [RFC 2324](https://www.rfc-editor.org/rfc/rfc2324).

See also [coffee-mode](https://github.com/defunkt/coffee-mode), a major mode for CoffeeScript and
IcedCoffeeScript. There is also a `coffee.el` meetup organized in San Francisco.



The **latest version** of this package should be available from

    https://github.com/emarsden/coffee-el/
