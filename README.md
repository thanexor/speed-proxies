# speed-proxies
Template to make physical proxy trading cards really quickly for Magic: the Gathering.  If you're crafty, you can DIY an entire commander deck in under 60 minutes.

Should also work for Pokemon, Yu-Gi-Oh, and other TCGs.

<img width="380" alt="image" src="https://github.com/thanexor/speed-proxies/assets/199630/9e340452-fa77-4154-9882-45b870174d77">


# Usage
You'll need: Photoshop, metal ruler, sharp blade.  If you really don't have a ruler and blade, you can use scissors.

* Download `.psd` template and open in Photoshop
* Show guides in Photoshop (ctrl/cmd+H)
* Copy a card image and paste into Cards group
  * <img width="248" alt="image" src="https://github.com/thanexor/speed-proxies/assets/199630/76ed7b34-2960-4e54-8d3a-3d8f29ce2156">
* Resize image to completely fill one of the slots within the guides
  * <img width="548" alt="image" src="https://github.com/thanexor/speed-proxies/assets/199630/0c29a8af-9476-4c69-bdbb-8e639a78c7e7">
* Print your sheet of 9 cards, allow clipping & don't scale
* Use cut marks to align your blade/scissors and cut
* Behold!  Cards.

# Hot tips for speed & quality
* Most efficient cutting technique:
  1. Cut the top and bottom margin off (avoid extra cuts on top/bottoms of cards)
  2. Cut off right side margin, then cut down each column of cards (cut columns away from side margins)
  3. Cut individual cards free from the columns with scissors (easy to make straight cuts with scissors on short distances & faster than aligning a straightedge and blade-cutting nine times)
* Forget cutting off the white corners.  It takes forever and is very fiddly.  If you really want rounded corners on your proxies, do a search for "craft corner cutter" so you can punch them out instead.  If speed is important to you like it is to me, use the corner covers and keep your proxies square.
* You should sleeve these proxies.  Damage from play is only a minor factor, but more importantly, shuffling DIY proxies without sleeves is nearly impossible.  Especially with square corners.
* For best print quality:
  * Use only premium high gloss photo paper.  Anything less looks fake, and doesn't feel at all like a card.
  * Use name-brand photo paper.  I use Epson Ultra Premium Photo Glossy paper (S042175).  I've tried a few different brands of paper, and unfortunately all low-cost glossy photo papers from Amazon all would not absorb ink fast enough to print a whole sheet.
  * Photoshop print settings that matter: Rendering intent (use Saturation), Position & size (check 'Center'), Scaled Print Size (*don't* check 'Scale to fit media').

<hr>

# Goals
* Go from digital image to printed & cut card proxy with least amount of human effort possible.
* Allow quick deck iteration with physical cards.
* Help normalize proxy creation.  Brewing decks is so much more fun and freeing when unfettered by finance.

# Future
* Is it possible to find a paper that allows printing card backs as well?
* Does Gimp work?  Does anyone care?
* Figma?

# Release notes
## v5
* Added black-normalizing layer.  I noticed that color grading on card images from Scryfall and other sources is very inconsistent.  This causes the 'black' borders of black-bordered prints to be highly varied in actual printed darkness.  In the Overlays group, I added an optional layer that will darken blacks that are too light, creating a dark and consistent border.
* Added cut line dots.  This optional layer shows teeny little dots at the card corners for cut alignment.  Dots have less of a visual footprint than lines, which lets you be a little less meticulous during cutting. <br><br> <img width="364" alt="image" src="https://github.com/thanexor/speed-proxies/assets/199630/5b1d2376-a4d2-4132-a5aa-14df9f5fda24">
* Cut lines brightness reduced.  Lines are too visible in the printed version, and unless you're 100% precise with all cuts it leaves visible fragments of the cut lines behind.

## v4
* Added corner covers layer.  These optional diamond-looking shapes are intended to make proxies square as a default.  They cover where the corners of card images meet, effectively squaring off card edges. <br><br> <img width="247" alt="image" src="https://github.com/thanexor/speed-proxies/assets/199630/91eb4b79-0872-4c0a-8f1c-f0dd97114268">
* Added basic cut lines.

## v3
* Sizing revamp.  Printed proxies should be nearly identical to the sizing of official MTG cards.
  
