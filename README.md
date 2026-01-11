# BloodBorne-SFX-Bible-from-Xenobyte-and-Gazu---all-FXR-files-catalogued
All the BloodBorne .FXR SFX files catalogued as to what they do in terms of actual graphics. Useful for modding like for instance, I combined an explosion one and a rock debris one this week for making a dynamite SFX using the ONESHOTSFX command when it detected a flag in EVEMD. Great for making new SFX and sprucing up any mod or project.

Just a reminder we also did 75%, or so of the legwork on the FXR file structure and making a rudimentary parser. If someone wants to finish it the info is here: 
https://github.com/xenobyteOG/bbfxrtoxml

I addition the last time this was updated was when Shad didn't do all the SFX with Intel so if there's updates or inaccuracies post them in issues and I'll update. Thanks! 

Please also remember that this is Intel-based, mainly especially the 12th generation that can't run the SFX without crashing. It's why we started this after all, so if it says CRASHES GAME it may work on AMD or work with later Intel or even work now with updated Shad. I'm always on the Shad or Test Data discord DM me and I'm happy to talk your ear off about FXR lol. Now to the main event:

------

Well, folks, I think it's been long enough to pass this along to someone else. Gazu and I worked for hours and hours to create this repository of every FXR file in BloodBorne and what it does on screen. You will see our colorful and insane language to describe best as we could what it looked like in action. Also, you will be able to see the numbering system and method they used in BloodBorne and prob other FromSoft games. Basically you'd get a main FXR file and the n/a ones beneath it are likely different variations of that SFX that rely on the parent FXR file to work. That's why when they were tested stand alone they did nothing or it was a ton of dupes in a row. Also, if you notice, the general numbering system for all maps is similar or the same. Lower numbers below 000100000.FXR usually mean items, actions, and other common stuff centered around the player and bosses/enemies. Higher and higher usually means more map-based SFX and/or the environmental stuff. BUT SEE THE NOTE BELOW ABOUT THINGS NOT ALWAYS HOLDING TO THE PATTERN!

Anyway, this bible is how we were able to make the SFXR mod so good and helpful to hundreds of thousands of you. We hope to pass it along now so that someone else can pick the torch and make something great with the game we all love!

THE SFXR BloodBorne FXR BIBLE - Xenobyte and Gazu  

Here's how the files work. Common SFX file is the first one listed. Those graphics are available everywhere in game. The individual map files FXR are only accessible on those maps, BUT you can easily replace one FXR from one map with an FXR from another as long as you keep the filenames exactly the same when you replace it. I suggest renaming the original one you replace like 0000023445.FXR.og so you have it just in case but you get the idea. Just BE CAREFUL what you replace. Even if it says N/A or not used or crashes game it may well be used somehow. That's how we had the infamous "fire feet" bug the plagued the mod for two months before we figured out one of those N/A were actually dust from starting running. We replaced it with a tiny flame and the rest is history. So just be careful. 

Also, if you are looking to change an SFX in the game, remember, it may be literally three places - COMMON file, DLC file, and PATCH file. A few times we had to remove or change all 3, although if memory serves there isn't much in PATCH and DLC supercedes the COMMON file, but don't always rely on that. BLOODBORNE IS WEIRD and has a ton of idosyncracies when it comes to stuff like this. You can literally see they built it on Dark Souls 1 and half the stuff doesn't even do anything because it is ripped straight from Dark Souls 1 inside the actual game param files. TLDR: Don't rely on a pattern or system to hold true always. It won't.

COMMON GFX FILE 

f000020255 edibles  
f000020257 sedatives  
f000000500 Fire Paper  
  
f000020275 Iosefka's  
  
f000900201 item glow  
f190000000 blood on attack  
f000610250 TORCH enemies  
f000021051 TORCH player  
f000000210 Player light aura  
  
f000021052 Player Lantern  
f000063111 living creatures (messengers probabaly)  
f000020359 white bang that fades  
f000020303 little head  
f000020297 cloud with sound  
f000020276 small fire explosion  
f000020275 no light (crashes)  
f000202002 roar with slashes  
f000700001 spotlight directional  
  
f000006000 to 6002 - various Rifle  
f000000042 big aura explotion  
f000000045 small red square with black x on self (lol)  
f000000053 white ring of radagon  
f000000054 white square with black bars  
f000000060 yellow blast  
f000000089 small white blast
f000000092 big yellow flaming light  
f000000095 crashy flames 
f000000110 prevalent yellowhite flamelight  
f000000117 prevalent green light  
f000000118 red light and then melting ball of goo  
f000000119 small white explotion on self  
f000000121 warp sfx  
f000000122 prevalent orange light  
f000000123 orange light  
f000000124 prevalent redorange light  
f000000140  
f000000170  
f000000171 ***CRASHES GAME***  
f000000175  red blotch that expands outward likely the blood bullet fx  
f000000178 doll level up sfx after you hit confirm  
f000000180 doll level up SFX in her hands before confirm  
f000000200-f000000263 fire shades???  
f000000300 circular air effect going in  
f000000301 n/a  
f000000302 n/a  
f000000303 circular air ripple effect going out  
f000000304 black circular dripping muds  
f000000305 circular air ripple effect, less pronounced  
f000000310 short small blue flash  
f000000311 short small red flash  
f000000320 yellow flash and soul suck sound  
f000000340 circular air ripple, .5 seconds later gunshot sound, explosion  
f000000341 white flash then air ripple and red flash fadeout  
f000000342 slightly delayed white flash and then air ripple  
f000000350 yellow bright medium size flash and then fadeout with soul suck sound  
f000000351 yellow bright medium size flash and then eerie ghost soul suck sound  
f000000400 n/a  
f000000401 **CRASHES GAME***  
f000000456 n/a  
f000000459 n/a  
f000000500 fire paper  
f000000501 empty phantasm shell sound cue and texture cue  
f000000502 lightning paper sound cue and texture cue  
f000000520 n/a  
f000000550 medium orange glow that stays on for 5 seconds  
f000000552 three small white round flashes 1 seconds apart, like lightning  
f000000556 delayed blood fountain, shoots into air toward player after 1 second  
f000000559 blood gooey gush on hit, 1 second later huge geyser of goo blood in air  
f000000800 n/a  
f000000806 thunder sound on hit  
f000000810 n/a  
f000000811 n/a  
f000000820 slow gooey blood splash  
f000000821 super gooey gushy slow blood explosion  
f000000830 gooey gushy slow blood explosion  
f000000835 n/a  
f000000845 n/a  
f000000850 n/a  
f000000851 n/a  
f000000854 n/a  
f000000855 n/a  
f000000865 n/a  
f000000866 n/a  
f000000868 ***CRASHES GAME***  
f000000869 white mist sucked in to central point
f000000870 n/a  
f000000880 small lightning on hit  
f000000900 steam then black leaves, 10 seconds  
f000000910 n/a  
f000000911 n/a  
f000000912 n/a  
f000000913 n/a  
f000000914 n/a  
f000000915 bright yellow flash, 1 second duration, centered on middle of body  
f000000916 bright yellow flash, 1 second duration, centered on the floor  
f000000917 brighter yellow flash, 1 second duration, centered on the floor  
f000000918 bright yellow flash, 1 second duration, centered on the floor  
f000000919 small yellow light centered on body fade in/fade out, 1 second duration  
f000000920 short flame aura, 3 seconds  
f000000935 red fire-like aura (hp regen)  
f000000940 green aura (stamina regen)  
f000000945 steaming aura  
f000000950 golden aura  
f000000960 tiny purple light like a firely fade in and out  
f000000961 miniscule blue spec of light that flies to target but ***CRASHES GAME****  
f000000962 bright yellow light fade in and out centered on ground  
f000002001 n/a  
f000002005 n/a  
f000002020 ***CRASHES GAME***  
f000002022 ***CRASHES GAME***  
f000002023 ***CRASHES GAME***  
f000002024 ***CRASHES GAME***  
f000002031 ***CRASHES GAME***  
f000002032 ***CRASHES GAME***  
f000002033 ***CRASHES GAME***  
f000002101 ***CRASHES GAME***  
**********  
f000002117 MASTER LIGHT SWITCH - this one overwrites many other lights and if you dont have it they wont work  
**********  
f000002125 n/a  
f000006000  
f000006100  
f000006105  
f000006120  
f000006200 black circle sphere but ***CRASHES GAME***  
f000006202 very quick small bright flash  
f000006203 very quick medium bright flash  
f000006205 orange sphere with lines streaming off but ***CRASHES GAME***  
f000006210 orange sphere with lines streaming off but ***CRASHES GAME***  
f000006215 big yellow explosion - maybe for molotov
f000006300 ***CRASHES GAME***  
f000006302 short bright flash centered on body  
f000006303 short bright flash centered on body  
f000006305 red fire streaks ***CRASHES GAME***  
f000006310 small flash wherever the weapon hits  
f000006311 yellow light fade in and out, not a flash  
f000006312 smaller yellow light fade in and out, not a flash  
f000006313 tiny yellow light fade in and out, not a flash  
f000006315 small orange light fade in and out where weapon connects, flash  
f000006316 orange light explosion fade in and out where weapon connects, flash  
f000006317 small orange light flash on hit  
f000006318 tiny orange explosion light flash on hit  
f000006400 n/a  
f000006402 flamesprayer  
f000006403 brighter flickery light centered on body, 5 second duration  
f000006405 n/a  
f000006410 n/a  
f000006415 n/a  
f000006500 n/a  
f000006502 rosmarinus spray
f000006503 sucking sound and then distant train horn blows twice  
f000006505 n/a  
f000006510 n/a  
f000006515 n/a  
f000007002 red/black blood gushing all over and reducing till gone, 5 sec duration  
f000007007 red/black blood gushing all over and reducing till gone, 5 sec duration  
f000007100 red/black blood gushing all over and reducing till gone, 5 sec duration  
f000007101 white spot on hit, circular, but stretched out horizontally  
f000007102 white circular flash on hit  
f000007103 small yellow glow , duration 1 sec, fade out  
f000007104 n/a  
f000007105 small short yellow flash  
f000007106 lightning flash, centered on ground  
f000007107 small red burst, stretched out horizontally  
f000007108 n/a  
f000007109 small yellow flash  
f000007110 yellow flash  
f000007111 small red flash and a little blood spurts out to the left  
f000007112 small yellow flash  
f000007113 ***CRASHES GAME***  
f000007200 n/a  
f000007205 n/a  
f000007210 lightning, 5 small sparks, 5 seconds duration  
f000007211 lightning, small spark  
f000007500 green flash, 1 second duration, centered on target floor  
f000007501 green flash, 1 second duration, centered on player floor  
f000007600 n/a  
f000007656 wavey air effect, medium distance forward of activation point  
f000007657 wavey air effect slightly up and to the left of activation point  
f000007659 wavey air effect slight slight left of activation point  
f000002000  
f000003000  
f000020305 n/a  
f000020359 yellow expanding little golden bubble, with small sound  
f000021051 yellow flash, 5 seconds  
f000021052 yellow flash, 5 seconds  
f000020200 Molotov explosion  
f000020208 numbing mist break on hit  
f000063111 tons of little messengers fly out on hit in a sphere  
f000100000 bright white light centered on ground, 5 second fade out  
f000100010 bright white light centered on ground, 5 second fade out  
f000100020 bright white light centered on ground, 5 second fade out  
f000100030 bright white light centered on ground, 5 second fade out  
f000100040 bright white light centered on ground, 5 second fade out  
f000100100 yellow light that fades in and out with little purple dot  
f000100110 yellow light that fades in and out with little purple dot  
f000100120 yellow light that fades in and out with little purple dot  
f000100130 yellow light that fades in and out with little purple dot  
f000100140 yellow light that fades in and out with little purple dot  
f000100200 yellow light that fades in and out with little purple dot - warp lantern  
f000700003 bright blue light  
f000820000 person size oblong wavy air, fade out 3 seconds  
f000822000 wavy air effect for fog wall with green light centered on middle of wall  
f000824100 **** Wavy air effect for most fog walls   
f000824103 wavy air effect for fog wall with green light included centered on floor  
f000828000 big white light that cuts across screen  
f000900100 small yellow flickery light
f000900101 actual candle flame with flicker  
f000900102 green light with flame slow flicker  
f000900103 actual candle flame with flicker and greenish mist  
f000900115 small yellow light  
f000900116 small yellow light  
f000900120 small green double flickery light  
f000900130 small item glow  
f000900131 bright item glow fast flash  
f000900200 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900202 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900203 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900204 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900205 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900206 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900207 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900208 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900209 ** PROB SOMETHING WITH ACTUAL ITEM ICON-CRASHES GAME WITH OBJ ERROR***  
f000900210 spotlight on head height  
f000900211 spotlight on head height  
f000900212 spotlight on head height  
f000900213 spotlight on head height  
f000900214 spotlight on head height  
f000900215 spotlight on head height  
f000900216 spotlight on head height  
f000900217 spotlight on head height  
f000900218 spotlight on head height  
f000900219 spotlight on head height  
f000900250 n/a  
f000900251 n/a 
f000900252 n/a 
f000900257 n/a  
f000900260 super bright yellow flickery light    
f000900261 n/a  
f000900270 very bright pulsing light half body height  
f000922140 n/a  
f000923231 n/a  
f000924095 super bright yellow light, slight flicker  
f000929115 n/a  
f000929205 *** CRASHES GAME ***  
f000929206 *** CRASHES GAME ***  
f000929207 n/a  
f000929208 n/a  
f001000000 n/a  
f001000001 n/a  
f001000002 n/a  
f001000003 n/a  
f001000004 n/a  
f001000005 n/a  
f001000006 n/a  
f001000009 n/a  
f001000010 n/a  
f001000011 n/a  
f001000012 n/a  
f001000019 n/a  
f001000020 n/a  
f001000021 n/a  
f001000022 n/a  
f001000027 n/a  
f001000221 n/a  
f001000321 n/a  
f001000501 throws red debris up from the ground then falls back down  
f001000502 throws red debris up from the ground then falls back down  
f001000503 throws red debris up from the ground then falls back down  
f001000521 n/a  
f001000531 throws white debris up from the ground then falls back down  
f001000532 throws red debris up from the ground then falls back down  
f001000600 n/a  
f001000601 throws big red debris up from the ground then falls back down  
f001000602 throws big red debris up from the ground then falls back down  
f001000603 throws bigger red debris up from ground then falls back down  
f001000621 n/a  
f001000631 throws bigger white debris up from ground and then falls back down  
f001000632 throws big red debris up from the ground then falls back down  
f001100000 white light then fades out, 1 second duration  
f001100100 n/a  
f001000400 white light to bright white light to yellow light then fade out  
f001101000 white light, 5 second duration  
f001101001 quick white flash on hit, small explosion  
f001101100 n/a  
f001101200 1 second delay they white flash centered on ground with sound  
f001101400 white to yellow to white light, fade out, 5 seconds duration  
f001101401 n/a  
f001101405 red messengers SFX  
f001103000 white light with healing injection sound  
f001103100 n/a  
f001103300 yellow to white light, fade out, **blood echoes retrieve SFX  
f001103400 light with 2 pulses, yellow then fade then white then fade  
f001103401 n/a  
f001105000 white light, face out, 5 seconds  
f001111001 1 second delay and then bluish-purple light centered on hit, fade out  
f001111002 1 second delay and then bluish-white light centered on hit, fade out  
f001111003 1 second delay and then bluish-white light centered on hit, fade out  
f001111101 1 second delay and then dimmer bluish light centered on hit, fade out  
f001111102 1 second delay and then bluish-white light centered on hit, fade out  
f001111103 1 second delay and then bluish-white light centered on hit, fade out  
f001200001 n/a  
f001200003 n/a  
f001200012 n/a  
f001200101 n/a  
f001200103 n/a  
f001200112 n/a  
f001200132 n/a  
f001500001 n/a  
f001500101 n/a  
f100015050 n/a  
f103015050 weird low-res blood spurt, as if it was close to the players eyes  
f103015056 fire weapon type sfx but ***CRASHES GAME***  
f103015057 ***CRASHES GAME***  
f103015059 ***CRASHES GAME***  
f103015060 weird blood spurt, half normal, half super low res as if it close to players eyes  
f103015063 ***CRASHES GAME***  
f103020040 white circle of mist explodes outward in waves at activation point  
f103021040 white circle of mist explodes outward in waves at activation point  
f103022040 white circle of mist explodes outward in waves at activation point  
f103023040 white circle of mist explodes outward in waves at activation point  
f103024040 white circle of mist explodes outward in waves at activation point  
f103025040 white circle of mist explodes outward in waves at activation point  
f103026040 white circle of mist explodes outward in waves at activation point  
f103027040 white circle of mist explodes outward in waves at activation point  
f103028040 white circle of mist explodes outward in waves at activation point  
f190000027 n/a  
f190000174 n/a  
f190000200 n/a  
f190000300 n/a  
f190001000 n/a  
f190001200 n/a  
f190001300 n/a  
f190002000 n/a  
f190002200 n/a  
f190002300 n/a  
f190010000 n/a  
f190013000 n/a  
f190020000 n/a  
f190020060 n/a  
f190040000 n/a  
f190060000 n/a  
f190740000 n/a  
f190890400 n/a  
f000020256 healing blood vial sfx  
f000020290  
f000020291  
f000020292  
f000020294  
f000020295  
f000020296  
f000020297  
f000200001  
f000202008  
f000203008  
f000252010  
f190890400 exploding blood  
f190890000 tiny normal blood  
f190013000 small explosion  
f190012000 tiny explosion  
f190011000 even tinier explosion  
f190010000 even tinier explosion 2  
f190002300 weird black and grey rectangles  
f190002200 transparent black and grey rectangles  
f190001300 transparent black squares  
f190001200 transparent black squares  
f190000300 transparent black squares  
f190000075 grey exploding blood (from goo monsters)  
f190000074 grey regular blood  
f190000060 red blood stream that shoots far  
f190000031 weapon hit on wall sparks type thing  
f190000002 rectangle explodey blood  
f190000001 pieces of paper flying out like when you destroy books  
f190000000 BLOOD  
f106008027 dark red blood splatter on the floor  
f106008020 dark red blood splatter on the floor 2  
  
light type  
  
f000200000 white light  
f000100200 lantern light glowing  
f000924095 torch with light source  
f000900117 bright pulsing light  
f000900100 nice low torch light (greenish)  
f000900110 super bright light  
f000900105 super bright light  
f000828000 brightest light ever  
f000824103 bluish smoke that eventually fades, good for a new spell  
f000822000 pulsing high light with waves  
f000820000 n/a  
f000700003 blue fast pulsing light  
f000650094 n/a  
f000650089 n/a  
f000650021 n/a  
f000650017 n/a  
f000627390 n/a  
f000625191 n/a  
f000620512 n/a  
f000620505 n/a  
f000900219 n/a  
f000900250 n/a  
f000922140 n/a  
f000923231 n/a  
f000924095 yellow light (long decay)  
f000929115 n/a  
f000929205 n/a  
f001000000 n/a  
f001000100 n/a  
f001000200 n/a  
  
m24  
f000924043 blue rays from right  
f000924047 frontal foggy godrays  
f000924048 difuse redish mist  
f000924080 yellow flame to the right (light)  
f000924081 flame close to the right  
f000924082 greenish central light  
f000924083 yellow flame to the right (light)  
f000924084 green light to the right (?)  
f000924086 yellowish difuse light  
f000924087 streetlamp  
f000924089 fuego  
f000924092 central yellow light  
f000924093 small candle flame  
f000924094 small candle flame  
f000924096 yellow centered light
f000924097 big centered yellow light  
f000924098 bigger centered yellow light  
f000924099 giantic centered yellow light laming noise  
f000924101 weird bad flame  
f000924103 giant inferno flame 
f000924110 giant spotlight from above  
f000924111 centered spotlight  
f000924112 redish flame 
f000929200 giant abductor light *trigger  
f000929203 giant smoke bomb *trigger  
f000929225 explosive bomb *trigger  
f000929226 giant activating explotion *trigger  
  
m24_02  
f000626000 lantern with led  
f000625721 mega white flashbang  
f000625715 white lights activation persevere  
f000625706 rain of rocks  
f000625705 waveforce with rocks  
f000625700 crashes  
  
Patch DCX  
f000000110 white light with negative void  
f000000117 greenblue light with negative void and grey gooblood  
f000000118 same but red  
f000000120 greenblue light with small void on tip  
f000000121 same but big void  
f000000122 red light with small void on tip  
f000000124 same but orange  
f000000127 same but violet  
f000000128 same but less quick  
f000000129 same but slower  
f000000136 violet light with void  
f000000137 violet light with big void that closes  
f000000138 same  
f000000139 same with grey gooblood  
f000000170 healing effect  
f000000175 same but dimmer  
f000000179 short yellow spot light  
f000000186 nothing ?  
f000000187 short white flash  
f000000189 same  
f000000190 same  
f000000211 greenblue spotlight  
f000000212 red spotlight  
f000000213 purple spotlight  
f000000214 violet spotlight  
f000000215 same  
f000000230 mist suck  
f000000231 mist out  
f000000300 circular mist  
f000000320 yellow activation  
f000000340 white bang with circular mist  
f000000341 white bang with red decay  
f000000342 same as 340  
f000000456 same as 341  
f000000459 white bang and mist  
f000000520 nothing  
f000000556 blood spatter with another later  
f000000559 same  
f000000602 nothing  
f000000604 nothing  
f000000605 nothing  
f000000606 nothing  
f000000607 red halo  
f000000608 nothing  
f000000614 nothing  
f000000615 nothing  
f000000616 nothing  
f000000618 nothing  
f000000624 nothing  
f000000625 nothing  
f000000806 nothing  
f000000810 nothing   
f000000820 wide blood burst  
f000000821 huge blood burst  
f000000830 blood burst  
f000000855 nothing  
f000000868 hard crash  
f000000915 big yellow bang  
f000000935 nothing  
f000000940 nothing  
f000003026 nothing  
f000003031 nothing  
f000003126 nothing  
f000003131 nothing  
f000003301 flying rocks  
f000003302 circle air suck  
f000003303 flying rocks  
f000003326 nothing  
f000003331 rocks flying with bang  
f000003332 rocks flying  
f000003426 nothing  
f000003431 flying lil rocks  
f000003432 flying lil rocks  
f000003526 nothing  
f000003531 nothing  
f000003626 nothing  
f000003631 nothing  
f000006001 fast bang  
f000006010 small bang  
f000006011 small bang  
f000006012 small bang  
f000006013 small bang  
f000006110 small bang  
f000006111 small bang  
f000006112 small bang  
f000006113 small bang  
f000006115 big bang  
f000006116 small bang  
f000006117 small bang  
f000006118 small bang  
f000006130 small bang  
f000006131 small bang  
f000006132 small bang  
f000006133 small bang  
f000006135 bang with faded shadow  
f000006136 same  
f000006137 same  
f000006138 bang  
f000006202 gunexplotion  
f000006203 biggunexplotion  
f000006210 long gunxplotion  
f000006215 same  
f000006310 gun bang with bullets  
f000006311 same  
f000006312 same  
f000006313 same  
f000006314 same  
f000006315 same  
f000006316 same  
f000006317 same  
f000006318 same  
f000006400 nothing  
f000006402 big yellow flame  
f000006403 biggest yellow flame  
f000006405 nothing  
f000006500  
f000006502 sound of wind ?  
f000006503  
f000006505   
f000007101 white flash  
f000007102 white flash  
f000007104 black flash  
f000007105 white flash  
f000007109 3 small yellow flash  
f000007113 yellow flash  
f000007500 white flash short  
f000008021 yellow light  
f000008023 aquagreen flames  
f000008024 veeeery yellow light  
f000008025 white light  
f000008026 green light  
f000010618 nothing  
f000010718 nothing  
f000010810 nothing  
f000010830 blood splash  
f000010910 nothing  
f000010930 blood splash  
f000020004 dagger  
f000020005 dagger  
f000020105 hard crash  
f000020200 yellow flash  
f000020204 dagger tip  
f000020205 dagger tip  
f000020206 yellow flash + rocks  
f000020209 nothing  
f000020230 yellow spotlight  
f000020231 green spotlight  
f000020232 purple spotlight  
f000020233 bright star  
f000020250 nothing  
f000020303 small rock  
f000020305 falling dagger  
f000020359 yellow flashbang  
f000200001 small blackvoid to white light  
f000200005 bell with white light (sound)  
f000200006 bone with yellow light (sound)  
f000202002 wind guts  
f000202005 big white light with smaller ones  
f000202010 white light with tentacles  
f000203001 white flash  
f000203005 white magic tip with yellow light  
f000203008 red bang with sound  
f000252020 quick yellow bang  
f000252022 small yellow bang  
f000610090 nothing  
f000610100 big flame light  
f000610101 fast flame light (12sec)  
f000610102 yellow light 1sec  
f000610110 yellow light 3sec  
f000610111 yellow light 2sec  
f000610112 yellow light 1sec  
f000610115 big flame light  
f000610116 yellow halo with giant expanding light  
f000610117 faint yellow flash  
f000610121 yellow flame 4sec  
f000610122 nothing  
f000610150 yellow light (lamp?)  
f000610300 dirt cloud + rocks  
f000610301 big dirt cloud + rocks  
f000610404 nothing  
f000610502 white light with waves
f000610516 yellow light 1sec  
f000610520 led circle tip with very white light  
f000610551 black leak with very white light  
f000610560 nothing  
f000610610 blue tip with white light HARD CRASH  
f000610611 blue halo with very whit light  - brain sucker projectile  
f000610612 blue halo with white bang (sound)  
f000610615 white bang - brain sucker projectile  
f000610616 moving white light  
f000610617 white bang  
f000610621 white bang
f000610622 big white bang  
f000610625 big white bang  
f000610626 nothing  
f000610902 nothing  
f000611101 black circle with white light  
f000611102 small black circle with white flash  
f000611112 nothing  
f000611113 nothing  
f000611125 nothing  
f000611201 nothing  
f000611202 nothing  
f000611402 nothing  
f000611500 nothing  
f000611501 nothing  
f000611502 nothing  
f000611601 yellow intermittent light 3sec  
f000611602 crushing Sound  
f000611603 nothing  
f000612115 white blood splash  
f000612200 suck air and air splash  
f000612202 nothing  
f000612203 suck air and air splash  
f000612204 continuous wind circle  
f000612205 nothing  
f000612300 nothing  
f000612301 nothing  
f000612305 nothing  
f000612306 transparent air movement  
f000612500 nothing  
f000612501 nothing  
f000612600 nothing  
f000612601 nothing  
f000612710 air camera focus  
f000612720 nothing  
f000612721 nothing  
f000612725 nothing  
f000612726 nothing  
f000613005 nothing  
f000613010 big white bang  
f000613011 lightball center to right  
f000614000 nothing  
f000614001 nothing  
f000614004 nothing  
f000614005 nothing  
f000620203 big white flash  
f000620213 big white flash with motion  
f000620252 nothing  
f000620401 nothing  
f000620511 giant red hue  
f000620806 white flash with giant wind ball  
f000620900 motion blur pulse  
f000620901 strong motion blur pulse  
f000620910 rain of rocks  
f000620911 fast yellow flash  
f000620915 rocks burst  
f000620921 dust cloud with fast wind  
f000620955 nothing  
f000620961 gooblood burst prevalent  
f000620965 nothing  
f000620990 green giant flash with big gooblood burst  
f000621002 black circle with sound  
f000621006 violet circle with giant white bang and sound  
f000621012 blue closing circle with green flash  
f000621023 after 1 sec, black mist returning  
f000621100 blue circle with big white bang  
f000621101 blue closing circle with short green bang  
f000621202 nothing  
f000621208 white circles with big red hue  
f000621215 falling black mist  
f000621218 falling black mist  
f000621225 flame 3 sec  
f000621226 flame 12 sec  
f000621227 yellow short bang  
f000621228 big yellow bang  
f000621305 big blood burst  
f000621306 biggest blood burst  
f000621307 giant blood burst  
f000621308 ultra mega blood burst  
f000621513 nothing  
f000621590 nothign  
f000621605 fire bang  
f000621610 giant fire bang with wind  
f000621611 same  
f000621612 yellow light 6sec  
f000621621 yellow activation light  
f000621700 nothing  
f000621701 short air move  
f000621800 yellow blink light 4sec  
f000621801 nothing  
f000621802 nothing  
f000621804 electricity  
f000621805 thunderbolt + flashbang  
f000621806 blue electric hue  
f000621810 activate gooblood burst  
f000621811 nothing  
f000621814 activate gooblood burst  
f000623204 redish hue with white activation  
f000623206 white oval bang with rocks  
f000623207 yellow bang with rocks and wind  
f000623220 yellow light 12sec  
f000623222 yellow flash  
f000623223 yellow light 14sec  
f000623225 yellow flash  
f000623226 whitereddish light 12sec  
f000623229 whitenuke with rocks  
f000623232 white flash  
f000623245 white light 12sec  
f000623251 nothing  
f000623301 nothing  
f000624001 some rocks  
f000624003 some rocks with sound 
f000624005 some rocks x2  
f000624007 some rocks x2  
f000624011 giant rocks  
f000625000 white light 2sec  
f000625002 white flash  
f000625005 white light 2sec  
f000625006 faint white flash  
f000625007 white flashlight  
f000625008 white flash  
f000625010 big whitegreenish light  
f000625011 giant white flash  
f000625012 yellow activation  
f000625015 white activation with blue aura  
f000625020 blue circle magic with prevailing blue tip (CRASHES)  
f000625105 after 1 sec, big greenbang + white flash 3 sec  
f000625107 green bang + 4 sec white light and prevailing one on weapon  
f000625108 nothing  
f000625110 nothing  
f000625120 big translucent circle activation with sound and wind circle  
f000625121 small mist activation  
f000625130 giant blood splash  
f000625131 gooblood splash  
f000625132 big gooblood splash  
f000625190 giant greenflash and gooblood  
f000625191 same  
f000625201 small air moving mist  
f000625206 big air moving mist  
f000625300 various white flash  
f000625301 circling rock with big yellow light  
f000625302 yellow bang with rocks  
f000625304 nothing  
f000625305 nothing  
f000625306 green light 3sec  
f000625307 biig green light 3sec  
f000625310 big air circle opens, closes after 2sec  
f000625320 small rock shower  
f000625321 fallin lil rocks  
f000625600 yellow circle light-like (no source light)  
f000625601 giant flame-like light  
f000625705 small rocks  
f000625706 two burst of rocks  
f000625710 white light 2sec  
f000625715 same  
f000625716 white light to black void  
f000625720 giant greenish blind light
f000625721 giant blueish blind light  
f000626200 short yellow flash  
f000626210 same  
f000626217 same with cannon sound  
f000626220 yellow intermittent light 3sec  
f000626221 same with sound  
f000626223 nothing  
f000627035 nothing  
f000627100 rocks to the front  
f000627102 yellow bangs + rocks (machinegun?)  
f000627105 activation + rocks  
f000627106 same  
f000627112 yellow flash  
f000627120 yellow increasing until rocks explosion  
f000627130 yellow flash  
f000627181 circle air activation + other one in top  
f000627200 rocks  
f000627205 same  
f000627206 yellow bang + airwave  
f000627208 more rocks  
f000627209 lil rocks  
f000627210 big rocks  
f000627220 big air focus  
f000627300 orange pulsing light  
f000627305 rocks shower x3  
f000627306 big rocks  
f000627307 yellow flash + rock shower x3  
f000627308 air flow + big rocks  
f000627390 green giant flashbang  
f000627402 nothing  
f000627407 nothing  
f000627410 nothing  
f000627411 nothing  
f000627415 nothing  
f000628104 nothing  
f000630000 yellow flamey light too bright  
f000630001 yellower flamey light 12sec  
f000630002 yellow flash  
f000630022 white flash  
f000630601 yellow light activation + blood stream  
f000630602 blood spater  
f000630606 5 sec blood stream to the back  
f000630607 yellow light activation  
f000630611 big yellow explotion + big blood explotion  
f000630612 big blood spater  
f000630615 blood spater  
f000630616 crash  
f000630621 crash  
f000630630 translucent wave  
f000630625 white flash + windgust + permanent debris back  
f000630640 blood spatter with 3 sec yellow light  
f000630645 big yellow light  
f000630646 red light with blood to the right  
f000630651 5 sec yellow light  
f000630652 normal blood spater  
f000630656 blood faucet  
f000630657 yellow activation light  
f000630665 normal blood spatter  
f000630666 redish light  
f000631215 Wind !  
f000631300 big shoot  
f000631305 debris shower  
f000631309 waveforce and debris  
f000631310 translucent void  
f000631311 mega blood spatter  
f000631315 giant blood spatter  
f000631316 giant blood spatter  
f000631317 blood spater  
f000631318 red faded circle  
f000631319 red circle expanding  
f000650002 blood wide spatter  
f000650008 warplike void  
f000650012 two fast shots  
f000650015 flying rocks  
f000650016 flying rocks  
f000728102 giant prevailing flame  
f000929032 small light like itemglow  
f000929131 yellow light prevails  
f000929132 greenish light prevails  
f000929133 redish light prevails  
f000929134 purple whitelighted torch  
f000929135 purple candle fades  
f000929136 greenflash stays on 2 secs  
f000929200 halo with flashbang  
f000929205 crashes  
f000929209 dirt cloud and debris  
f000929210 dirt cloud and debris  
f000929218 greenish centered lght  
f000929220 blackmist violet rays  
f000929226 explotion  
f000929227 crashes  
f000929236 electricity  
f000929260 explosion  
f000929261 mega explosion  
f000929306 green glow light  
f000932211 white flashbang light  
f000929131 lantern orange  
f001000200 FIRE FEET aka dust on feet when walking etc  
f190900400 n/a  
f000000187 in your face soul light when you kill something  
  
  
  
DLC DCX  
  
f000000142 bright green light, centered on ground, fade out 5 seconds  
f000000143 bright green light with air distortion, fade out 5 seconds  
f000000144 bright green light, centered on ground, fade out 5 seconds  
f000000145 bright green light with air distortion, fade out 5 seconds  
f000000266 ***CRASHES GAME***  
f000000267 yellow light on hit, centered on ground, fade out 3 seconds  
f000000268 n/a  
f000000269 n/a  
f000000270 ***CRASHES GAME***  
f000000271 ***CRASHES GAME***  
f000000272 ***CRASHES GAME***  
f000000273 ***CRASHES GAME***  
f000000274 ***CRASHES GAME*** transformed beast cutter heavy (r2) swing  
f000000275 ***CRASHES GAME***  
f000000276 ***CRASHES GAME***  
f000000277 ***CRASHES GAME***  
f000000278 ***CRASHES GAME***  
f000000279 ***CRASHES GAME***  
f000000280 n/a  
f000000290 circular white air distortion, sucked in to activation point  
f000000291 circular white air distortion, pushed out from activation point  
f000000303 circular white air distortion, pushed out from activation point  
f000000360 n/a  
f000000361 n/a  
f000000362 n/a  
f000000363 n/a  
f000000364 n/a  
f000000921 n/a  
f000000970 n/a  
f000003021 n/a  
f000003121 n/a  
f000003221 n/a  
f000003800 n/a  
f000003801 big red debris explodes up and out circular at activation point  
f000003802 big red debris explodes up and out circular at activation point  
f000003803 big red debris explodes up and out circular at activation point  
f000003804 big red debris explodes up and out circular at activation point  
f000003805 big red debris explodes up and out circular at activation point   
f000003806 big red debris explodes up and out circular at activation point with air distortion  
f000003807 air distortion  
f000003808 big red debris explodes up and out circular at activation point  
f000003809 big red debris explodes up and out circular at activation point  
f000003810 big red debris explodes up and out circular at activation point  
f000003811 big red debris explodes up and out circular at activation point with air distortion  
.  
f000003818 n/a  
.  
f000003821 n/a  
.  
f000003825 n/a  
f000003826 n/a  
.  
f000003833 n/a  
.  
f000006600 3 or 4 alternating short orange streak lines going towards activation point  
f000006602 very fast flickery orange light with filmstrip sound, machine gun  
f000006603 very fast flickery orange light with filmstrip sound, machine gun  
f000006604 n/a  
f000006605 5 or 6 alternating orange streak lines going towards activation point  
f000006610 small orange flash on hit  
f000006615 small orange flash on hit  
f000006700 ***CRASHES GAME***  
f000006702 bright orange very quick flash centered on ground  
f000006703 bright orange very quick flash centered on ground  
f000006705 ***CRASHES GAME***  
f000006710 bright orange explosion with debris centered on ground  
f000006715 bright orange explosion with debris centered on ground  
f000006800 ***CRASHES GAME***  
f000006802 small orange flash with explosion sound at activation point  
f000006803 small orange flash with explosion sound at activation point  
f000006805 ***CRASHES GAME***  
f000006810 small orange flash with explosion sound at activation point  
f000006811 small orange flash with explosion sound at activation point  
f000006812 small orange flash with explosion sound at activation point  
f000006815 small orange flash with explosion sound at activation point  
f000006816 small orange flash with explosion sound at activation point  
f000006817 small orange flash with explosion sound at activation point  
f000007114 small red flash at activation point  
f000007115 n/a  
f000007116 blue splash of water in a line from activation point  
f000007117 green light on hit, fade out, 2 seconds, moonlight sword l1 transformation  
f000007118 dimmer green light on hit, fade out, 2 seconds  
f000007119 blood gush, sphere shape, with blood line shooting out of sphere  
f000007120 blood gush, sphere shape, with blood line shooting out of sphere  
f000007121 blood gush, sphere shape, delay 1 second and then line gushing out  
f000007122 blood gush in a line  
f000007123 small blood gush spherical  
f000007124 blood gush, sphere shape, with blood line shooting out of sphere  
f000007125 orange light, 6 quick flashes, drilling sound, 2 seconds duration  
f000007126 quick small orange flash  
f000007127 white light, fade out, 1 second  
f000007128 white light, fade out, 1 second  
f000007129 n/a  
f000007131 medium orange flash, centered on ground, fade out 1 second  
f000007205 n/a  
f000007503 medium green light flash centered on ground, fade out 1 second  
f000007504 medium green flash with slight distortion, fade out 1 second  
f000020020 n/a  
f000020061 1 sec delay then small circular ripple at activation X2  
f000020063 1 sec delay then small circular ripple at activation  
f000020098 big red centipede in half circle shape at activation  
f000020120 ***CRASHES GAME***  
f000020162 n/a  
f000020198 n/a  
f000020220 small yellow light on hit, 3 pulses each pulse smaller light  
f000020221 small yellow light on hit, 2 pulses each pulse smaller light  
f000020262 black circular ripple on hit with sound, fade out 2 seconds  
f000020320 orange light flash  
f000020398 n/a  
f000020420 n/a  
f000200050 small blue light, flashes bright after 1 second, back to small, fadeout  
f000200051 red light at activation point, fade out, 3 seconds  
f000200052 n/a  
f000201050 blue light at activation with little tiny blue sphere in front  
f000201051 n/a  
f000201052 large black circular air ripple effect  
f000202001 Projectiles from A call beyond  
f000202008 medium orange/red light, fade out, 5 seconds  
f000202050 blacksky eye projectile  
f000202051 bright red light at activation, fade out, 5 seconds  
f000202052 giant snake head comes out of black air ripple to chomp down  
f000203050 black cloud, small air ripple, debris, explosion  
f000203051 bright red flash, ghost sound  
f000204001 white-blue dot appears and fades out  
f000204050 n/a  
f000250030 green light, fade out, 2 seconds, moonlight sword l2,r2 first effect  
f000250035 green light with green shine in a line, fade out 2 seconds  
f000250040 small red hot item with heat wave distortion - boom hammer transform sfx  
f000250041 orange light, fade out, 2 seconds  
f000250042 small orange flickery light and then debris explosion, 2 seconds  
f000250050 small orange flickery light and then debris explosion 5 seconds  
f000250061 blood gushing out 2 seconds  
f000250070 medium flickery orange light, cranking sound continues after fade out for 3 seconds  
f000250080 medium orange flash *** SFX 1 for death when actual injury takes place (SFX 2 in patch.dcx)  
f000250081 grey blood (fish goo) circular fountain at activation  
f000250083 small circular windy effect, 5 seconds  
f000250100 white flash on hit  
f000250101 white blood (fish guts) explosion from activation point  
f000250102 n/a  
f000250103 n/a  
f000250110 n/a  
f000250111 n/a  
f000252010 n/a  
f000252011 oblong medium size red mist explosion  
f000252030 green light then ***CRASHES GAME***  
f000252031  moonlight sword r2 projectile light shadow  
f000252032   moonlight sword l2 projectile green light  
f000252033 moonlight sword l2 effect 2, green shockwave  
f000252034 ***CRASHES GAME***  
f000252035  moonlight sword running r2 projectile  
f000252040 yellow flash  
f000252041 orange flash  
f000252042 orange flash  
f000252043 orange flash  
f000252060 huge blood explosion, all 4 directions with a little distortion  
f000252062 huge blood explosion directions: up, left, right  
f000252070 small flickery orange light 1 second, also dentist drill sound 3 seconds  
f000252071 small flickery orange light and dentist drill sound, 3 seconds  
f000252080 fast large white mist explosion
f000252082 mist tornado with debris flies up, starts at head height  
f000252090 ***CRASHES GAME***  
f000252091 ***CRASHES GAME***  
f000252092 ***CRASHES GAME***  
f000252102 n/a  
f000252103 a few red dead fishes spurt out on hit  
f000252104 n/a  
f000252030 green flash  
f000253031 green flash  
f000253032 green flash  
f000253033 green flash  
f000253034 green flash  
f000253035 green flash  
f000253070 3 quick small orange light pulses  
f000253090 n/a  
f000253091 medium size oblong air distortion  
f000253102 n/a  
f000253103 n/a  
f000610310 n/a  
f000610311 yellow light fade out, 10 seconds  
f000610500 white light, fade out, 6 seconds  
f000610502 white light, fade out, 5 seconds  
f000610510 red build up 3 seconds, on last second red mist dissipates with light fading, mist repeats  
f000610550 dim white light fades in and out, 8 seconds  
f000625001 bright white light with upwards mist tornado, 3 seconds  
f000724070 n/a  
f000900261 bright orange explosion with large paper debris  
f001000601 red debris explodes up and out circular at activation point  
f001000603 big red debris explodes up and out circular at activation point  
f001000621 n/a  
f001101405 red messengers with puddle and misty red light  
f001101408 red messengers with puddle and intense red light  
f001101409 red messengers with puddle and intense white light  
f190000027 n/a  
  
m21.ffxbnd.dcx  
  
f000721010 blood spurt from "submit" ending cutscene neck chop  
f000921216 hunters dream yellow light 1 (high above doll)  
f000921100 hunters dream yellow light 2 (doll lantern)  
f000921217 hunters dream Yellow light 3 (general doll area)  
f001101402 hunters dream grave stone second light  
f001101403 hunters dream chalice dungeon grave stone light  
  
m_24_00 dcx file  
f000627030 white glow pulsing  
f000627000 yarnham cathedral priest lantern guys lantern light  
f000627010 yarnham cathedral priest lantern guys light on projectile launch  
f000627011 yarnham cathedral priest lantern guys light under actual projectile  
  
m25  
  
f000725011 after lorarious cutscene swirling wind part 1  
f000725012 after logarious cutscene wind part 2 (crashy)  
  
m28  
  
f000610520 simple while ball projectile  
  
m29a  
  
f10000080 medium lava that spurts out sideways  
  
m29b  
  
f000610000 n/a  
f000610050 n/a  
f000610051 n/a  
f000610100 dim orange light  
f000610101 orange flash then dim orange, fadeout, 3 seconds  
f000610102 quick fade in fade out orange flash  
f000610110 dim orange light, fadeout, 2 seconds  
f000610111 orange flash then dim orange light, fadeout, 5 seconds  
f000610112 quick fade in fade out orange flash  
f000610150 dim yellow light, fade out, 5 seconds  
f000610221 air distortion  
f000610404 n/a  
f000610450 *** CRASHES GAME ***  
f000610502   
f000610505 delay and then flash and then tiny ball with two expanding fading circles  
f000610510 delay and then orange flash and then large expanding fading mist sphere  
f000610515 orange light quick pulsing  
f000610601 n/a  
f000610611 blue small expanding fading circle and then white light, fadeout, 5 seconds  
f000610612 contracting transparent blue sphere  
f000		white light the spins like a siren  
f000610617 white light air distortion  
f000610621 green light, thunder sound, light balls exploding up, good for magix  
f000610622 bright white green light  
f000610625 very bright white light, thunder sound  
f000610900 n/a  
f000610903 n/a  
f000611101 expanding black transparent sphere, cyclone shaped air distortion  
f000611105 white light on weapons, fadeout, 5 seconds  
f000611125 n/a  
f000611201 transparent splurge of green goo  
f000611400 n/a  
f000612200 n/a  
f000612203 n/a  
f000612500 n/a  
f000612710 slight air distortion  
f000612900 n/a   
f000612901 two little red balls  
f000613005 n/a  
f000620203 white light, fadeout, 3 seconds  
f000620213 white light then rays of spider webs suck in to activation  
f000620400 n/a  
f000620401 n/a  
f000620410 n/a  
f000620805 dim white light, fadeout, 2 seconds  
f000620806 white light and expanding mist cloud  
f000621001 white light with air distortion, 5 seconds, no fadeout  
f000621002 expanding black circle, twice  
f000621006 big purple and black expanding cloud with air distortion  
f000621011 expanding blue transparent sphere on activation, white light, fadeout 5 seconds  
f000621012 contracting white transparent circle to white light  
f000621016 n/a  
f000621100 expanding blue transparent sphere on activation, white light  
f000621101 expanding blue transparent sphere on activation  
f000621104 red-white light, fadeout, 3 seconds  
f000621201 small intense orange light, flashes 3x, fadeout  
f000621208 expanding red mist circle  
f000621220 orange flash, gun sound  
f000621225 dim orange light  
f000621226 flickering orange light, fadeout, 3 seconds  
f000621227 quick orange light  
f000621228 bright orange light  
f000621230 n/a  
f000621232 n/a  
f000621233 flickering orange light  
f000621235 orange light, fadeout, 5 seconds  
f000621605 intense orange light  
f000621615 orange light and air distortion  
f000621620 small intense orange light  
f000621621 small intense orange light  
  
m29c  
  
f000620900  
f000620901  
f000620911  
f000620915  
f000620920  
f000620921  
f000620990  
f000631310  
f000631311  
f000631318  
f000631319  
f000650104 extremely bright orange light, fadeout, 5 seconds  
f000650109  
f000650110  
f000650111  
f000650113  
f000650115  
f000650116  
f000650119  
f000650120  
f000650125  
f000650127  
f000650129   
f000650139   
f000650163 bright orange light  
f000650181  
f000650188  
f000650195 huge fire lava explosion  
f000650402 lightning activity around activation point  
f000650403 super lightning activity around activation point  
f000650412 3 short orange flashes and then small debris for 5 seconds  
f000650413 medium debris explodes on activation  
f000650414 big medium debris explosion on activation  
f000650415 lightning strike comes down, small white tornado then debris  
f000650416 big lighting surrounds activation then big white tornado and debris explosion  
f000650417 lightning strikes surrounding activation and then white tornado sucks in to point  
f000650418 small air distortion  
f000650425 quick lightning and then white tornado and debris  
f000650426 big lighting surrounds activation then big white tornado explodes out and debris   
f000650435 lightning strike comes down, small white tornado then debris  
f000650436 white tornado explodes out then lightning strikes and debris explodes  
f000650450 big red blood explosion  
f000650455 n/a  
f000650456 little blood red circle expands from activation  
f000650800 3 short orange flashes and then small debris for 5 seconds  
f000650815 quick lightning strikes come down and debris explosion  
f000650816 3 quick lightning strikes then debris explosion  
f000650819 lightning strikes from ground at feet of activation point, 5 seconds  
f000650821 lightning surrounds player after activation, 3 seconds  
f000650822 big lightning storm then explosion  
f000650823 big lightning storm surrounding activation  
f000650824 big lightning storm surrounding activation  
f000650825 super lightning in columns surrounding activation, 5 seconds  
f000650827 big transparent blue wave explodes outward and debris  
f000650828 big transparent blue wave explodes outward and debris  
f000650829 big transparent blue wave explodes outward and a little debris  
f000650831 white pulsing light and round lightning storm, light fades halfway thru, 8 seconds  
f000650832 white pulsing light and round lightning storm, light fades halfway thru, 8 seconds  
f000650833 white pulsing light and round lightning storm, light fades halfway thru, 8 seconds  
f000650834 white pulsing light and round lightning storm, light fades halfway thru, 8 seconds  
f000650835 big lighting surrounds activation then big white tornado explodes out and debris  
f000650836 big lighting surrounds activation then big white tornado explodes out and debris  
f000650845 lighting strike pulses  
f000650850 faster lightning strike pulses  
f000650855 lightning strikes around activation  
f000650857 lightning strikes up and left of activation  
f000650860 lightning strike surrounds, small white tornado then debris  
f000650861 lightning strike surrounds, small white tornado then debris  
f000650862 lightning strike surrounds, small white tornado then debris  
f000650863 lightning strikes from ground at feet of activation point, 5 seconds  
f000650870 big debris  
f000650871 huge debris explosion  
f000650872 large debris  
f000650895 green light and huge debris explosion  
f000650905 small flash and small debris  
f000650910 a little debris  
f000650915 n/a  
f000650916  
f000650920 debris and blood explosion  
f000650925  
f000650930 a little blood  
f000650936 blood and debris  
f000650940 small orange light  
f000650941  
f000650942   
f000650944   
f000651000 big air distortion  
f000651001 big air distortion  
f000651012 transparent meteor  
f000651013 white flash and debris explosion  
f000651014 big transparent white meteor  
f000651016 white light with distortion  
f000651017 white light and distortion in the sky  
f000651217 small white light with debris explosion  
f000651218 bright white light  
f000651225 3 short orange light bursts  
f000651230 small amount of debris  
f000651232 small distortion and debris  
f000651233 wind blows up and debris  
f000651235 big stellar stars sucked into activation  
f000651236 white light and expanding white mist  
f000651237 blue wind circles, above head, 5 seconds  
f000651241 big blood explosion  
f000651245 n/a  
f000651246 delay and then small red blood circle expands and disappears  
f000655100 white light and wind mist explodes with feathers above activation  
f000655190 a green light and feathers explodes from activation  
  
m29d  
  
f000610115 small steady orange light  
f000610116 bright orange light, fadeout, 1 second  
f000610117 small red light  
f000611302 small quick yellow light  
f000611600 n/a  
f000611601 small orange light 4 random pulses  
f000612100 n/a  
f000612300 n/a  
f000612306 n/a  
f000630000 fast pulsing bright orange light with heat waves  
f000630001 smaller, oranger fast pulsing light with heat wave, 8 seconds  
f000630002 small quick orange light  
f000630010 expanding fading white circle  
f000630016 n/a  
f000630017 n/a  
f000630021 bright white light  
f000630022 quick white light  
f000630102 red little bottle with yellow light and heat waves  
f000630110 small air distortion  
f000630115 n/a  
f000630311 small air distortion and tiny debris  
f000630405 bright orange-white light  
f000630410 small orange flash  
f000630412 n/a  
f000630415 small debris explosion  
f000631130 white light  
f000631200 n/a  
f000829000 fog ball  
f000829001 fog ball  
f000929020 n/a  
f000929021 n/a  
f000929045 n/a  
f000929046 n/a  
f000929050 sparse debris  
f000929080 small pulsing orange light  
f000929130 spotlight on enemy weapon on hit  
f000929140 n/a  
f000929141 n/a  
f000929142 n/a  
f000929160 pulsing green-blue light  
f000929209 smoke cloud, dissipates 2 seconds  
f000929210 smoke cloud, dissipates 2 seconds  
f000929213 blue light and black circle with stars, 3 seconds  
f000929215 blue light and black circle with stars, 3 seconds  
f000929217 dim blue light with black cloud and air distortion  
f000929218 blue light with air distortion  
f000929220 weird lens flare  
f000929225 orange flash  
f000929226 explosion and debris  
f000929227 white light, air distortion, and black mist  
f000929236 sky lightning  
f000929237 sky lightning   
f000929238 sky lightning  
f000929245 n/a  
f000929260 orange flash  
f000929300 small yellow-green light  
f000929302 n/a  
f000929304 n/a  
f000929305 n/a  
  
m32.ffxbnd.dcx  
  
f000000081 real fog that doesn't fill up the whole map  
f000007661 air distortion  
f000007761 big blood explosion to the left of activation  
f000610601 n/a  
f000610611 yellow light that switches to white light, fade out, 5 seconds  
f000610612 blue-white light with contracting blue transparent circle of mist  
f000610616 siren-like white light  
f000610617 white light  
f000610621 green light  
f000610622 bright green-white light  
f000610625 bright white light  
f000611101 expanding transparent black sphere, air distortion  
f000611105 white spotlight up and left of activation point  
f000611125 n/a  
f000621100 expanding white sphere  
f000621101 contracting white sphere  
f000621104 bright small red light  
f000625300 white light two flashes then fadeout  
f000625301 big yellow rock with yellow light, fadeout, 10 seconds  
f000625302 flash with debris explosion  
f000625307 white smoke and particles, 5 seconds  
f000625310 big blue stars and wind sucked in to activation point  
f000625320 small debris explosion  
f000625321 n/a  
f000627300 orange flickering light  
f000627306 small amount of debris  
f000627307 small rock debris explodes out  
f000627308 debris explosion  
f000627402 n/a  
f000627407 n/a  
f000627411 n/a  
f000631310 air distortion  
f000651000 air distortion  
f000651001 air distortion  
f000651012 rotating transparent meteor, fade out, 5 seconds  
f000651013 white flash and small amount of debris  
f000651014 large transparent rock, fade, 1 second  
f000651016 white light, fadeout, 1 second  
f000651017 white flash in the air  
f000932000 small orange light with heatwaves   
f000932003 n/a  
f000932007 n/a  
f000932200 big black cloud with purple light with round air distortion  
f000932201 white light, air distortion  
f000932210 big white screen air distortion, 3 seconds  
f000932211 greenish dispersed light slight flicker  
f000932220 bright white flashing light, good for items  
f190000061 spurt of grey blood (fish goo)  
  
m33.ffxbnd.dcx  
  
f000003033 n/a  
f000003133 n/a  
f000003333 n/a  
f000003433 n/a  
f000003533 n/a  
f000003633 n/a  
f000620805 white light, fade out, 4 seconds  
f000620806 quick bright white light  
f000621800 medium orange light, 3 double pulses, fade out, 5 seconds  
f000621804 lighting strike spherical from activation point  
f000621805 bright white flickering light with lightning strikes, 1 second  
f000621810 grey blood (fish goo) big spurt opposite direction of hit  
f000621806 quick white flash that turns blue and pulses out (for lightning hit)  
f000621814 smaller, slower gray blood spurt with slight air distortion, same direction as hit  
f000621850 orange light, fade out, 5 seconds  
f000624001 a few pieces of random sized debris flies out  
f000624003 pieces of random sized debris flies out  
f000624007 tiny rocks fly up from ground on activation  
f000624005 debris flies out on activation, 2x  
f000624206 debris flies out on activation, 2x  
f000624011 super huge debris flies out on activation  
f000624015 shiny dark red blood spurts out on activation  
f000625502 n/a  
f000627105 small debris flies out on activation  
f000627106 n/a  
f000627200 tiny debris flies out on activation  
f000625217 white spotlight, followed by yellow light and then debris explosion  
f000651218 super bright light, fade out, 5 seconds  
f000651225 three extremely quick orange pulses  
f000651230 wide sparse debris explosion on activation  
f000651232 wide sparse debris explosion on activation  
f000651233 sparse debris explosion away from activation  
f000651235 large white distorted light rays surrounding activation  
f000651236 bright orange light, fade out, 2 seconds  
f000651237 large blue space and stars circular wind gusts sucked into the left of activation, 5 seconds  
f000651241 big blood explosion at activation point  
f000651245 n/a  
f000651246 n/a  
f000651350 bright yellow light with distortion, fade out, 5 seconds  
f000733000 n/a  
f000926023 short delay and then two spurts of dark red reflect blood  
f000933009 crow sound  
f000933050 n/a  
f001000533 n/a  
f001000633 n/a  
  
m34.ffxbnd.dcx  
  
f000003035 n/a  
f000003041 n/a  
f000003135 n/a  
f000003141 n/a  
f000003235 n/a  
f000003241 n/a  
f000003335 n/a  
f000003341 n/a  
f000003435 n/a  
f000003441 n/a  
f000003535 n/a  
f000003541 n/a  
f000003635 n/a  
f000003641 n/a  
f000003835 n/a  
f000003841 n/a  
f000610900 n/a  
f000610901 n/a  
f000610903 two little transparent red nubbins appear then ***CRASHES GAME***  
f000612900 n/a  
f000612901 two little transparent red nubbins appear  
f000612910 n/a  
f000620900 ***CRASHES GAME***  
f000620901 big circular air distortion  
f000620910 small rock debris flies out, 5 seconds  
f000620911 small orange flash, 3 very quick pulses  
f000620915 big debris flies out then settles down to ground, 3 seconds  
f000620916 n/a  
f000620920 n/a  
f000620921 burst of real smoke expands on hit  
f000620941 1 second delay and then small gray blood (fish goo) spurt  
f000620942 n/a  
f000620950 n/a  
f000620951 gray blood (fish goo) spurt, repeat 3x  
f000620952 n/a  
f000620953 gray blood (fish goo) spurt, repeat 2x  
f000620954 n/a  
f000620960 n/a  
f000620961 big gray blood (fish goo) spurt, repeat 3x  
f000620964 n/a  
f000620980 medium debris explodes up from ground, 3 seconds  
f000620981 big debris explodes up from ground, 3 seconds  
f000620990 bright green-white light flash followed by gray blood (fish goo) explosion  
f000621001 bright orange-white light, no fade out, 3 seconds  
f000621005 orange-white light, fade out, 4 seconds  
f000621010 bright green-white light, no fade out, 3 seconds  
f000621011 bright green spotlight with white lens flare, fade out, 5 seconds  
f000621015 n/a  
f000621016 dark red reflecty blood spurt in direction of hit  
f000621020 orange light, fade out, 5 seconds  
f000621024 n/a  
f000621311 n/a  
f000621312 n/a  
f000625501 n/a  
f000625502 n/a  
f000625505 n/a  
f000627110 quick small orange flash  
f000627118 n/a  
f000627121 n/a  
f000640000 small quick orange flash, blood sound  
f000640005 small quick orange flash, blood sound  
f000640016 small orange circle light with red hot object, no light source  
f000640020 air distortion to the left of activation  
f000640021 blood explosion to the left of player  
f000640070 small air distortion  
f000640081 ***CRASHES GAME***  
f000640085 two red streaks but ***CRASHES GAME***  
f000640086 ***CRASHES GAME***  
f000640092 n/a  
f000640093 n/a  
f000640094 orange light on player, fade out, 2 seconds  
f000640100 small intense purple blob and light  
f000640105 small air distortion  
f000640110 quick orange flash on hit  
f000640112 bright yellow light, fade out, 2 seconds  
f000640115 air distortion with small red light, fade out, 2 seconds  
f000640116 air distortion with medium red-white light, fade out, 2 seconds  
f000640117 air distortion with medium red-white light, fade out, 2 seconds, followed by circular air distortion  
f000640118 small air distortion  
f000640131 purple mist blast followed by another purple fading expanding mist air ripple  
f000640132 medium white light, fade out, 2 seconds  
f000645001 large intense orange light, fade out, 5 seconds  
f000645005 n/a  
f000645006 large orange light, fade out 3 seconds  
f000645010 orange light centered on player, fade out, 2 seconds  
f000645011 orange light, fade out, 2 seconds  
f000645012 medium intense orange light, flickering, fade out, 5 seconds  
f000645020 small intense orange light centered on player but far away  
f000645021 medium circular orange mist, fade out, 5 seconds  
f000645022 n/a  
f000645025  
f000645030 air distortion, 3 seconds  
f000645035 bright white light followed by big orange blood goo explosion, 3 seconds  
f000645025 intense large orange light, fade out, 5 seconds  
f000640111 n/a  
f000640130 white light, fade out, 3 seconds  
f000645102 n/a  
f000645104 bright green-white light, flickering, fade out, 5 seconds  
f000645111 very small orange light, 3 very quick pulses and two spurts of small debris  
f000645112 very small orange light, 3 very quick pulses and two spurts of small debris  
f000645114 n/a  
f000645115 ***CRASHES GAME***  
f000645118 green light above and behind activation  
f000645119 some sort of transparent light but ***CRASHES GAME***  
f000645120 bright green-white light with shaft of light towards activation point  
f000645121 ***CRASHES GAME** but probably the same as above with orange-white light  
f000645122 bright green-white light  
f000645127 bright green-white light with shaft of light towards activation point  
f000645130 bright green-white light, air distortion, debris explosion  
f000645135 very bright green-white light, fade out, 6 seconds  
f000645136 smoke-like flowing off activation, 1 second  
f000645144 very small orange light, 3 very quick pulses and two spurts of small debris  
f000645151 bright green-white light  
f000645152 very bright green-white light, 3 quick pulses  
f000645160 n/a  
f000645161 n/a  
f000645190 small air distortion  
f000734200 n/a  
f000734204 n/a  
f000734209  
f000734300   
f000734302  
f000734303 green-white light that faces enemy front, fade out, 3 seconds  
f000734304 green-white light with rays coming down to activation point, fade out, 2 seconds  
f000734306 green-white light with vertical black circular distortion, fade out, 3 seconds  
f000734308 wide black light ray with glowing edge coming from sky to activation point, 3 seconds  
f000834000 green-white light behind activation point, fade out, 3 seconds  
f000834002 green-white light behind activation point, fade out, 8 seconds  
f000934100 orange light, fade out, 8 seconds  
f000934200 small air distortion followed by medium circular debris ejection  
f000934212 small orange flash  
f001000335 n/a  
f001000341 n/a  
f001000535 n/a  
f001000541 n/a  
f001000635 n/a  
f001000641 n/a  
f001451027 n/a  
f001451127 n/a  
f001451135 n/a  
f001451201 small distortion followed by circular large debris ejection  
f001451227 n/a  
f001451235 small distortion followed by circular large debris ejection  
f001451301 small distortion followed by circular large debris ejection  
f001451335 small distortion followed by circular large debris ejection  
f001451435 small distortion followed by circular large debris ejection  
f001451535 n/a  
f001451735 n/a  
f001451835 circular large debris ejection  
f001451935 medium debris eruption from ground to right of activation point  
f190780000 gray blood (fish goo) spurt in direction of hit  
f190900400 orange blood (maybe lava) big spurt in direction of hit  
  
  
m35_ffxbnd.dcx  
  
f000000370 red light with air distortion, fade out, 2 seconds  
f000000317 red light, fade out, 5 seconds  
f000000372 red light with air distortion, fade out, 2 seconds  
f000003034 n/a  
f000611000 n/a  
f000626200 quick yellow-white flash explosion  
f000626201 n/a  
f000626210 quick yellow flash with barrel breaking sound  
f000626211 little grey 3d-arrow appears  
f000626215 orange light with gun fire streak, machine gun sound, 5 seconds  
f000626216 orange streaks going into activation point, 3 seconds  
f000626217 small orange flash at activation point  
f000626220 medium orange pulsing light, 5 seconds  
f000626223 wind blowing sound, 3 seconds  
f000626230 n/a  
f000626233 n/a  
f000640200 dim blue-white light, fade out, 4 seconds  
f000640202 white light, two pulses  
f000640205 n/a  
f000640206 n/a  
f000640210 small red blood goo spurt in opposite direction of hit  
f000640216 3 small quick orange pulses followed by 3 seconds of small debris ejected  
f000640220 n/a  
f000640221 n/a  
f000640222 n/a  
f000640223 n/a  
f000640225 air distortion  
f000640230 medium red blood goo spurts the opposite way of hit  
f000640231 quick red blood goo explosion towards player  
f000640235 n/a  
f000640236 n/a  
f000640237 n/a  
f000640242 small red debris on hit  
f000640300 very bright yellow light, fade out, 8 seconds  
f000640301 medium red rock debris explosion  
f000640305 white light fade in, fade out, 3 seconds  
f000640306 white light fade in, fade out, 2 seconds  
f000640307 bright white flash  
f000640310 yellow light, fade out, 3 seconds  
f000640311 white light, centered on player, fade out, 5 seconds  
f000640315 big rock debris exploding towards player  
f000640320 green-white light, fade in and out, 2 seconds  
f000640321 meteor with blue-white light with rotating distortion, fade out, 5 seconds  
f000640322 white light, circular air ripple, some debris, fade out, 2 seconds  
f000640323 white-orange flash with debris exploding out  
f000640324 bluish fog that actually works  
f000640330 green-white light, fade out, 2 seconds  
f000640331 n/a  
f000640332 small white spotlight, fade out, 5 seconds  
f000640333 medium white flash on hit  
f000640334 white flash followed by white air ripple, followed by black fog circle for 6 seconds  
f000645200 ***CRASHES GAME*** Lady Maria Double Overhead blood trail swing  
f000645204 bright orange light, fade out, 2 seconds  
f000645205 small orange flash  
f000645206 expanding red smoke tornado, 2 seconds  
f000645207 expanding red smoke tornado, 2 seconds, followed by white-orange light flash  
f000645210 quick bright orange flash, centered on player  
f000645215 red blood goo spurts out and straight up  
f000645216 big red blood goo explosion  
f000645220 air distortion  
f000645221 expanding white smoke tornado, 2 seconds  
f000645222 air distortion  
f000645223 air distortion followed by white-orange flash  
f000645225 1/2 second delay and then big spurts of red goo blood suck into activation point  
f000645226 big red blood goo explodes low res as if close to player's eyes  
f000645227 dark red lady maria air explosion stage 1 ***CRASHES GAME***  
f000645228 lady maria explosion part 2 ***CRASHES GAME***  
f000645230 red streaks like a meteor trail but ***CRASHES GAME***  
f000645231 n/a  
f000645232 red streaks like a meteor trail but ***CRASHES GAME***  
f000645233 orange light behind player, fade out 2 seconds  
f000645240 ***CRASHES GAME***  
f000635244 orange light, fade out, 2 seconds  
f000645247 .5 second delay then orange light  
f000645250 ***CRASHES GAME***  
f000645254 green light  
f000645256 ***CRASHES GAME***  
f000645257 n/a  
f000645259 n/a  
f000645260 ***CRASHES GAME***  
f000645261 n/a  
f000645263 n/a  
f000645264 distant orange light behind player, fade out 1 second  
f000645265 n/a  
f000645270 ***CRASHES GAME***  
f000645291 n/a  
f000645293 n/a  
f000735002 n/a  
f000735003 n/a  
f000735005 n/a  
f000835001 green light on enemy weapon, fade out, 5 seconds  
f000935000 n/a  
f000935001 n/a  
f000935005 n/a  
f000935010 n/a  
f000935011 aura from a shining light  
f000935012 n/a  
f000935013 n/a  
f000935020 n/a  
f000935025 n/a  
f000935026 n/a  
f000935030 n/a  
f000935100 green-white light, bright, fade out, 5 seconds  
f000935101 small orange-white light, fade out, 5 seconds  
f000935102 smaller orange-white light, fade out, 8 seconds  
f000935200 n/a  
f000935201 n/a   
f000935202 n/a  
f000935210 slight air distortion  
f000935211 n/a  
f001262001 n/a  
f001262101 n/a  
  
M36.ffbnd.dcx  
  
f000000370 whitish-red light centered on ground, fade out, 3 seconds  
f000000371 red light centered on ground, fade out, 5 seconds  
f000000372 whitish-red light centered on ground, fade out, 2 seconds  
f000000930 small white lightning, 2-3 tendrils  
f000000931 medium white lightning, 3-4 tendrils  
f000000932 n/a  
f000003037 n/a  
f000003137 n/a  
f000003237 n/a  
f000003337 n/a  
f000003437 n/a  
f000003537 n/a  
f000003637 n/a  
f000003837 n/a  
f000007671 air distortion, 2 seconds, large  
f000007771 grey and red blood vertical explosion slightly to left of activation point  
f000625500 n/a  
f000625501 n/a  
f000625502 n/a  
f000625505  
f000625600 yellow ball of light, original item icon size  
f000625601 extremely bright yellow light, fade out, 5 seconds  
f000640405 small bright yellow-white light at activation point, fade out, 5 seconds  
f000640406 small bright yellow-white light at activation point, fade out, 5 seconds  
f000640407 extremely bright yellow light, fade out, 3 seconds  
f000640408 yellow-white light, fade out  
f000640409 yellow-white light, fade out  
f000640501 bright yellow-white flash with fast pulses  
f000640502 bright white-yellow flash then small white lightning, 2-3 tendrils  
f000640510 fast pulsing bright green light, 5 seconds  
f000640511 very bright yellow-white light, pulse, 1 second  
f000640515 red-white light, fade out, 5 seconds  
f000640516 dimmer red-white light, 4 seconds  
f000640517 small air distortion  
f000640520 bright green light behind activation point in air, fade out, 12 seconds  
f000640525 green light pulsing with white lightning tendrils behind activation point  
f000640256 small green-white light, on for 1 second, off for 1 second, repeat once  
f000640590 red-white light, fade out, 5 seconds  
f000640591 small air distortion  
f000640700 n/a  
f000640701 n/a  
f000640800 big circular air distortion  
f000645401 n/a  
f000645404 pink blood/goo explosion at activation  
f000645406 n/a  
f000645407 yellow flash followed by great goo explosion, 2 seconds total  
f000645408 n/a 
f000645409 yellow-white flash centered on player  
f000645410 ***CRASHES GAME***  
f000645420 small purple sphere light  
f000645421 yellow-white light, fade out, 3 seconds  
f000645422 yellow-white light at activation with red mist, fade out  
f000645423 yellow-white light, fade out, 3 seconds  
f000645424 very bright yellow-white flash, fade out, followed by small debris falling  
f000645425 yellow-white light, fade out, 3 seconds  
f000635426 bright yellow-white light, fade out, 1 second  
f000645430 bright white light, fade out 1 second followed by falling debris  
f000645500 n/a  
f000645501 n/a  
f000651102 bright white flash followed by 2-3 lightning strikes on ground  
f000651112 bright white pulsing with lightning strikes and falling debris, 8 seconds  
f000736000 n/a  
f000736001 n/a  
f000736002 n/a  
f000736003 n/a  
f000736005 n/a  
f000736006 n/a  
f000736103 n/a  
f000736110 n/a  
f000736111 n/a  
f000926023 3 spurts of dark red reflecting blood  
f000936000 n/a  
f000936001 little bursts of water in the air around activation, 3 seconds  
f000936005 n/a  
f000936020 n/a  
f000936100 green light, fade out, 10 seconds  
f000936101 little orange light, fade out, 5 seconds  
f000936102 orange light, fade out, 5 seconds  
f000936200 bright orange light, fade out  
f000936201 bright orange light, fade out  
f000936202 bright orange light, fade out  
f001000537 n/a  
f001000637 n/a  
f001406001 rock debris flies out from activation point  
f001406101 rock debris flies out from activation point  
f001406201 a few bits of rock debris flies out from activation point  
f001406236 n/a  
f001406237 n/a  
f001454010 n/a  
f001454036 n/a  
f001454110 n/a  
f001454136 n/a  
f001454210 rock debris flies out from player  
f001454236 rock debris flies out from player  
f001454310 a few bits of rock debris flies out from player  
f001454336 a very few bits of rock debris flies out from activation point  
f001454410 rock debris flies out from activation point  
f001454436 rock debris flies out from player  
f190000037 n/a  
f190000071 gray and red blood spurts out in the direction of hit  
f190000171 n/a  

congratulations - if you made it this far you are insane and love BloodBorne as much as us. Can't wait to see what you do with it!  
