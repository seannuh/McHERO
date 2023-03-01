# McHERO


This is a mod of zeroantix HERO theme.

This theme includes integration of the following extensions, install and configure those for most bang for your buck:
* LibraryManagement - for feature icons
* ScreenshotVisualizer - for displaying screenshots taken in game, currently displayed in alphabetical order based on screenshot file names
* ExtraMetadataLoader - for displaying logos and trailers, trailers will stream directly from Steam if game is in Steam library or has a link to it's Steam page
* NewsViewer - will display most recent news article from Steam only, open web button does not work
* DuplicateHider - will display other versions when the '...' button is pressed in the game details page
* SuccessStory - for displaying achievement progress on game details page

![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/00.png)
![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/01.png)
![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/02.png)
![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/03.png)
![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/04.png)

Below are the recommended settings that you'll want to set in both fullscreen and desktop settings.

![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/settings rec.png)
![picture alt](https://github.com/seannuh/McHERO/blob/main/MEDIA/settings rec 2.png)

A few caveats I would like to address.
* Horizontal and vertical view will be skewed (and possibly broken) when covers are not set to 1:1 aspect ratio in desktop settings as shown above.
* You can change or add images shown in the tabs on the main page by placing files corresponding to your preset names into the theme folder under Icons > Filter.
* You can change or add platform or source icons that are show on the GameDetails page by placing files corresponding to the platform or source the game is assigned into the folder under Icons > Source.
* With the ScreenshotsVisualizer integration, obviously the more screenshots you have for a game, the longer this will take to load and will eat up your RAM as a result. I have made it so it will disable once leaving the GameDetails page and give you those resources back, but just keep in mind if you have something with an obscene amount of screenshots.
* The way both the screenshots and details column on the right side of the GameDetails page scroll up and down, they do not currently reset even when moving to another game, so if something was scrolled down for one game and you go to the next, things may be pushed off screen until you use the scroll buttons again.
