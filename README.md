#EO1 Screen.

This repo provides automatically updating image screen-savers for the [Electric Objects EO1](https://www.electricobjects.com/).

In practice, what that means is that your EO1 display will change automatically without needing to open the app.

The feed pulls the latest image from a variety of Twitter feeds and deplays them on a page specifically formatted for the EO1.

This means that the images on your EO1 will always be fresh and interesting.

### How to:

Copy one of the links below for the screen you would like to show.
Visit the Electric Objects custom URL site: [https://www.electricobjects.com/set_url](https://www.electricobjects.com/set_url)
Paste the copied link (i.e. [http://www.eo1screen.com/life](http://www.eo1screen.com/life)) in the "Display URL" field and click Submit.

### Available Displays

These are the available image feeds currently. More coming soon!

* NASAGoddardPix - @NASAGoddardPix on Twitter - We share cool science. this is the official image/video tweeting account for @NASAGoddard.
* EarthPix - @EarthPix on Twitter - Amazing pictures of places, people, animals, and nature.
* History In Pics - @HistoryInPics on Twitter - Sharing the most powerful and entertaining historical photographs ever taken.
* LIFE - @LIFE on Twitter - Incredible stories and treasured photographs from the LIFE archive.
* Brilliant_Ads - @Brilliant_Ads on Twitter - The most creative, unique, controversial, remarkable and powerful ads, signs and marketing related things from around the world.
* Archillect - @archillect on Twitter - The ocular engine.
* Photography Blogger - @PhotoBlggr on Twitter - Inspiring photographers with some great photography subjects.
* The Big Picture - @big_picture on Twitter - The Big Picture is a photo blog created by the photo editors of @BostonGlobe, with the best in photojournalism from around the world.
* Telegraph Pictures - @TelegraphPics on Twitter - Photo galleries and the latest news pictures from http://Telegraph.co.uk
* NYTimes Photo - @nytimesphoto on Twitter - Tweeting about photography and visual journalism in the news and on our radar.
* Magnum Photos - @MagnumPhotos on Twitter - Magnum Photos is a photographic cooperative of great diversity and distinction owned by its photographer members.
* 500px - @500px on Twitter - 500px is the premier photography community and licensing marketplace. Follow us for awesome photos every day.
* Getty Images - @GettyImages on Twitter - Moving the world with images.
* Tweegeemee Bot - @tweegeemee on Twitter - I'm a #Clojure twitterbot by @RogerAllen. Favorite & retweet my images to select them for future genetic algorithm breeding.


### Instagram Feed

The site also supports pulling images from Instagram via a hashtag.


### Contact Info

If you would like to suggest a twitter account for EO1 displaying or just want to get in touch. Please submit a pull request or email eo1screen@johncoogan.com.


### Twitter Feed Widget

In order to pull images from the Twitter feed on the front-end. The pages use an open-source library created by Jason Mayes called Twitter Post Fetcher v13.1. Here is the disclosure about that library:

/*********************************************************************
*  #### Twitter Post Fetcher v13.1 ####
*  Coded by Jason Mayes 2015. A present to all the developers out there.
*  [www.jasonmayes.com](www.jasonmayes.com)
*  Please keep this disclaimer with my code if you use it. Thanks. :-)
*  Got feedback or questions, ask here:
*  [http://www.jasonmayes.com/projects/twitterApi/](http://www.jasonmayes.com/projects/twitterApi/)
*  Github: [https://github.com/jasonmayes/Twitter-Post-Fetcher](https://github.com/jasonmayes/Twitter-Post-Fetcher)
*  Updates will be posted to this site.
*********************************************************************/

In order to use create a new page for a Twitter feed, you will need to create a twitter widget and generate an ID.

### HOW TO CREATE A VALID ID TO USE: ###
* Go to www.twitter.com and sign in as normal, go to your settings page.
* Go to "Widgets" on the left hand side.
* Create a new widget for what you need eg "user time line" or "search" etc.
* Feel free to check "exclude replies" if you don't want replies in results.
* Now go back to settings page, and then go back to widgets page and
* you should see the widget you just created. Click edit.
* Look at the URL in your web browser, you will see a long number like this:
* 345735908357048478
* Use this as your ID below instead!
