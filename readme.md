# SYNAPTIC LIGHTROOM PRESETS 0.7

This is a collection of presets for Adobe Lightroom 4+ that I regularly use in my post-processing workflow. In the spirit of the open source software movement I am sharing them freely. Enjoy!

## INSTALLATION

Download these presets and copy them to your Lightroom 4+ presets folder. If you don't know where it is, try this help file:
http://helpx.adobe.com/lightroom/kb/preference-file-locations-lightroom-4.html

If you are upgrading I **strongly** recommend deleting the entire `Synaptic Presets` folder and reinstalling rather that overwriting files. I regularly rename or delete existing presets and folders as I work.

If you plan to modify my presets for your own usage but wish to remain updated I would suggest forking this project and learning the ins and outs of GitHub.

## USAGE

### ORGANIZATION

I recently divided my develop presets into several different folders:

* General: lens correction and noise reduction.
* Series 1: treatments from 2011 and earlier.
* Series 2: treatments from 2012.
* Series 3: treatments from 2013 to the present day. These are generally what I use on a day-to-day basis.
* Vignetting: exactly as it says on the tin.

Some additional notes:

* Presets marked (A) refer to autotone; you may wish to adjust toning in the basic panel to achieve a different look.
* Presets marked (W) alter white balance, often to achieve a desired effect.
* Instead of purely descriptive names many of my presets are named after the places I have been. I find this system useful as a mnemonic but it takes some getting used to.
* All presets in the main series folders do not affect lens correction, noise reduction, or vignetting, all of which should be applied separately.

### WORKFLOW

Here is an outline of my workflow, which is optimized for rapid processing:

1. Import photos into date-based folders and apply default presets. I use the "Lens Correction Plus" preset (under "General") which combines lens correction with a hint of noise reduction and vignetting. I also use a metadata preset (not included) to cover the basics *e.g.* copyright status (or lack thereof), contact information, etc.
2. Browse through the newly imported photos to identify *obvious* picks (keyboard shortcut "P") or rejects ("R"). The idea here is to work fast to reduce the number of photos that need to be processed. Finish up by filtering the current import by flagged and unflagged photos. (This hides rejected photos.)
3. Pick a representative photo from a batch of photos shot with similar lighting conditions. Try out different presets to get a rough idea of what looks good. Test out the difference between auto white balance and "as shot". Experiment with different vignetting levels. Zoom in and gauge how much noise there is. The idea here is to come up with a plan of attack for the rest of the photos in the series.
4. Select a bunch of photos in the film strip (at the bottom) and apply presets in batch. Start with noise reduction and vignetting and apply toning treatments last. Think of this as a "base coat" for your photos.
5. Start working through the photos, making individual modifications as you go. Generally speaking, once I set a base coat most of my modifications are limited to the "Basic" and "Tone Curve" tools. My style is to reduce highlights, increase shadows, and push contrast to make my photos more vivid and dreamlike. I seldom finalize photos without further tweaks of the initial preset.
6. If you find yourself making the same modification to several photos in a row (for example, reducing blue saturation), then it may be time to spin off a new preset for batch processing. Smaller changes can easily be accommodated by the "copy settings from previous" command. I try to leave cropping and graduated filters to the end specifically so I can copy settings from one photo to another without extra hassle.
7. Eventually I run through and use the pick, unflag ("U"), and reject shortcuts to finalize what photos will be prepared for export, kept around but otherwise left alone, or deleted from disk. Prepare for the next step by filtering by flagged photos only.
8. Metadata time! Most people probably don't care about this stuff but I am very OCD about adding titles and location data (using the excellent map module) to finalize the photos I plan to upload. Since I go by memory when geotagging photos I find this is easiest immediately after processing (with the images fresh in my mind).
9. Export all finalized photos in two batches: full-size copies for Flickr and archival purposes and 1920 px copies for Facebook, blogging, and mobile use.
10. Clean up workspace by deleting all rejected photos from disk (there is a shortcut for this).

## EXAMPLES

![Synaptic Lightroom Presets - Example 1](/synaptic-lightroom-presets-example-1.png "Synaptic Lightroom Presets - Example 1")

![Synaptic Lightroom Presets - Example 2](/synaptic-lightroom-presets-example-2.png "Synaptic Lightroom Presets - Example 2")

**For more examples [follow me on Flickr](http://www.flickr.com/photos/synapticism), check out a selection of my work in [my photography portfolio](http://synapticism.com/c/portfolio/photography), or [like me on Facebook](https://www.facebook.com/synaptic.imagery)!**

## DONATIONS

If you find these presets useful please consider making a donation! Not only do I give my presets away but my photos are also released under a Creative Commons license. My entire livelihood is based on free culture, in fact. This only works if people are generous! (Assuming, of course, that anyone derives value from my work.) Here are a variety of ways you can support me:

* Bitcoin: **124wj2hgRo7vyJLi68VuEz6uGi5DJnNyQS**
* Dogecoin: **DMTqKumNjutVuw6aogV4EsxkFaj4AbirUb**
* Flattr: http://flattr.com/thing/1266169/
* Paypal:

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B5KKQP6YJ5PUJ)

## SUPPORT

Please visit [Reddit](http://www.reddit.com/r/Lightroom) or [Flickr](http://www.flickr.com/groups/adobe_lightroom/) for general help with Lightroom. You are also welcome to discuss these presets on [Reddit](http://www.reddit.com/r/Lightroom/comments/1zjwxe/synaptic_lightroom_presets_07/) and [Flickr](https://secure.flickr.com/groups/adobe_lightroom/discuss/72157641868398153/). [Find me on Twitter](https://twitter.com/Synapticism) if you have any specific questions about using these presets.

## LICENSE

Copyright 2013-2014 [Alexander Synaptic](http://alexandersynaptic.com). Licensed under the GPLv3: http://www.gnu.org/licenses/gpl.txt

Please link back to my web site (http://synapticism.com) and/or this GitHub repository (https://github.com/synapticism/synaptic-lightroom-presets) if you make use of these presets.

*Redistribution is strongly discouraged.* I would rather you link back to this repository so that anyone interested in these presets can download the latest version. Thanks!