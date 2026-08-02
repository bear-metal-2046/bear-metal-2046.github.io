---
title: Laser Cutting Guide
description: How to laser cut like a pro
---

??? note "Note:"
    At the start of this guide most of the settings that are stated here are **very general** and there will be many cases (if not most cases) in which you will have to mess with the setting based on the specific material that you are using especially as materials get thicker. Just keep in mind that laser cutting is driven by a lot of **guessing and feel**. To be *good* you just have to try things and get used to the laser. Trial and error is the name of the game. But this doesn’t mean you can be an idiot if it looks like it will burn or cause damage, don't **do it** or at least be careful as there is always a chance of some issues.

# How to complete a laser job

## Generating a file and importing to Illustrator

1. Design a part in inventor that can be made out of ⅛,¼,or ½ plates.  
2. Click on the face that will be cut and use “export face” save as a .dxf file.  
3. Save that file with a name that can be found.  
4. Open Adobe Illustrator.  
5. Open a new file with the correct settings.  
   1. Max size 32in by 20in  
   2. Black for engraving  
   3. Red for cutting  
6. Click File \-\> Place. When importing a file, make sure to check “import file with original dimensions”.  
7. Once you have checked that the design will fit on the bed and has the right colors where they should save as a .AI file.

## Moving the file on to Ruby

1. If not on a computer with Ruby installed, move the file to a flash-drive and add to the laser computer.  
2. Open Ruby.  
3. Open the design tab and click on the “import design” button to upload the file.  
4. Double check that everything is right, especially screw holes.  
5. Click [Fit to design](#fit-to-design).  
6. click CREATE JOB.  
7. Move over to the ‘prepare’ tab.

## Setting up the laser

1. Turn the key on the laser to the right till there is a click.  
   1. If there isn’t a click, turn it back to the other side and then back again   
2. Wait until the laser cutter finishes its set up sequence (it will beep a few times).  
3. Grab the material being cut and set it inside the manifold in the upper left corner.  
4. Using the controls, position the laser reticle over the material.  
   1. If auto level is working press the up and down arrows at the same time to auto level the bed  
   2. If the auto level does not work look in the drawer labeled laser and look for a think metal spacer with a screw the same color as the laser lens (most likely black) place it on the lip of the laser head on the left side once in place press and hold the up button until the bed just pushes the spacer off the head remove the spacer before cutting  
5. Move the laser head with the arrows as close to the upper left corner as possible without any part of the design being off the cutting bed or material.  
6. On the computer, there should now be a crosshair for where the laser head is. Move this crosshair to the top left and bottom right of the design to make sure that it fits on the cutting bed and the amount of material you have.

## Setting the correct settings

1. Open the material detail in the bottom right corner.  
2. There are two different types of operations: cutting and engraving. Red should be cutting and black should be engraving for a basic design.  
3. Check [Material Settings](#material-settings) to find the speed and power you should cut along with suggestions for each material.

## Final steps

1. If the settings are good, save. when back on the prepare screen click “push to laser”.  
2. On the produce screen press play, in a moment the cutter will start.  
3. After it is done, give it a minute to air out, look for smoke. if there is none or like me you don’t care, pull out the part, put the remainder back in the cabinet correctly sorted, or the trash if there is not much left. If you are not sure whether there is enough to save or not ask a current laser tech.  
4. Turn the laser off if there are no more cuts.

# Advanced Settings

## Design Screen

#### Fit to design {#fit-to-design}

* When this button is clicked it will set the max borders as close to the edge as it can minus any margin that you tell it to add from the drop down button next to it.

#### More colors

* There are 16 different colors in the Trotec system.  
* Each color can be used as a separate operation that may be cutting or engraving which allows you to create very detailed/layered designs.  
* Each different operation can have different speed, power, and advanced settings and each will run in order of top to bottom in the materials details list.  
* To create a new operation go to the material details and click *add effect to material* then go to the top of that drop down and and put a name that can be anything ex 1, 2, 3 and choose engraving or cutting click ok and it should pop in at the top.  
* At the side of each operation is \+ sign and maybe a color you can click this to add a color to that operation. You can add multiple colors to the same operation.  
* Make sure if the design calls for it to save an operation for cutting.

## Prepare Screen

### Main Screen

#### Calculate job time

* This will give you a close estimate at how long the job will take. This calculation gets better as you run the laser, if you repeat a design, or a similar design. 

#### Zoom Selection

* When used it will zoom into a highlighted area.

#### Print and cut

* This setting will only work if the camera attachment is added which neither of the current lasers have.  
* Assuming that you do have a camera if activated this will allow you to use three points in your design which you have pre-printed on a piece of paper/cardboard/etc and align the points so that it cuts based on the paper printing and not a set dimension in case there was a size change at some point in the process.

#### Rotary

* This setting will swap the design plane to a thin long plane which represents the surface of a cylinder when the rotary tool is attached it will allow you to cut/engrave a cylindrical object.  
* Ask Collins for more details.

### Engraving

#### Engraving mode

* The setting controls how the laser will move to engrave the design it is normally set to standard but can also be set to unidirectional this will not affect the time unless you are doing multiple engrave layers.

#### Z-offset

* This will affect how much extra space the laser will put between the laser head and material; this is set to zero and there is no need to change that.

#### Passes {#passes}

* This will control how many times the set operation is repeated before it moves to the next one. This can be used to run the same setting multiple times which can help to engrave through denser material without the worry of causing a fire or warping the material.

#### High Quality

* This setting is only used for detailed designs and is naturally in the off position; this should be left this way in most cases.

#### Process gas

* This setting controls how the laser removes particulates during a job that should always be set to air assist.

#### Power correction

* This depending on the number set will let the laser adjust the power by a bit. The standard for this works well and there is no need to change it unless there is an operation you are not sure about.

#### Relief/Engrave covered layers

* These settings work together to allow you to place multiple operations in the same place if your design calls for that and this is not set it will only run based on the layers that can be seen from the top.

#### Dithering

* Dithering is used when you are cutting a grayscale image. Each different setting is a different way for the laser to decide what each color in the image represents. The standard setting is ordered and this is one of the best/most consistent settings.

#### Direction

* This setting controls the direction that the laser will move through the design, the standard being top left to bottom right the other setting goes from bottom left to top right and then two more to swap the left and right of each previous setting.

#### Extended overshoot

* This will let you tell the laser in mm how far past the edges of the design. This can help if you want to make sure that all the edges are engraved to the same level and don’t care about wasting a bit of material.

### Cutting

#### Passes

* This controls how many times the operation will be repeated This is useful for materials that don’t cut easily or are thicker see [Material Setting](#material-settings) for more detail.

#### Power Correction

* This will allow the laser to edit the power on the go which is helpful for new materials but can be left at standard for most cases.

#### Z-Offset

* This sets how much extra depth the laser will have for this operation; this is naturally set to 0 and there is no reason to change it for normal cuts.

#### Process Gas

* This is how the laser will remove particulates that should stay on air assist.

## **Misc**

#### Side check mark

* On the left side of the material details dropdown there are checkmarks near the edge of each operation you can click this to disable that operation meaning that if you run the file without changing that it will not do whatever operation is attached to that.  
* This can be used to rerun a design without doing a section which is already done Ex: you run an operation and it doesn’t cut through all the way so you disable the engrave setting and run it only with the cut setting activated.

# Material Settings {#material-settings}

## Wood

Most wood cut settings will use 100% power unless otherwise stated

* Wood cuts with a thickness of ⅛ or thinner should use a minimum of 1.2% for cutting this will work for most cases any slower can cause extra warping or scorch marks.  
* Wood cuts thicker than ¼ should use a max of .6% speed. An alternative is to set the speed to 1.0-1.2 and set the [passes](#passes) to 2+.  
* Wood cuts thicker than ½ should use a max of .2% or .1% speed based on the quality of wood slower with multiple passes will work better especially if you are trying not to scorch it.  
* Wood can be engraved with almost every engraving speed and power if you don’t know what will work you can check/make a burn board which has all settings from in 10th intervals.

## Plastics

Plastics should only be cut by an experienced laser tech and should be handled with care using proper PPE when necessary.

### Acrylic

Note that while acrylic does not have any major health effects it does have a horrendous smell and long term exposure can lead to persistent headaches.   
also it annoys colton but that is just a fun thing to do

* Acrylic is best cut with settings around 100% power and a speed of 50% on average.   
* Acrylic has different issues depending on the thickness.  
  * thinner plates around ⅛ if the speed is not high enough or if the detail requires too much time spent within a small area, there is a high chance of warping. The best way to deal with this is to cut at lower powers for ⅛ around 60%-80% is better than the standard along with splitting the design up so that the heat has some time to dissipate between operations.  
  * Plates thicker than ⅛ around ¼-½ when being cut will try to refuse the best course of action would be to cut at a medium speed around 30%-60% with many passes to slowly chip through. Also while there is a lower chance if there is too much cutting there is still a chance of warping especially around the edges of the design.

   

### Teflon 

* Teflon should not be cut if possible; it is an extreme skin and eye irritant and has a high chance of starting a fire.    
* If needed it should only be cut alone, under constant supervision by the main laser tech with proper PPE including a mask and gloves and suggested but not required being goggles. Along with having wet paper towels on hand to **smother** the fire as just getting it wet will not put it out. In the case of fire, end job immediately move the laser head away from the fire, open the hood slowly and wrap the inflamed area in an excess of paper towels once there is no visible fire and the Teflon is cold enough to be held immediately as quick as possible move to the cage and place out of the way, leave until the next day to fully cool dispose of afterwards. Leave the laser open and on until the end of the day and do not let unnecessary people enter. End cutting for the day if possible.  
* Teflon if it should be cut should be cut using a fast speed and a lower power as to not heat up the plastic too much. The settings are reactive and should be decided by the main laser tech based on the thickness of the panel.

## Paper

* Should be cut not engraved.  
* In most cases will leave the edge of the cut area yellowed.

## Foam

* Fast high power with many passes as to more or less drill through thicker foam.  
* Also this is for dense like play foam not styrofoam that has not been tested.

# How to set up a new computer

Before you follow the following steps please make sure you have gotten permission to make an account. ***do not share the superadmin password with anyone please and thank you*** 

1. Open [Trotec](https://www.troteclaser.com/en-us/laser-machines/laser-software) in a browser, find the [download link](https://liverubyfiles.blob.core.windows.net/installer/Trotec.Ruby.Installer.Offline.exe?sv=2023-01-03&si=site2025&sr=b&sig=HZsZEJXlHA460zEsiE%2FFZignQNFSCX9iqyN1p%2FxyvdA%3D) or use the one in this document.  
2. Enter the team email and password.  
3. Click on the left most tab at the top. It should say “Manage” when you hover over it.  
4. Then click on add laser put in S36-2527 if it says wrong or no configuration click on the arrow in the bottom right of your computer a panel should show up look or the ruby icon click on it move to import configuration look for files search then jobcontrol add that in then redo the serial code.   
5. If you do not need to set a permanent account for yourself you can stop here if you want a permanent one, continue.  
6. go over to the three lines in the top left corner and go to user management.  
7. Click add user and put in your email copy the code that they give you.  
8. Log out and put in your email and the temporary password, set up a password, save your account. You should now be able to access ruby on that device with that email and password. :)

# Maintenance

## Cleaning laser interior

* When it comes to cleaning the inside of the laser this can be done by anyone. When cleaning, turn on the laser, drop the bed to the lowest it will go and pull the front red plate down so you can access the entire inside.  
* Once opened, wash the sides of the laser with wet paper towels and be ready with many if it has not been cleaned in a while.  
* When cleaning the back wall of the laser there is a large box near the bottom which is the gas exchange there are two screws on a top plate which sits on top of the gas exchange remove those and clean the bottom side of the plate and the holes for the gas exchange you can push the particulate through of use a vacuum either works but not using a vacuum will cause extra cleaning later.  
* To clean the underside of the cutting bed push the four “buttons” in the corners of the bed after they are all in the up position (they should move with some slack) you can grab the bed and pull it out place off to the side clean the underbed with paper towels and vacuum any wood scraps at the bottom.  
* The bed can be cleaned with a hose but this only needs to be done on average once a year, use hot water and use a rough brush if needed.  
* This needs to be done at least once every 1-2 months.

## Cleaning laser lens

* Be aware that by reading this section you are still **not allowed to clean the laser lens** **until you** **have been trained by a person who has been certified.**  
* First open the laser and go to the head, make sure the laser is off.  
* Look for the red round section of the head right below a black section twist this to the left to untighten it once loose grab the black section and remove gently as this is the laser lens move the laser over to a surface (the top of the markforge printers are a good place).  
* Go into the laser drawer and grab some wipes and red lens cleaner. It should be in a mid-sized dropper bottle.  
* Put 1-2 drops of the cleaner onto the lens concave up and **soft as you can** swipe the cleaner off the lens **do not put too much pressure on the lens.**  
* Once cleaned put the lens back in its slot make sure the arrow is facing in the right direction, retighten the circle part then boom you are done.

## Cleaning the gas manifold

* To start, make sure that you have the time to do this as it will take some time and that you have the tools and a place to keep screws.  
* First move the laser from the wall so you can access the back.  
* Untighten the gas hose so that you can take it off the back of the laser.  
* Find the four screws which are on the same plate as the gas exhaust **make sure to don’t lose the screws.**  
* Go to the inside of the cut bed and look for the plate on top of the gas manifold unscrew and remove the plate.  
* Now you can remove the gas manifold and take it outside to the cage.  
  * Be aware that the manifold is a heavy weird shape and should be handled with care  
* Fill with water and slosh it around so that the water hits everywhere. Be generous with the water as on average you only need to clean the manifold every 2-3 years. Once washed, dispose of the liquid.  
* Undo all the steps done to detach it in reverse and push the laser back into place.
