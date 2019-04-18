# Notes on my fork

* This adds an inline preview button
* It works for what it is

## Bugs
* It doesn't really work if you also have a full-page preview, full page, or regular preview button
* But since I don't use those, it doesn't matter

## Changes
* Updated gulpfile to use gulp 4.0
* Added `toggleSideBySideInline`
* Made gulp NOT uglify - since that will happen automatically in my build, and is easier for debugging.