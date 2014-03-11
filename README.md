New-Tongwentang-for-Chrome
==========================

New Tongwentang was created by [softcup](https://github.com/softcup) and is hosted on http://tongwen.openfoundry.org/

This fork includes a minor update to provide functionality to automatically convert after AJAX calls on certain websites.

This is important for some lessons on memrise.com to use the well-crafted HSK lessons with traditional characters (note that the mems don't work as well as they're designed for simplified characters).

The code is limited to the memrise.com domain since it causes a conversion on every DOM change (which happens often). I'm sure there's a better way to do it, but this works for now.
