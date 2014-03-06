New-Tongwentang-for-Chrome
==========================

Minor update to the amazng New Tongwentang Chrome tool that converts simplified and traditional mandarin.

This conversion did not work automatically in memrise.com (a great language study utilty) since the HTML was loaded through AJAX.

I added a check to catch the AJAX changes and apply the automatic conversion.

This is great for converting the well-crafted HSK lessons to traditional characters.

The code is limited to the memrise.com domain since it causes a conversion on every DOM change (which happens often). I'm sure there's a better way to do it, but this works for now.
