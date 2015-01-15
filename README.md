lib-bitters
===========

This is a replica of [Thoughtbot's Sass Bitters library](https://github.com/thoughtbot/bitters) but provided in a format that can be used as a submodule for other git projects to avoid having to add Bitter files to source control.

Usage
---

### Adding as a submodule

To add this library as a submodule, execute the following commands inside of your project. This will add this library as a submodule and checkout the current 0.10.1 version into a folder called "bitters."

	git submodule add -b v0_10 https://github.com/Sujevo/lib-bitters bitters
	git submodule update --remote

### Current Hosted Versions

Use the following table to see what branch to use for the corresponding version of Bitters.

| Version  | Branch           | Release Date   |
| -------- | ---------------- | -------------- |
| 0.10.1   | v0_10            | September 2014 |
| 0.10.1*  | v0_10-neat       | September 2014 |
| 0.10.1^  | v0_10-neat-rails | September 2014 |

\* The Bitters library either works with Neat or without Neat, if you are using Bitters together with Neat, use the `v0_10-neat` branch as it will have a modified `_base.scss` file with a Neat import ready.

\^ The Bitters library can be incorporated in a Rails project automatically so imports are handled specially. If you're not using Rails, then do not use this branch and use `v0_10-neat` instead which has a relative path to Neat helpers.

## Credits

[![thoughtbot](http://images.thoughtbot.com/bourbon/thoughtbot-logo.svg)](http://thoughtbot.com)

Bitters is maintained and funded by [thoughtbot, inc](http://thoughtbot.com). Tweet your questions or suggestions to [@bourbonsass](https://twitter.com/bourbonsass) and while you’re at it follow us too.

## License

Copyright © 2011–2014 [thoughtbot, inc](http://thoughtbot.com). Bitters is free software, and may be redistributed under the terms specified in the [license](https://github.com/thoughtbot/bitters/blob/master/LICENSE.md).
