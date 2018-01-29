-Relocate additional resources to the bottom of the page (even if it looks ugly)
-External resources downloaded and served from within the site itself
-Static resources minified (css and js)

-Reduced image size to require less resizing

-since the js just wouldn't work if deferred, I placed the minimized scripts in-line, the reason it's in the middle is cause any other way would produce console errors.

-at this point, it was enough for the mobile version, but on desktop I still had lowwer than 90, so I'll do last step with the css as well.

-I had 99 on mobile and 89 on desktop, only by ALSO in-lining the font url I could get it over 90