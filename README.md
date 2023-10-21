# Papilio-Belt-Extruder

<img src="https://kevinakasam.com/wp-content/uploads/2023/10/comp.png"/>


#### I recommend visiting my website for slightly more aesthetic documentation :)

## A Belt-Extruder, what is that?

No metal teeth biting the filament, but soft rubber belts pushing the filament down to the nozzle. This is the concept of the Papilio: A Belt Extruder which uses regular rubber timing belts instead of metal extruder gears to feed the filament.

You may wonder why we need an extruder that uses belts instead of gears? Guess it’s fair to say, that we all know the woodpattern on flat surfaces or the small bites on the filament when the metal gears grab the filament. With the belts there are no metal teeth damaging the filament, but soft rubber belts pressing against the filament guiding it all the way through the extruder into the nozzle. As all my projects the Papilio is an 100% opensource project.

<img src="https://kevinakasam.com/wp-content/uploads/2023/02/b58f7de4-cdf1-484d-8bd1-506d2f21b68b-1024x1024.png" width="49%"/> <img src="https://kevinakasam.com/wp-content/uploads/2023/10/filament-1024x1024.png" width="49%"/>


## How does it work?

Powered by a Nema 14 the Papilio uses a gear reduction to drive two tiny 2GT looped timing belts. In order to keep everything as minimalistic and cheap as possible the Papilio uses very common hardware in combination with some printed parts. The Nema 14 doesn’t make it only super compact but also very light weight – only 140g!

The Papilio uses a Dual-Drive System so the filament gets pushed on both sides by the two timing belts. Using some special shaped pulleys the belts get curved and can perfectly warp around the filament. This ensures a maximum contact to the filament for a very strong grip and keep the filament centered.


## There are two of them?

Yes indeed! There are two versions of the extruder, the Papilio and Papilio Lite. After many many iterations the Papilio was the first working version of the belt extruder. The design reminded me on a butterfly so I named the extruder Papilio– latin for butterfly. But I didn’t stop! My goal was to develop a much more powerful design, so I went further into the rabbit hole. After many attempts and failures I ended up with the Papilio Lite: Less weight, more power. This doesn’t mean the original Papilio is outdated, he just got a brother.

<img src="https://kevinakasam.com/wp-content/uploads/2023/07/comp.png" width="49%"/> 

## What has changed?

### The Papilio Lite

The Papilio Lite got it’s name from the it’s internals – rather than using the BMG Drive Gear assembly, the Lite uses the Gears from the LGX Lite. With the two stage reduction of 44:10 and 37:17 ( or 44:8, 37:17 with a 8T motor) the Papilio Lite is not only much stronger but also lighter! With 130g the Lite saves you another 10g on the toolhead compared to the original Papilio!

The Papilio Lite also uses a Dual-Drive System to feed the filament on both sides by the two timing belts. The much more closed design of the Papilio Lite allows you to print flexibles, which wasn’t possible with the original design.

Like the original Papilio, the Papilio Lite uses the Sherpa Mini footprint, making it compatible with a wide range of toolheads – due to it’s increased depth it got some additional mounting points lining up with the LGX Lite. The boxed and compact design makes it even compatible with the Voron Steathburner!

<img src="https://kevinakasam.com/wp-content/uploads/2023/07/BeltBox_LGX-Lite_2023-Jul-16_08-59-46AM-000_CustomizedView15343119718.png" width="49%"/>

## Open source - this is our project!

As all my work the Papilio is also an Open Source project - all files are free to use! You get all the STLs and CAD files via my GitHub and the build logs below. I also added a User Mod Folder to the GitHub so you can contribute to the project with your awesome ideas and adaptions. I can't wait to see what you will come up with :) This extruder deserves it to be something special!

Also the CAD file is 100% parametric, so small adaptions like tolerances, different bearing or heatinserts sizes etc. are easy to do! I tried my best to describe the parameters, if you still have any questions feel free to ask. Ah and if you can't do CAD yourself, I'm sure I can help you out ;)

<img src="https://kevinakasam.com/wp-content/uploads/2023/10/Bild_2023-10-20_153853368-1024x551.png" width="49%"/>

### ❤️ Support my work

All my work is 100% Open-Source and free for everyone to use. But designing and developing all these things takes a lot of time and effort, so if you appreciate my work and would like to support it and also help cover the costs of gettings the mods perfect, you can use one of the following links. Thanks a lot 🤍

<a href="https://www.buymeacoffee.com/kevinakasam" target="_blank"><img src="https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png" alt="Buy Me A Coffee" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>
<a href="https://paypal.me/donationskevinakasam?" target="_blank"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/b/b5/PayPal.svg/1200px-PayPal.svg.png" alt="Donate via Paypal" style="height: 41px !important;width: 174px !important;box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;-webkit-box-shadow: 0px 3px 2px 0px rgba(190, 190, 190, 0.5) !important;" ></a>

## How can I try this out?

### Current state: Beta-Testing

After seven months of a closed Alpha Testing it's time for a public Beta!

While we did a lot of testing and improving during the Alpha, there's still room for improvements. If the Papilio caught your interest you can now build your very own Papilio extruder! As for all my Beta testings all communication will happen on my Discord - check the channel "#papilio-chat" for more information. All files are available on my GitHub - check the build instructions below. 
Click on the icon to join my [Discord Server](https://discord.gg/xqpKrxt9FC):

 
<a href="https://discord.gg/xqpKrxt9FC">
         <img alt="Join" src="https://github.com/kevinakasam/BeltDrivenEnder3/blob/main/_ignore/Pictures/Discord-Logo%2BWordmark-Color.png"
         width=250" >
      </a>


### Alpha Testing: Completed

You are awesome! After half a year of Alpha testing we can now start the public Beta. Thank you very very much for all your help, suggestions, time and willing to help.  Shoutout to these awesome people:

You | are | some | really | awesome | People!!
:-------------------------: | :-------------------------: | :-------------------------: | :-------------------------: | :-------------------------: | :-------------------------:
 |   |   |   |   |      
1957Axel | 10Boltoa | aid3nn | André | Andy | barnus84
bigbosshogg412 | Bomble_doodle | Butter202 | Chilly | chestwood96 | [CR3D](https://www.cr3d.de/)
Ciccius | diabolicaldan | Farva | Fruitz | hawk16zz | interitus
JamesH | Keh | Kingn00dles | Lemcott | Luigivaba | macuser_1984
memy | Mr ed | Naraki | [oldcrazyeye/CrazyLlamaCustoms](https://github.com/oldcrazyeye) | oliof | PCR
Phanzer | PigeonGiraffe | pnewb | q66 | qwib | SpitefulOwl
Stu | tcbp | Tkaus | verm | Wight555 | [zruncho](https://github.com/zruncho3d)




## Build Instructions

I'm glad that you want to give the Papilio a try. Just click on the Papilio you want to build:

<a href="https://kevinakasam.com/papilio-build-instructions/">
         <img alt="Click" src="https://kevinakasam.com/wp-content/uploads/2023/03/Papilio1-1024x1024.png"
         width=49%" >
      </a>

<a href="https://kevinakasam.com/papilio-lite-build-instructions/">
         <img alt="Click" src="https://kevinakasam.com/wp-content/uploads/2023/07/BeltBox_LGX-Lite_2023-Jul-16_02-21-54PM-000_CustomizedView4341908316-1024x1024.png"
         width=49%" >
      </a>


