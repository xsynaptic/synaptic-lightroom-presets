# SYNAPTIC LIGHTROOM PRESETS 0.6

This is a collection of presets for Adobe Lightroom 4+ that I regularly use in my post-processing workflow. In the spirit of the open source software movement I am sharing them freely. Enjoy!

## INSTALLATION

Download these presets and copy them to your Lightroom 4+ presets folder. If you don't know where it is, try this help file:
http://helpx.adobe.com/lightroom/kb/preference-file-locations-lightroom-4.html

If you are upgrading I **strongly** recommend deleting the entire Synaptic Presets folder and reinstalling rather that overwriting files. I regularly delete or rename existing presets or even entire folders to improve my workflow.

If you plan to modify my presets for your own usage but wish to keep updated I would suggest forking this project and learning the ins and outs of GitHub.

## USAGE

I recently divided my presets into treatments, effects (*e.g.* vignetting), lens correction, and noise reduction. Presets from different groups do not overwrite any settings from the others; you can safely play with effects and later apply treatments and lens correction (or vice versa). Previously I used the lens correction feature for vignetting but this is the wrong way to apply such an effect. Now all vignetting is done properly with post-crop effects. Similarly, my older presets included noise reduction values, but this isn't a smart approach. Noise reduction is now accomplished with a set of additional presets in the General folder.

Just to be clear, you will probably want to apply three different *classes* of preset to each photograph you work on:

* A treatment (anything not under General).
* Vignetting (the "soft shadow" presets under General).
* Noise reduction (also under General).

### ORGANIZATION

Nowadays I am grouping my presets into folders by year. Some notes:

* Presets suffixed with `(A)` refer to autotone; you may wish to adjust toning in the basic panel to achieve a different look.
* Presets without autotone may seem too light or too dark for your photos. You may need to tweak the results depending on the exposure value of your photos.
* Experimental: everything else, including the "night" presets I was dabbling with earlier, presets I no longer use, etc. Use with caution or delete this folder indiscriminately.
* General: lens correction, noise reduction, vignetting, etc.

Instead of purely descriptive names many of my presets are named after the places where I first developed them. This is a handy mnemonic to have once you start playing around with them.

### WORKFLOW

Here is an outline of my workflow:

* Import photos into date-based folders while applying develop and metadata presets.
    * The develop preset I apply by default combines lens correction with soft vignetting. This preset is available in the "general" folder.
    * A metadata preset is not included here but it is easy to make your own and apply it when importing new photos. I set the basics *e.g.* copyright status, contact information, etc.)
* Browse through all newly imported photos to quickly pick (P) or reject (R). Skip to the next photo when uncertain. Then filter by flagged and unflagged. (This feature is available in the bottom right of the develop module just above the filmstrip.) The purpose of this step is to focus on the photos worth working on.
* Now it is time to get creative: apply treatment presets to individual photos and modify as needed. Often when I work on a given shoot I will apply the same preset to each photo as a base and then edit from there. Remember: presets are often just a starting point for further experimentation! Along the way make sure to flag photos for export and unflag photos that do not make the cut.
* Apply noise reduction and vignetting presets, often in bulk. This can be done before or after working with treatments.
* Add essential metadata to all finalized photos:
    * Filter by flagged photos only.
    * Add location data using the map module.
    * Add a title using the library module.
* Export all finalized photos.
    * Full-size copies for Flickr and archival purposes.
    * 1920 px per side copies for Facebook, blogging, and mobile use.
* Clean up workspace by deleting rejected photos from disk.

## EXAMPLES

![Synaptic Lightroom Presets Example 1](/example1.png "Synaptic Lightroom Presets Example 1")

For more examples find me on Flickr:
http://www.flickr.com/photos/synapticism

Or check out a selection of my work in my photography portfolio:
http://synapticism.com/c/portfolio/photography

## DONATIONS

Find these presets useful? Donations are very welcome!

* Bitcoin: 124wj2hgRo7vyJLi68VuEz6uGi5DJnNyQS
* Flattr: http://flattr.com/thing/1266169/

## SUPPORT

Please visit Reddit or Flickr for general help with using Lightroom presets:
http://www.reddit.com/r/Lightroom
http://www.flickr.com/groups/adobe_lightroom/

Discuss these presets here:
http://www.reddit.com/r/Lightroom/comments/1cnkf1/my_collection_of_lightroom_presets_is_now/
http://www.flickr.com/groups/adobe_lightroom/discuss/72157633377500237/

## LICENSE

Copyright 2013 Alexander Synaptic. Licensed under the GPLv3: http://www.gnu.org/licenses/gpl.txt

Please link back to my web site (http://synapticism.com) and/or this GitHub repository (https://github.com/synapticism/synaptic-lightroom-presets) if you make use of these presets.

*Redistribution is strongly discouraged.* I would rather you link back to this repository so that anyone interested in these presets can download the latest version. Thanks!