# About "Enchanted Elves" skin for PlaneShift

"Enchanted Elves" skin is based on Elves GUI skin version 2.0 for PlaneShift 0.5, with some fixes and enchantements. Original creators Cherppow &amp; Vengeance. Special thanks to Rizin, Lanarel, weltall, Xordan and LigH. And my special thanks to Bonifarzia.

Skin forum thread: http://www.hydlaaplaza.com/smf/index.php?topic=41186.0
ANY FEEDBACK is welcomed!

[PlaneShift] (http://www.planeshift.it) is a Role Playing Game immersed into a 3D virtual fantasy world which is fully free to play. Fully free means you will have no surprises of premium content which will limit your gameplay or unbalance the game. There are no limitations in skills, ranks, abilities, items you can gain with your account.

## Common Goals

* Be visually compatible with defaut "Elves v2" skin
* Add some polishing to it and improve usability
* Increase compactness (not dramatically)
* Be "Better "Elves v2" :) At least to some players...

## Plans and ideas
   
* Add numeric representation to mana and HP in Info window (like in BoNeSkin, but not % - don't know how)
* Add progressbars to Weigth and Capacity in inventory
* Use less decorative font for book writing
* Add separate background to Book writing window (not to scale readbook.png)  
* Add spellcheck to char description
   
# Changelog

## Changes in 0.6.1-alpha version:

* Added AttackQueueDisp widget to fix new PS client 0.6.1 crush then loading skin version 0.6.0-beta.
* AttackQueueDisp widget is hidded - attack queue is not used by now anyway.
* Custom active magic & shortcuts windows were disabled - need more work to explore and adapt new features. 
* Skin version number now follows PS client's.
* Project moved to GitHub - check [releases] (https://github.com/roman-yagodin/PlaneShift.EnchantedElves/releases) to get new skin version!

## Changes in 0.6.0-beta version:

* Quick fix release for PS 0.6.0 - just to be able to use Enchanted Elves with a new PS.
* Expect next relase with more sane changes in about a week.
* Button size in the new active magic window set to 32 - default 48 is hell of a large.
* Disable stats bars in the new shortcut window - no need to duplicate Info and Stats windows. 	 

## Changes in 2013/04/24 version:

### Skill window:
   
* Added extra width to skill value column to prevent partial hiding of values - and maybe, it need even more!
* Few extra items in a skill list, so more skills are visible at once.
* Filter button moved to the left of "X" in a window title.
* Removed useless tab buttons attachments and fixed tab button misplacement.
* Description textbox and skill list are same width.
* Experience bar height set equal to stamina bars.
* Reduced window borders - window now more compact.
  
### Buddy & Ignore windows:

* Added button to open Ignore window from Buddy.
* Minimalistic buttons style.
* No maximum height and width for both Buddy and Ignore.
* Make Ignore window more like Buddy (same button placement, style, window behaviour, etc.) 
* Added tooltips for buttons.

### Active magic window:

* Debuff list are not resizable anymore and resizing of buff list is more predictable (no need to use PROPORTIONAL anchoring). Reason: I don't most people not theyr chars would feel comfortable with a wide list of active debuffs, so I hope that having 4-5 items in a debuff list is a sane value. 
* Minimum window width are same with Buddy window, to simplify stacking.
* No maximum height and width for a window.

### Inventory & Small inventory:

* "Switch to small / full inventory" buttons moved to the left of "X", which is more common and recognizable.

### Cursor:

* New cursor based on classic cursor and eye icon from "Elves" art.
* A small collection of cursors from various skins are in "cursors" folder inside extras.zip

### Info window:

* Colors of all bars reverted to base from "Elves"

## Changes in 2013/02/20 version:

### Common:

* Used more sensible quest icon for a "Scribe" resource, old icon now "Scribe_old"

### Toolbar:
   
* Some minor sync between control_styles.xml with control.xml

### Book reading window:

* Window title removed
* Added "Сlose" button on the book page with 'X' icon
* "Write" and "Save" buttons are relocated and use icons instead of text labels
* Book title now left-aligned and 2 pages in width - no more cutted titles!
* Book title now of "Bistre" color (almost black brown)
* "Prev Page" button tooltip now "Previous Page"
* One more line of text on a page

### Write book window:

* Window title removed
* Added "Сlose" button on the book page with 'X' icon
* "Cancel" button marked as invisible - same as close button
* "Load" and "Save" buttons are relocated and use icons instead of text labels
* "Write Book" texture coordinates recalculated to keep original texture aspect

### Info window:

* Starting colors of progressbar's gradients now darker - gradients more visible
* Target HP, Health and Mana progressbars are now thicker (may be useful in the future)
* Stamina progressbars combined with Health and Mana
* Changed font family, size and color to make current time more visible
* Some tooltip text changed

## Changes in 2013/02/15 version:

### Inventory window:
   
* Removed right vertical decoration (tree) - makes a scrollbar more visible
* Character doll now bigger, camera distance set to 2.0 (does kra fit in it?)
* Added working "Switch to Small Inventory" button just bottom to "X"
* "View Item" button bigger and placed near right window border
* "Tria:" label now "Trias:" (like in Small Inventory window, maybe on the contrary is right?)
* Some position adjustments of widgets inside Inventory window
* Size of Inventory window slightly decreased
* "Back" slot tooltip now "Back", not "Back_inv"

### Small Inventory window:

* Added working "Switch to Full Inventory" button just bottom to "X"
* Size of Small Inventory window slightly decreased

### Study window:

* Added default text Study window "You have to read the book first!" to help new users
* Study window now resizable. WARNING: can lag on resize if contained text is big!
* Study window title now "Study Notes", not "Study notes:"
* Study window not keeping it's aspect ratio on resize

### Widget options window:
   
* Removed background image in bottom part of Widget options - make window style unified
* Fix Widget options scrollbars size and label positions
   
### Active magic window:

* Used original font for effect names - some users may find cupandtalon.ttf of size 11 almost unreadable
* Added tooltips to effect lists to "replace" Buff / Debuff labels

## Changes in 2013/02/14 version (first release for PlaneShift 0.5.9.4)

### Active magic window:

* Window title now "Active Effects", since not all effects have magical nature
* Active effects lists now stacked vertically
* Added resizing to window and proportional resizing to listboxes (not ideal, but acceptable)
* Buff / debuff labels removed - user can easily distinguish buffs and debuffs by color and location
* Column width set to 512 supress ugly horizontal scrolling for long effect names
* Changed font for effect names to cupandtalon.ttf (default is too boring, IMHO)
* Checkbox is invisible - you can set window popup behaviour in options

### Chat window: 
  
* Width of scrollbars set to 20 to fix wrong arrows placement
* Chat buttons width increased to hold "Channels" and "Whisper" labels
* Channels button tooltip set to "Channels", not "Chat"
* Inputbox height of  slightly decreased

### Toolbar styles:

* All toolbar buttons relocated to 64x64 grid
* Active crystal button moved to (16,16) for all styles
* Set minimum icon size to 24
* style5 and style2 buttons reordered to separate social / system and other function
   
### Buddy window:

* Buttons are moved to the top-left and have fixed positions
* Some resizing and position adjustments

### Book writing  window:

* Using "Brown (web)" color instead of "Red" for spellChecker


