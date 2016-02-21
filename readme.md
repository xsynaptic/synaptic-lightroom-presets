# SYNAPTIC LIGHTROOM PRESETS

This is an evolving collection of presets for Adobe Lightroom 4+ that I regularly use in my post-processing workflow. In the spirit of the open source software movement I am sharing them freely for everyone to use, adapt, and study.

![Synaptic Lightroom Presets](/Samples/synaptic-lightroom-presets-banner.jpg "Synaptic Lightroom Presets")



## INSTALLATION

[Download and unpack this archive](https://github.com/synapticism/synaptic-lightroom-presets/archive/master.zip) and copy the folders beginning with `Synaptic Presets` to your Lightroom 4+ presets folder. To find your presets folder try searching your system for `Develop Presets`. Alternately, open up `Preferences`, select the `Presets` tab, and click on `Show Lightroom Presets Folder`. The `Synaptic Presets` folders should be copied into `Develop Presets`.

If you are upgrading I **strongly** recommend deleting every `Synaptic Presets` directory (unless you have made modifications of your own, of course). I regularly rename or delete existing presets and folders as I work and simply overwriting files won't necessarily give you the most current collection of presets. The latest version always represents the most finely tuned and current set of presets from my collection.

Of course, if you know your way around the command line you would be much better off cloning the repo or installing with Bower: `bower install synaptic-lightroom-presets`. It is beyond the scope of this document to explain how to use these tools but I can assure you it is worthwhile learning how to do this sort of thing. You can also set things up so you can modify these presets and still merge updates by *forking this project* and [learning the ins and outs of GitHub](https://try.github.io).



## USAGE

Please read this document carefully to get the most out of these presets. Many commercial Lightroom preset vendors suggest that all you need is one click to transform an image. I take a different approach with my presets, breaking out lens correction, noise reduction, and vignetting from toning treatments. I also conceive of presets as a *starting point* for further modification.

### ORGANIZATION

I divide my development presets into different folders, each representing a different category of preset:

* **General**: lens correction and noise reduction; the subtle stuff you won't see when you're zoomed out.
* **Series 1 to 4**: tone curve, colour, saturation, luminance, split toning, and camera calibration settings. These are probably what you're thinking of when you think "Lightroom presets".
* **Vignetting**: post-crop effects to add vignetting (shadows along the edges) independently of other treatments.

Presets in each category do not affect the settings of any other. This modular approach facilitates easier batch processing. An example: you can select a bunch of photos and adjust noise reduction or vignetting without affecting the colour treatment.

### CONVENTIONS

* Almost all my colour treatments (*i.e.* in the Series folders) use autotoning; you will likely want to adjust toning in the basic panel to achieve a different look. I tend to reduce highlights, boost shadows, and increase contrast to emphasize details but you should play around and find out what works for you.
* The presets in the Series folders are organized roughly from oldest to newest. Previously the older presets weren't really up to the quality standards of the newer presets but I have since refined those older presets with the benefit of everything I have learned since originally publishing them. Even so, if you are evaluating these presets I suggest experimenting with the later series rather than starting at the beginning.
* The preset number (e.g. Changhua 1 or Bangkok 2) doesn't mean anything in particular—a higher number does not mean a preset is better. When I create a variation on an existing preset (e.g. when working on a batch of photos with overcast rather than clear skies) I like to keep it close to the original for reference.
* Instead of purely descriptive names many of my presets are named after the places I have been. I find this system useful as a mnemonic but it may take some getting used to.

### WORKFLOW

Here is an outline of my workflow:

1. Import photos into date-based folders while automatically applying default development and metadata presets. Personally I use the "Lens Correction Plus" preset (under "General") which combines lens correction with a hint of noise reduction and vignetting to save myself the trouble of doing so later. The metadata preset (not included here) covers copyright and contact information; you'll want to create your own from scratch to match your needs. The use of these default presets is a major time-saver and won't take long to setup.
2. Browse through the newly imported photos to identify *obvious* picks `P` (keyboard shortcut) or rejects `R`. The idea here is to work fast to *reduce the number of photos that need to be processed*. I finish up by filtering the current import by flagged and unflagged photos, hiding rejected photos.
3. Pick a representative photo from a batch of photos shot under similar lighting conditions. Try out different colour treatment presets to get a rough idea of what looks good. Test out the difference between auto white balance and "as shot" (I often find that Lightroom wants to make my photographs way too yellow). Experiment with different vignetting levels. Zoom in and gauge how much noise there is. The idea here is to come up with a plan of attack for the rest of the photos in the series.
4. Select a bunch of photos in the film strip (at the bottom) and *apply presets in batch*. Start with noise reduction and vignetting and apply toning treatments last. Think of this as a *base coat* for your photos.
5. Start working through the photos, making individual modifications as you go. Generally speaking, once I set a base coat most of my modifications are limited to the *Basic* and *Tone Curve* tools. My style is to reduce highlights, increase shadows, and pump up the contrast to make my photos more vivid and dreamlike. I almost never finalize photos without further tweaks of the initial preset; there is no such thing as a "one-click wonder" preset!
6. If you find yourself making the same modification to several photos in a row (for example, reducing blue saturation), then it may be time to spin off a new preset for batch processing. Smaller changes can easily be accommodated by the "copy settings from previous" command `command+alt+V` (learn this shortcut—it'll save you loads of time—but you may want to follow up with another round of autotone). I try to leave cropping and graduated filters to the end specifically so I can copy settings from one photo to another without extra hassle.
7. Eventually I browse through the photos I have just worked on, using the pick, unflag `U`, and reject shortcuts to finalize what photos will be prepared for export, kept around but otherwise left alone, or deleted from disk.
8. Metadata time! Most people probably don't care about this stuff but I am very OCD about adding titles and location data (using the excellent map module) to finalize the photos I plan to upload. Since I go by memory when geotagging photos I find this is easiest immediately after processing (with the location of the images fresh in my mind).
9. Export all finalized photos in two batches: full-size copies for Flickr and archival purposes and 1920 px copies for Facebook, blogging, and mobile use. (Update: nowadays I publish directly from Lighroom to Flickr; it's way easier than dealing with files at any step of the process.)
10. Clean up workspace by deleting all rejected photos from disk.



## SAMPLES

![Synaptic Lightroom Presets Sample - Example 1](/Samples/synaptic-lightroom-presets-example-1.png "Synaptic Lightroom Presets Sample - Example 1")

![Synaptic Lightroom Presets Sample - Example 2](/Samples/synaptic-lightroom-presets-example-2.png "Synaptic Lightroom Presets Sample - Example 2")

![Synaptic Lightroom Presets Sample - Checheng](/Samples/synaptic-lightroom-presets-sample-checheng.jpg "Synaptic Lightroom Presets Sample - Checheng")

![Synaptic Lightroom Presets Sample - Hong Kong](/Samples/synaptic-lightroom-presets-sample-hong-kong.jpg "Synaptic Lightroom Presets Sample - Hong Kong")

![Synaptic Lightroom Presets Sample - Seoul](/Samples/synaptic-lightroom-presets-sample-seoul.jpg "Synaptic Lightroom Presets Sample - Seoul")

![Synaptic Lightroom Presets Sample - Mong Kok](/Samples/synaptic-lightroom-presets-sample-mong-kok.jpg "Synaptic Lightroom Presets Sample - Mong Kok")

![Synaptic Lightroom Presets Sample - Maokong](/Samples/synaptic-lightroom-presets-sample-maokong.jpg "Synaptic Lightroom Presets Sample - Maokong")

[Additional samples are available on the release announcement on my blog](http://synapticism.com/synaptic-lightroom-presets-1).

**For even more examples of my work in Lightroom check out [Synapticism](http://synapticism.com/meta/photography), my regularly updated photo blog; [Flickr](http://www.flickr.com/photos/synapticism); and [Facebook](https://www.facebook.com/synaptic.imagery).**



## DONATIONS

If you find these presets useful please consider making a donation! Here are a variety of ways you can show your support:

* [Bitcoin](https://bitcoin.org/): **1AkzqWAqsxedefHq9G4hcYTmhBWkmJfF14**
* [Stellar](https://launch.stellar.org): **gpkNMoRefk8YV7PakSqyHEg1BNsmzAn4Ne**
* Paypal:

[![Donate](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=B5KKQP6YJ5PUJ)



## SUPPORT

Please visit [Reddit](http://www.reddit.com/r/Lightroom) or [Flickr](http://www.flickr.com/groups/adobe_lightroom/) for general help with Lightroom. [Find me on Twitter](https://twitter.com/Synapticism) if you have any specific questions about using these presets.



## LICENSE

Imagery copyright 2013-2016 [Alexander Synaptic](http://synapticism.com); permission is granted to reuse these images to promote this preset library as long as proper credit and a link back is given. Presets licensed under the [GPLv3](https://www.gnu.org/licenses/quick-guide-gplv3.html): http://www.gnu.org/licenses/gpl.txt

Please link back to [my web site](http://synapticism.com) and/or [this GitHub repository](https://github.com/synapticism/synaptic-lightroom-presets) if you make use of these presets!

*Redistribution of these presets is strongly discouraged.* I would much rather you link back to this repository so that anyone interested in these presets can download the latest version. *Thanks!*
