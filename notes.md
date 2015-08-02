1DAWG






dclasses,actions,mental stats,physical stats,questions,,,,,,,
,,,,,,,,,,,
bandit,attack,aggression,health,how likely to attack,,,,,,,
wild dog,wait,curiosity,stamina,"if they attack, how does that work",,,wait restores stamina,shared,pc,npc,stamina needs descriptors like health has
villager,flee,boldness,agility,"if they don't attack, what do they do",,,flee checks ,name,dispo,faction,/%a
legionnaire,,,,"if attack occurs, how does it end",,,,stats,notoriety multiplier,friendliness,
enclave,bite,skills?,maxHealth,how to escape,,,,,faction alignments,weapon/gear,to do:
bobcat,maul,,maxStamina,do they stop attacking after a point,,,,,,,- flesh out bandit checks so they are equivalent to dawg checks
coyote,howl,,,dogs are faster than people,,,,,,,"- create better behavior for pursuit, does bandit ever decide to leave you alone?"
mountain lion,,,,stealth vs pursuit,,,,,,,- add choice to kill or leave
bear,verbs,,,nocturnal vs day hunter,,,,,,,- add looting to check the disabled bandit if desired
,bark,,,,,,,,,,- make a generic enemy class where bandit gets injected
,growl,,,crit?,,,,,,,"-- bandit is the generic class, figure out how to make variants and use the same template to avoid boilerplating yourself into oblivion"
,snarl,,,hit ratio?,,,,,,,"- think about different kinds of attacks, variable damage"
,snap,,,items?,,,,,,,"- blood smell mechanic, add max health so blood smell is a percentage of max health, like bubbling ships in homeworld"
,howl,,,,,,,,,,- 
,pant,,,,,,,,,,
,whine,,,,,,,,,,%/
,whimper,,,,,,,,,,"/%a hitting should relate to what kind of damage is being dealt, changing ""hit"" to relevant verb for bandits%/"
,squeal,,,,,,,,,,/%a make better combat math %/
,yelp ,,,,,,"build group of NPCs, humans + animals",,,,"/%a fleeing favors the one doing the fleeing, should perhaps be random %/"
,bite,,,,,,friendliness check ,,,,/%a need better combat system math %/
,paw,,,,,,initiative check ,,,,"/%a dog fleeing  favors dawg, should perhaps be random %/"
,gnaw,,,,,,attack loop check,,,,
,lick,,,,,,,,,,/%a need more elegant waiting recovery behavior  %/
,,,,,,,fight for health and stamina,,,,
,,,,,,,"get to the end of health, dead",,,,
,howl,,,,,,"get to the end of stamina, disabled",,,,
,// damages boldness ,,,,,,kill or leave? ,,,,
,,,,,,,,,,,
,bite,,,,,,notoriety percentage,,,,
,// damages health moderately ,,,,,,,,,,
,// costs little stamina ,,,"<<if $time.season eq ""spring"">>",,,some things to think about,,,,
,,,,,,,friendliness / notoriety,,,,
,maul,,,14,cool,,gifts / dialogue,,,,
,// damages health ,,,36,mild,,disposition,,,,
,// costs much stamina ,,,19,warm,,,,,,
,,,,22,hot,,"health, smell of blood",,,,
,,,,,,,readiness,,,,
,,,,6,rain,,,,,,
,,,,1,snow,,,,,,
,,,,,,,,,,,
,,,,66,gusty,,,,,,
,,,,11,windy,,,,,,
,,,,15,breezy,,,,,,
,,,,51,clear,,,,,,
,,,,5,hazy,,,,,,
,,,,15,cloudy,,,,,,
,,,,10,overcast,,,,,,
,,,,,,,,,,,
,,,,,,,,,,,
,,,,"<<elseif $time.season eq ""summer"">>",,,,,,,
,,,,1,warm,,,,,,
,,,,12,hot,,,,,,
,,,,78,scorching,,,,,,
,,,,,,,,,,,
,,,,11,rain,,,,,,
,,,,1,snow,,,,,,
,,,,,,,,,,,
,,,,15,gusty,,,,,,
,,,,12,windy,,,,,,
,,,,12,breezy,,,,,,
,,,,53,calm,,,,,,
,,,,55,clear,,,,,,
,,,,5,hazy,,,,,,
,,,,14,cloudy,,,,,,
,,,,4,overcast,,,,,,
,,,,,,,,,,,
,,,,,,,,,,,
,,,,"<<elseif $time.season eq ""autumn"">>",,,,,,,
,,,,12,cool,,,,,,
,,,,22,mild,,,,,,
,,,,22,warm,,,,,,
,,,,35,hot,,,,,,
,,,,1,scorching,,,,,,
,,,,,,,,,,,
,,,,8,rain,,,,,,
,,,,2,snow,,,,,,
,,,,,,,,,,,
,,,,1,gusty,,,,,,
,,,,1,windy,,,,,,
,,,,32,breezy,,,,,,
,,,,59,calm,,,,,,
,,,,57,clear,,,,,,
,,,,4,hazy,,,,,,
,,,,12,cloudy,,,,,,
,,,,9,overcast,,,,,,
,,,,,,,,,,,
,,,,,,,,,,,
,,,,"<<elseif $time.season eq ""winter"">>",,,,,,,
,,,,52,cold,,,,,,
,,,,38,cool,,,,,,
,,,,1,warm,,,,,,
,,,,,,,,,,,
,,,,5,rain,,,,,,
,,,,9,snow,,,,,,
,,,,,,,,,,,
,,,,10,breezy,,,,,,
,,,,80,calm,,,,,,
,,,,57,clear,,,,,,
,,,,3,hazy,,,,,,
,,,,12,cloudy,,,,,,
,,,,12,overcast,,,,,,














//

Chapter 1: intro, birth
Chapter 2: newborn
Chapter 3: puppy
Chapter 4: grown, calamity

//
// Verbs //
//

bark
growl
snarl
snap
howl
pant
whine
whimper
squeal
yelp 
bite
paw
gnaw
lick

//
//
//



###############
### CHAPTER 1 ###
###############

//
// Scene 1 //
// 
// art: postapocalyptic moody urban setting
//
// 

<Howl...>

<Howl growl wimper.>

<Growl snarl, bark bark.
Whine, yelp. Howl. Pant, pant, pant.
Growl, bark. Howl. Whimper. Bark.
Snarl snap, growl, howl...>

<Pant, howl... howl growl wimper.>

// 
// Scene 2
//
// art: black, veiny yellowish, throbbing abstract
// larger text blocks on top, quotes below 
//


"Good girl. There's my good girl."

"Shh! Here it comes!"


...


"It moved! Oh my! ... Oh my god!"


...blind, blind 
first taste of cold 
awakened by mother's tongue
licking, slapping, biting
teeth against belly... 


"Great. Another mouth to feed."


...pulling, ripping, tearing
bloody, separate
weak, powerless, unbalanced
drowning in air
slow, sluggish, impossibly heavy...


"It moved! Oh my! ... Oh my god!"


rolling on something rough and stabbing
breathe, bear down on heavy lungs
scream, vocalize, anything
the tiniest sound...

...


<Squeal!>


"My puppy is having puppies!"


"What should we call the first one?"


% text input; get name var %


"Seriously? You wanna call it _that?_ I hope you know you're gonna be the one taking care of it."

"Dad, you promised..."



### Chapter 2 ###

puppy time, short sequence where entire level is inside the cage, maybe busting out, interaction with dad to choose first perk

### Chapter 3 ###

grown dog time, running up and down corridors, some infinite semi-infinite combat zone, trigger for shit to go down

### Chapter 4 ###

intro to wasteland

### Chapter 5 ###







"all ends with beginnings"



//
//
//
//
//




human companions
- pathfinding
- skill/capabilities
	> doctor
	> locksmith
	> fighter
	> vault dweller

combat system
- hp
- fatigue?
- bite, lunge, scratch
- bosses? cover?

mechanics
- drink water
- eat corpses
- interaction verbs
	> perks
	> upgrads





plot arc
- is there an overall plot?

quests
- something based on smell
- 

locations
- town

hold 327
(the poor man's vault; more crowded, less secure, leaky)

burned out settlement
scary, close to death though nothing kills you

night in the cold
first encounter... first meal.

friendly place
someone's back yard, porch, they have guns, sleep easy.

bandit camp
scavengers leeching on remnant of civilization
get a perk (maybe off some common character twixt town and bandits)

armory, old world weapons cache

first encounter with %legion% 

junkyard, encounter with familiar other

newcomers' sactuary

quarry (rare earths, some kind of tech)

god dog, something with a church and a preacher

drug dealers

the artist formerly known as three dawg

rat companion in the lonely shack

scavengers

slavers

famer

robot overlord

mirror universe

frosty humans in stasis pods and networked sim

dick iron

sideshow, dressed up, old dog / new tricks

detective dawg, bloodhound

neurotoxins/ portal reference

tall tale tellin boy / l4d reference (KEITH)

THE four bridges:
earth, underground tunnel
water, overground bridge
air, airport or maybe space elevator
fire, some irradiated waste

ghost dog
i am legend dog 
dog elders, council of schnauzers
wasteland revitalization 




upgrade quests: 
	brain
	armor
	agility
	jaw/attack


kill boss quests:
	frozen businessman and his robots
	warlord and his generals
	
grocery store

library

water filtration plant

oil rig

caverns


some breaking bad quest

gypsy mc, guy with beer wants weed




achievements:

REX, king of dogs, upgrade everything
MAN'S BEST FRIEND finish all human companion sidequests
DOG TIRED, made it to friendly settlement
YO DAWG, for beating some meta-quest
DOG PLUS TWO, beating 3dog quest
THE HOUSE NEVER WINS, kill frozen tycoon




sweet roll reference






// chapters //

YO, DAWG

A DOG AND HIS BOY

THE ONCE AND FUTURE DOG

THE HOUND OF WASTEVILLE

DOG TIRED

GONE TO THE DOGS

DOG WITH TWO BONES

LOVE ME, LOVE MY DOG

HAIR OF THE DOG

COME AT THE DOG, YOU BEST NOT MISS

SEE A MAN ABOUT A DOG









factions

think about equivalents:

bos
enclave
%ncr%


%legion%
	good: 
	bad: 
	
	self-deterministic, grab your gun and bring in the cat, 
	dogs: used as fighters, dangerous, dirty, ill-fed, badass mafuqqrs




free vegas


you're a dog though, who gives a fuck about these things? the humans can do whatever they're doing. 



dog in the dead city














// comments
choices -> tree;


dialog | options | table


id | entity | "text" | options | result | 

1 | entity.name | "" | option1, option2 | result1 | 





walk up to someone
initiate conversation:
are you initiating or are they?

make choices:
resolve outcomes
go to next dialog
or end dialog
(loops)




//
// Fonts

titling: AtariST8x16SystemFont
normal: nokiafc22
small: Volter__28Goldfish_29

computer: computer_pixel-7
rare npc: 5pixdeath
special npc: Romulus

//
//





//
// wastelander pixel art process //

1: photo, crop to square
2: mask/delete background
3: resize to 32x32px
4: desaturate
5: noise reduction
6: adjust levels
7: convert to 9 color grayscale (8+trans)
8: save

//
//



















greens
apples
bread
cottage cheese
beans, soups
juice
pepper
raisins 




// Screens
//
iPad Mini: 1024x768px / 7.9in / 163dpi
Macbook Air: 1440x900px / 13.3in / 128dpi
LG L9 Phone: 960x540px / 4.3in / 256dpi
//

///
quick first build

minimum

environment:
2-3 walls
3-4 floors
1 door
2 windows
2 rubble

1 dog
1 rat

///




factions


AI
human A vs human B
human C support the AI
beasts







/.//


8 directional sprites
|\-/|\-/


interior set:

9-patch for shading (AO)
           for rubble
           for stain, tire marks?
           lighting
           water



wall mat, >2 sets
floor mat, >2 sets



base layer > overlays

material > items

items are things like windows and bones

materials are gradient of patterns
see soft dystopias


what if colors are overlay?

remember sub squares
16x16
8x8




////


exploration game

dog in wilderness


fog of war -
distance draws in low contrast grayish dog spectrum
close draws in electric glitchy noise with directional guides to clues, locations, NPCs

expansive maps, environmental challenges. grass slows you down, you could fall into stuff, traps, etc.

/// grass subtly disturbed leaves a clue to traps


day and night versions







UI elements


dialog: call/response






///

verb chooser
	enabled, disabled, invisible
action reservoir
	empty, filling, full
d-pad
	active, inactive, disabled
enemy readiness
	"green, yellow, orange, red"
actor highlighting
	coded to relationship
health bar/smell of blood
smell overlay faint when moving, more visible in pause

///




wreckage of seed ship
repair?

choice:

destroy, don't make the mistakes of the past again
launch into the void, a distant minute hope
launch somewhere in the world, burn down and start again

add memento from the beginning? yes/no




ninja kitty







seedanspark.com






































/%a

we bring you now
                   to the weather
%/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a chapter titles                               %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

<h1><<print either("TWO-DOG NIGHT", "YO, DOG", "DOG TIRED", "GONE TO THE DOGS", "DOG WITH TWO BONES", "LOVE ME, LOVE MY DOG", "HAIR OF THE DOG", "COME AT THE DOG, YOU BEST NOT MISS", "SEE A MAN ABOUT A DOG")>></h1>

%/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a booklet back page                            %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

<p>wasteland stink... sand, dust, rust, blood, gunpowder, rubber, human sweat. tang of small beasts' fear, whisper sweet cactus, reedy grass. water someplace near, many flavored piss... and blended, scattered, tracked, muddled, acidic blood.</p>

%/


<h1 class="top">[[1D0G|dawg]]</h1>

[img[0dawg][dawg]]

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a soundtrack                                   %/
/%a track 1: mNaxGrPCVwY                         %/
/%a track 2: GxO7rqdWyYs                         %/
/%a track 3: ???????????                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<playbgm GxO7rqdWyYs>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a initialize dawg                 [img[0dawg]] %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $dawg = {
	name: "dawg",
	dispo: "exploring",
	notoriety: 1,
	bodycount: 0,
	sleep: 0,
	home: false,
	health: random(2, 10), maxHealth: 10,
	stamina: random(1, 8), maxStamina: 8,
	agility: random(1, 6 + 2),
	aggression: random(1, 6),
	curiosity: random(1, 6),
	boldness: random(1, 6),
}>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a initialize home                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $home = {
	env: "nowhere",
	level: 0
}>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a initialize time                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $time = {
	clock: 0,
	hour: 0,
	phases: 4,
	light: 0,
	hourSeason: 0,
	seasonCount: 1,
	season: "summer"
}>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a initialize environment                       %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $env = {
	type: "road",
	zone: "highway",
	style: "dusty",
	here: "dusty highway",
	next: "",
	log: "dusty highway"
}>>

/%a instantiate weather variables %/

<<set $weather = {
	sky: ""
}>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a        google analytics for oxru.in          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<script>
  (function(i,s,o,g,r,a,m){i['GoogleAnalyticsObject']=r;i[r]=i[r]||function(){
  (i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),
  m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)
  })(window,document,'script','//www.google-analytics.com/analytics.js','ga');

  ga('create', 'UA-45812449-1', 'auto');
  ga('send', 'pageview');

</script>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a core behaviors for overall loops %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a update clock                                 %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $time.clock += 1, $time.hour += 1, $time.hourSeason += 1>>

/%a time of day advancement %/

<<if $time.hour > 3>> 
<<set $time.phases += 1, $time.hour -= 4>>
<<endif>>

<<if $time.phases > 5>>
<<set $time.phases -= 6>>
<<endif>>

/%a daylight descriptors %/
<div class="sky">
<<if $time.phases eq 0>>
<<set $time.light to either("night", "midnight")>>
[img[sky0]]
<<elseif $time.phases eq 1>>
<<set $time.light to either("dawn", "sunrise")>>
[img[sky1]]
<<elseif $time.phases eq 2>>
<<set $time.light to either("morning", "day")>>
[img[sky2]]
<<elseif $time.phases eq 3>>
<<set $time.light to either("afternoon", "day")>>
[img[sky3]]
<<elseif $time.phases eq 4>>
<<set $time.light to either("evening", "sunset")>>
[img[sky4]]
<<elseif $time.phases eq 5>>
<<set $time.light to either("dusk", "twilight")>>
[img[sky5]]
<<endif>>
</div>
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a seasons                                      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a season advancement calculation %/

<<if $time.hourSeason > 2191>>
<<set $time.seasonCount += 1, $time.hourSeason -= 2192>>
<<endif>>

<<if $time.seasonCount > 3>>
<<set $time.seasonCount -= 4>>
<<endif>>

/%a season descriptors %/

<<if $time.seasonCount eq 0>>
<<set $time.season to "spring">>
<<elseif $time.seasonCount eq 1>>
<<set $time.season to "summer">>
<<elseif $time.seasonCount eq 2>>
<<set $time.season to "autumn">>
<<elseif $time.seasonCount eq 3>>
<<set $time.season to "winter">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a lunar phases                                 %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if $time.clock % 720 lt 12>>
<<set $time.moon = "new">>
<<elseif $time.clock % 720 gt 12 and $time.clock % 720 lt 168>>
<<set $time.moon = "crescent">>
<<elseif $time.clock % 720 gt 168 and $time.clock % 720 lt 192>>
<<set $time.moon = "first quarter">>
<<elseif $time.clock % 720 gt 192 and $time.clock % 720 lt 348>>
<<set $time.moon = "gibbous">>
<<elseif $time.clock % 720 gt 348 and $time.clock % 720 lt 372>>
<<set $time.moon = "full">>
<<elseif $time.clock % 720 gt 372 and $time.clock % 720 lt 538>>
<<set $time.moon = "disseminating">>
<<elseif $time.clock % 720 gt 538 and $time.clock % 720 lt 552>>
<<set $time.moon = "last quarter">>
<<elseif $time.clock % 720 gt 552 and $time.clock % 720 lt 708>>
<<set $time.moon = "balsamic">>
<<elseif $time.clock % 720 gt 708>>
<<set $time.moon = "new">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather probabilities                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a number of expected days of weather per season %/

<<if $time.seasonCount eq 0>>
	<<set $weatherChance = {
		cold: 0,
		cool: 14,
		mild: 36,
		warm: 19,
		hot: 22,
		scorching: 0,
		rain: 6,
		snow: 1,
		calm: 0,
		breezy: 66,
		windy: 11,
		gusty: 15,
		clear: 51,
		hazy: 5,
		cloudy: 15,
		overcast: 10
	}>>

<<elseif $time.seasonCount eq 1>>
	<<set $weatherChance = {
		cold: 0,
		cool: 0,
		mild: 0,
		warm: 1,
		hot: 12,
		scorching: 78,
		rain: 11,
		snow: 1,
		calm: 53,
		breezy: 12,
		windy: 12,
		gusty: 15,
		clear: 55,
		hazy: 5,
		cloudy: 14,
		overcast: 4
	}>>

<<elseif $time.seasonCount eq 2>>
	<<set $weatherChance = {
		cold: 0,
		cool: 12,
		mild: 22,
		warm: 22,
		hot: 35,
		scorching: 1,
		rain: 8,
		snow: 2,
		calm: 59,
		breezy: 32,
		windy: 1,
		gusty: 1,
		clear: 57,
		hazy: 4,
		cloudy: 12,
		overcast: 9
	}>>

<<elseif $time.seasonCount eq 3>>
	<<set $weatherChance = {
		cold: 52,
		cool: 38,
		mild: 1,
		warm: 0,
		hot: 0,
		scorching: 0,
		rain: 5,
		snow: 9,
		calm: 80,
		breezy: 10,
		windy: 0,
		gusty: 0,
		clear: 57,
		hazy: 3,
		cloudy: 12,
		overcast: 12
	}>>

<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a        weather chance randomization          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a temperature chance %/

<<set $weatherChance.temp = $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot + $weatherChance.scorching>>
<<set $weatherChance.tempRoller to random(1, $weatherChance.temp)>>

/%a precipitation chance %/

<<set $weatherChance.precip = $weatherChance.clear + $weatherChance.rain + $weatherChance.snow>>
<<set $weatherChance.precipRoller to random(1, $weatherChance.precip)>>

/%a wind chance %/

<<set $weatherChance.wind = $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy + $weatherChance.gusty>>
<<set $weatherChance.windRoller to random(1, $weatherChance.wind)>>

/%a sky chance %/

<<set $weatherChance.sky = $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy + $weatherChance.overcast>>
<<set $weatherChance.skyRoller to random(1, $weatherChance.sky)>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                  weather                     %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a temperature descriptors %/

<<if $weatherChance.tempRoller lte $weatherChance.cold>>
<<set $weather.temp = "cold">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool>>
<<set $weather.temp = "cool">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild>>
<<set $weather.temp = "mild">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm>>
<<set $weather.temp = "warm">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot>>
<<set $weather.temp = "hot">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot>>
<<set $weather.temp = "scorching">>
<<endif>>

/%a precipitation descriptors %/

<<if $weatherChance.precipRoller lte $weatherChance.clear>>
<<set $weather.precip = "dry">>
<<elseif $weatherChance.precipRoller gt $weatherChance.clear and $weatherChance.precipRoller lte $weatherChance.clear + $weatherChance.rain>>
<<set $weather.precip = either("rain", "thunderstorm")>>
<<elseif $weatherChance.precipRoller gt $weatherChance.clear + $weatherChance.rain>>
<<set $weather.precip = either("snow", "blizzard")>>
<<endif>>

/%a wind descriptors %/

<<if $weatherChance.windRoller lte $weatherChance.calm>>
<<set $weather.wind = "calm">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm and $weatherChance.windRoller lte $weatherChance.calm + $weatherChance.breezy>>
<<set $weather.wind = "breezy">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm + $weatherChance.breezy and $weatherChance.windRoller lte $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy>>
<<set $weather.wind = "windy">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy>>
<<set $weather.wind = "gusty">>
<<endif>>

/%a sky descriptors %/

<<if $weatherChance.skyRoller lte $weatherChance.clear>>
<<set $weather.sky = "clear">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear and $weatherChance.skyRoller lte $weatherChance.clear + $weatherChance.hazy>>
<<set $weather.sky = "hazy">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear + $weatherChance.hazy and $weatherChance.skyRoller lte $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy>>
<<set $weather.sky = "cloudy">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy>>
<<set $weather.sky = "overcast">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a      assume dawg exists in the universe      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $dawg.woundedness = $dawg.health / $dawg.maxHealth>>
<<if $dawg.woundedness lte 0.2>>
<<set $dawg.wounds = "beaten">>
<<elseif $dawg.woundedness lte 0.5>>
<<set $dawg.wounds = "exhausted">>
<<elseif $dawg.woundedness lte 0.7>>
<<set $dawg.wounds = "wounded">>
<<elseif $dawg.woundedness lte 0.9>>
<<set $dawg.wounds = "sore">>
<<elseif $dawg.woundedness eq 1>>
<<set $dawg.wounds = "healthy">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                                              %/
/%a                 outputs                      %/
/%a                                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<h1><<print $env.here>></h1>

<p>
<<print $weather.wind>>, <<print $weather.sky>>, <<print $weather.temp>> <<print $time.season>> <<print $time.light>>. 

<<if $weather.precip is not "dry">>
<<print $weather.precip>>. 
<<endif>>

<<if $time.phases gt 3 or $time.phases lt 2>>
<<if $weather.sky eq "clear" or $weather.sky eq "hazy">>
<<print $time.moon>> moon. 
<<endif>>
<<endif>>

<<print $dawg.wounds>> <<print $dawg.name>> <<print $dawg.dispo>>. 

<<if $npc.present eq true>>
a distinct scent is here... 
<<endif>>

<<if $encounter.chance gt 0 and $npc.present eq false>>
someone is here. 
<<elseif $encounter.chance gt 0 and $npc.present eq true>>
someone else too. 
<<endif>>

</p>

<<if $dawg.health / $dawg.maxHealth lte 0.3>>
<div class="dispo hostile"></div>
<<elseif $dawg.health / $dawg.maxHealth gt 0.3 and $dawg.health / $dawg.maxHealth lte 0.8>>
<div class="dispo neutral"></div>
<<elseif $dawg.health / $dawg.maxHealth gt 0.8>>
<div class="dispo friendly"></div>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                 choices                      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<ul>

<li>[[walk|environment][$dawg.dispo = "exploring", $npc.present = false, $encounter.chance = 0]]</li>

<<if $encounter.chance lt 1>>
<li>[[rest|sleep][$dawg.dispo = "resting"]]</li>
<<elseif $encounter.chance gte 1>>
<li>[[seek|encounter][$dawg.dispo = "seeking"]]</li>
<<endif>>

<<if $npc.present eq true>>
<li>[[sniff|socialize][$dawg.dispo = "sniffing"]]</li>
<<endif>>

<<if $dawg.home eq false and visited() gt 1 and $encounter.chance eq 0>>
<li>[[stay|home][$dawg.home = true, $home.env = $env.here]]</li>
<<endif>>

<<if visited() gt 4>>
<li>[[think|remember][$dawg.dispo = "thinking"]]</li>
<<endif>>

<<if $quest.active eq true>>

<<if $quest.name eq "bones" and $env.zone eq "garden">>
<li>[[<<$dawg.name>> smells bones|joshua]]</li>
<<endif>>

/%a add more quests %/

<<endif>>

/%a<li>[[Ø|debug][$dawg.dispo = "in a cyber trance"]]</li>%/

</ul>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%fin%%%%%/

/%a

notes: 

encounter type based on environment type 
humans, animals, machines 
different name classes

either bobcat, bear, 
either farmer, guard 
either sentry, drone
etc 

store individual log of environments to return and continue encounters?

%/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a select a random environment type             %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $env.type to either("road", "natural", "wastes", "urban", "dwelling", "scary", "industrial")>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a select a thematic zone from environment type %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if $env.type is "road">>
<<set $env.zone to either("highway", "trail", "path", "bridge", "sidewalk", "street", "ditch", "parking lot")>>
<<set $env.style to either("dusty", "long", "cracked", "lonely")>>

<<elseif $env.type is "urban">>
<<set $env.zone to either("suburbs", "downtown", "checkpoint", "boardwalk", "building", "campus", "shop")>>
<<set $env.style to either("gritty", "bustling", "crowded", "vacant","abandoned")>>

<<elseif $env.type is "dwelling">>
<<set $env.zone to either("farm", "ranch", "camp", "caravan", "lodge", "house", "mansion", "garden", "trailer", "rv", "wreck", "shacks", "radio station")>>
<<set $env.style to either("dusty", "cramped", "rundown", "old", "rusty" ,"overgrown")>>

<<elseif $env.type is "natural">>
<<set $env.zone to either("hill", "plain", "pine forest", "canyon", "crater", "foothills", "mountain", "marsh", "lake", "river", "stream")>>
<<set $env.style to either("wet", "dry", "dusty", "lonely", "wide")>>

<<elseif $env.type is "wastes">>
<<set $env.zone to either("dust", "mud flats", "salt flats", "scrub", "battlefield", "sands", "ashland")>>
<<set $env.style to either("windy", "wide", "long", "lonely", "desolate", "ruined", "still")>>

<<elseif $env.type is "industrial">>
<<set $env.zone to either("mine", "oil well", "power plant", "steel mill", "refinery", "control room", "slum")>>
<<set $env.style to either("gritty", "smoky", "putrid", "hazy", "humid", "tense")>>

<<elseif $env.type is "scary">>
<<set $env.zone to either("cave", "nest", "sewer", "tunnel", "dungeon", "bunker", "hold", "basement")>>
<<set $env.style to either("dank", "dry", "wet", "black", "glistening", "reeking")>>

<<endif>>

/%a name next environment %/

<<set $env.next = $env.style + " " + $env.zone>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a seed encounters                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $encounter = {
	chance: random(0, 2),
	count: random(0, 5),
}>>

<<set $npc = { present: false }>>

/%a  spawn carlos %/
/%a  he's always open for business %/
<<if $env.zone is "shop">>
<<set $npc = {
	name: "carlos",
	type: "human",
	class: "trader",
	pronoun: "he",
	friendliness: 1,
	health: 4,
	stamina: 3,
	agility: 3,
	aggression: 2,
	curiosity: 4,
	boldness: 3,
	present: true,
	civilized: true,
}>>
<p class="carlos">¡!¡!??</p>
<<endif>>

/%a  spawn rose %/
/%a  sometimes you see her on the road %/
<<if $env.type is "road">>
<<set $npc = {
	name: "rose",
	pronoun: "she",
	type: "human",
	class: "wanderer",
	friendliness: 2,
	health: 9,
	stamina: 6,
	agility: 5,
	aggression: 3,
	curiosity: 4,
	boldness: 6,
	present: true
}>>
<p class="rose">!?<3¡!</p>
<<endif>>

/%a  spawn beast %/
/%a  never know where he'll be %/
<<if $env.type is "natural" or $env.type is "wasteland">>
<<set $npc = {
	name: "beast",
	pronoun: "he",
	type: "animal",
	class: "beast",
	friendliness: -1,
	health: 18,
	stamina: 6,
	agility: 4,
	aggression: 6,
	curiosity: 6,
	boldness: 0,
	present: true,
}>>
<p class="beast">?¿!!!!¡</p>
<<endif>>



<<if $quest.active eq true>>

<<if $quest.name eq "bones" and $env.zone eq "garden">>
<<set $npc = {
	name: "joshua",
	pronoun: "he",
	type: "human",
	class: "gardener",
	friendliness: 1,
	health: 6,
	stamina: 3,
	agility: 2,
	aggression: 3,
	curiosity: 6,
	boldness: 4,
	present: true
}>>
<<set $encounter.chance = 0>>
<p class="rose">?¿?!¿¡</p>
<<endif>>

<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                                              %/
/%a                 outputs                      %/
/%a                                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() eq 1>>
<p>leaving <<print $env.here>>.</p>
<<endif>>
<p><<print $dawg.dispo>> <<print $env.next>>. 
<<if $encounter.chance gt 0>>someone is here.<<endif>></p>

<ul>

<li>[[keep walking|environment][$env.passing = $env.next, $time.clock += random(1,3)]]</li>

<li>[[stop here|dawg][$env.here = $env.next, $env.log += ", " +$env.next]]</li>

<<if $dawg.home eq true>>
<li>[[go home|home][$time.clock += random(1,12)]]</li>
<<endif>>

</ul>

/%a notes:

housebuilding / crafting flows

encounters at home

hanging out somewhere, bring sticks, find mate, reproduce, decorations, trophies, 

deliveries

things to do with your time 

%/

<h1>home</h1>

<p>
<<print $dawg.name>>'s corner of <<print $home.env>>. 

<<if $home.level eq 0>>
nothing here yet. 

<<elseif $home.level eq 1>>
have a small wood pile. 

<<elseif $home.level eq 2>>
have a large wood pile. 

<<elseif $home.level eq 3>>
have a leaky shelter. 

<<elseif $home.level eq 4>>
have a decent shelter. 
<<endif>>

<<print $dawg.dispo>>.
</p>

<ul>

<<if $home.level eq 0>>
<li>[[find wood|home][$dawg.dispo = "gathering", $home.level += 1, $time.clock += 2]]</li>

<<elseif $home.level eq 1>>
<li>[[find more wood|home][$dawg.dispo = "gathering", $home.level += 1, $time.clock += 4]]</li>

<<elseif $home.level eq 2>>
<li>[[build a shelter|home][$dawg.dispo = "building", $home.level += 1, $time.clock += 6]]</li>

<<elseif $home.level eq 3>>
<li>[[fix holes|home][$dawg.dispo = "fixing", $home.level += 1, $time.clock += 4]]</li>
<<endif>>

<li>[[sleep|sleep][$dawg.dispo = "sleeping"]]</li>
<li>[[leave|dawg][$dawg.dispo = "exploring"]]</li>
</ul>

/%a
notes:
reaction * notoriety 
faction alignment for flavor
refactor bandit script to be helpful
add options for more than one on one combat 
%/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a  spawn bandit %/
<<set $bandit= {

	name: "bandit",
	pronoun: "he",
	friendliness: random(-3, 1),

	health: random(1, 6),
	stamina: random(1, 6),
	agility: random(1, 6),

	aggression: random(1, 6),
	curiosity: random(1, 6),
	boldness: random(1, 6)

}>>

/%a give bandit some different qualities %/

<<set $bandit.name to either("bandit","banks","fish","hanna","steve","courier","dean","sam","dog","bear","bobcat","E D","farmer","villager","guard","jesse","walt")>>

<<set $bandit.pronoun to either("he","she","ze","it")>>

/%a///////////////////////////////////////////%/

/%a begin encounter text %/
<p>you encounter <<print $bandit.name>>.</p>

/%a///////////////////////////////////////////%/

/%a friendliness check %/

<<set $checkFriends = $bandit.friendliness * $dawg.notoriety>>
/%a add some more nuanced options here so notoriety creates unique situations %/

<<if $checkFriends lt 0>>
<<set $encounterType = "hostile">>
<p><<print $bandit.pronoun>> smells <<print either("dangerous","mean","like death","hostile")>>.</p>

<<elseif $checkFriends eq 0>>
<<set $encounterType = "neutral">>
<p><<print $bandit.pronoun>> smells <<print either("uncertain","wary","suspicious","distracted")>>.</p>

<<elseif $checkFriends gt 0>>
<<set $encounterType = "friendly">>
<p><<print $bandit.pronoun>> smells <<print either("safe","ok","like food","friendly")>>.</p>

<<endif>>

/%a end friendliness check %/

/%a///////////////////////////////////////////%/

/%a encounter checks %/

/%a friendly encounter%/
<<if $encounterType eq "friendly">>

<ul>
<li>[[bite|fightDawg][$dawg.dispo = "biting"]]</li>

<li>[[leave|dawg][$dawg.dispo = "pausing", $encounter.chance = 0]]</li>
</ul>

<<endif>>
/%a end friendly encounter%/

/%a///////////////////////////////////////////%/

/%a neutral encounter %/
<<if $encounterType eq "neutral">>
<ul>
<li>[[bite|fightDawg][$dawg.dispo = "biting"]]</li>
/%a <li>[[howl|fightDawg][$dawg.dispo = "howling"]]</li> %/
/%a <li>[[scratch|fightDawg][$dawg.dispo = "scratching"]]</li> %/
/%a <li>[[whine|fightDawg][$dawg.dispo = "whining"]]</li> %/
<li>[[leave|dawg][$dawg.dispo = "exploring", $encounter.chance = 0]]</li>
</ul>

<<endif>>
/%a end neutral encounter %/

/%a///////////////////////////////////////////%/

/%a begin hostile encounter %/
<<if $encounterType eq "hostile">>

/%a initiative check  %/
<<set $checkInitiative = ($bandit.agility * $bandit.boldness) / ($dawg.agility * $dawg.boldness)>>

<<if $checkInitiative lte 1>>/%a dawg wins initiative %/

<p><<print $bandit.name>> <<print either("is exposed","doesn't see you yet","stumbles")>>.</p>

<ul>
<li>[[bite|fightDawg][$dawg.dispo = "biting"]]</li>
<li>[[wait|fightDawg][$dawg.dispo = "waiting"]]</li>
<li>[[flee|fightDawg][$dawg.dispo = "fleeing"]]</li>
</ul>

<<else>>/%a dawg loses initiative %/

<p><<print $bandit.name>> <<print either("gets the drop on you","comes out of nowhere","sees you","takes a swing")>>.</p>

<ul>
<li>[[dig in|fightBandit][$dawg.dispo = "waiting"]]</li>
<li>[[dodge|fightBandit][$dawg.dispo = "dodging"]]</li>
</ul>

<<endif>>/%a end initiative check %/
<<endif>>/%a end hostile encounter %/

/%a end encounter check results %/

/%a///////////////////////////////////////////%/

/%a dawg fight loop segment %/

/%a///////////////////////////////////////////%/

/%a life check  %/
<<if $dawg.health gt 0>>

/%a stamina check  %/
<<if $dawg.stamina gt 0>>

/%a///////////////////////////////////////////%/

/%a biting check %/
<<if $dawg.dispo eq "biting">>

<<set $dawg.stamina -=1>>
<<set $hitDawg to random(1, 20)>>

<<if $hitDawg gt $dawg.agility + $dawg.aggression - $bandit.aggression>>

<<set $bandit.health -= 1>>

<p><<print $dawg.name>> succeeds <<print $dawg.dispo>> <<print $bandit.name>>. <<print $bandit.name>>'s health is now <<print $bandit.health>>.</p>

<<else>>
<p><<print $dawg.name>> fails <<print $dawg.dispo>> <<print $bandit.name>>.</p>
<<endif>>

<ul>
<li>[[continue|fightBandit][$dawg.dispo = "idle"]]</li>
</ul>

<<endif>>
/%a end biting check %/

/%a///////////////////////////////////////////%/

/%a start waiting check %/
<<if $dawg.dispo eq "waiting">>

<<set $dawg.stamina += random(1, 3)>>

/%a correct for health and stamina overruns %/

<<if $dawg.health > $dawg.maxHealth>>
<<set $dawg.health = $dawg.maxHealth>>
<<endif>>

<<if $dawg.stamina > $dawg.maxStamina>>
<<set $dawg.stamina = $dawg.maxStamina>>
<<endif>>

<p><<print $dawg.name>> waits.</p>

<p>stamina is now <<print $dawg.stamina>>.</p>

<ul>
<li>[[continue|fightBandit][$dawg.dispo = "idle"]]</li>
</ul>

<<endif>>
/%a end waiting check %/

/%a///////////////////////////////////////////%/

/%a fleeing check %/
<<if $dawg.dispo eq "fleeing">>

<p><<print $dawg.name>> attempts to flee

<<set $escapeDawg = ($bandit.agility + $bandit.aggression) / ($dawg.agility + $dawg.stamina)>>

<<if $escapeDawg lte 1>>
 and gets away!</p>

<ul>
<li>[[continue|environment][$dawg.dispo = "escaping", $encounter.chance -= 1]]</li>
</ul>

<<else>>
 but <<print $bandit.name>> pursues!</p>

<ul>
<li>[[continue|fightBandit][$dawg.dispo = "idle"]]</li>
</ul>

<<endif>>
/%a end escape check %/

<<endif>>
/%a end fleeing check %/

/%a///////////////////////////////////////////%/

/%a if the stamina check fails, this happens  %/
<<else>>

<<set $dawg.stamina = 2>>

<p><<print $dawg.name>> is exhausted.</p>

<ul>
<li>[[continue|fightBandit][$dawg.dispo = "idle"]]</li>
</ul>

<<endif>>
/%a end dawg stamina check section  %/

/%a///////////////////////////////////////////%/

/%a if the life check fails, this happens  %/
<<else>>

<p><<print $dawg.name>> meets death.</p>

<ul>
<li>[[...|death][$dawg.dispo = "dead"]]</li>
</ul>

<<endif>>
/%a end dawg fight loop %/

/%a bandit fight loop segment %/

/%a///////////////////////////////////////////%/

/%a check if bandit is alive %/
<<if $bandit.health gt 0>>

/%a check bandit stamina %/
<<if $bandit.stamina gt 0>>

/%a///////////////////////////////////////////%/

/%a check bandit boldness %/
<<if $bandit.boldness gt 1>>

<<set $bandit.stamina -=1>>

<<set $hit to random(1, 20)>>

/%a bandit attacking check %/
<<if $dawg.dispo eq "dodging">>
<p>you try dodging.</p>
<<set $hit -= 1>>
<<endif>>

<<if $hit gt $bandit.agility + $bandit.aggression - $dawg.aggression>>

<<set $dawg.health -= 1>>

<p><<print $bandit.name>> attacks and <<print $bandit.pronoun>> hits you. your health is now <<print $dawg.health>>.</p>

<<else>>

<p><<print $bandit.name>> attacks and <<print $bandit.pronoun>> misses you.</p>

<<endif>>

<ul>
<li>[[bite|fightDawg][$dawg.dispo = "biting"]]</li>
<li>[[wait|fightDawg][$dawg.dispo = "waiting"]]</li>
<li>[[flee|fightDawg][$dawg.dispo = "fleeing"]]</li>
</ul>
/%a end bandit attacking check %/

/%a///////////////////////////////////////////%/

/%a if the boldness check fails, this happens %/
<<else>>

<<set $escapeBandit = ($dawg.agility + $dawg.aggression) / ($bandit.agility + $bandit.stamina)>>

<<if $escapeBandit lte 1 >>

<p><<print $bandit.name>> <<print either("flees","turns tail and runs","heads for the hills")>>.</p>

<ul>
<li>[[continue|dawg][$dawg.dispo = "seeking", $dawg.notoriety += 0.2, $encounter.chance -= 1]]</li>
</ul>

<<else>>

<p><<print $bandit.name>> <<print either("struggles pitifully","begs for mercy","tries to crawl away")>>.</p>

<ul>
<li>[[bite|fightDawg][$dawg.dispo = "biting"]]</li>
<li>[[wait|fightDawg][$dawg.dispo = "waiting"]]</li>
<li>[[leave|dawg][$dawg.dispo = "leaving", $dawg.notoriety += 0.2, $encounter.chance -= 1]]</li>
</ul>

<<endif>>/%a end fleeing check %/

<<endif>>/%a end boldness check %/

/%a///////////////////////////////////////////%/

/%a if the stamina check fails, this happens  %/
<<else>>

<<set $bandit.stamina = 2>>

<p><<print $bandit.name>> stops moving. <<print $bandit.pronoun>> still breathes.</p>

<ul>
<li>[[bite|fightDawg][$dawg.dispo = "biting"]]</li>
<li>[[wait|fightDawg][$dawg.dispo = "waiting"]]</li>
<li>[[flee|fightDawg][$dawg.dispo = "fleeing"]]</li>
</ul>

<<endif>>
/%a end bandit stamina check section  %/

/%a///////////////////////////////////////////%/

/%a if the life check fails, this happens  %/
<<else>>

<<set $dawg.bodycount += 1>>

<p><<print $dawg.name>> kills <<print $bandit.name>>.</p>

<ul>
<li>[[feed|consuming][$dawg.dispo = "consuming", $encounter.chance -= 1]]</li>
<li>[[leave|dawg][$dawg.dispo = "exploring", $encounter.chance -= 1]]</li>
</ul>

<<endif>>
/%a end bandit fight loop %/

/%a resolution from encounter %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a consuming %/
<<if $dawg.dispo eq "consuming">>

<<set $dawg.health = $dawg.maxHealth, $dawg.stamina = $dawg.maxStamina>>
<<set $dawg.notoriety += 0.1>>
<p><<print $bandit.name>>'s flesh restores you.</p>

<ul>
<li>[[leave|dawg]]</li>
</ul>

<<endif>>
/%a end consuming %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<p><<print $dawg.name>> survived <<print $time.clock>> hours before perishing. the bones of <<print $dawg.name>> will litter the wasteland until they too become dust.</p>

<ul>
<li>[[restart|Start]]</li>
</ul>

<p><<print $dawg.dispo>>...</p>

<ul>

<<if $npc.name eq "rose">>
<li>[[rose is here|rose]]</li>
<<endif>>

<<if $npc.name eq "carlos">>
<li>[[carlos is here|carlos]]</li>
<<endif>>

<<if $npc.name eq "beast">>
<li>[[beast is here|beast]]</li>
<<endif>>

<li>[[leave|dawg][$npc.present = false]]</li>

</ul>

/%a determine amount of sleep %/

<<set $dawg.sleep to random(0, 13)>>

/%a update clocks based on sleep %/

<<set $time.clock += $dawg.sleep, $time.hourSeason += $dawg.sleep>>

/%a fix time of day after sleeping %/

<<if $dawg.sleep > 0>>
<<set $time.phases += 1>>
<<elseif $dawg.sleep > 3>>
<<set $time.phases += 2>>
<<elseif $dawg.sleep > 6>>
<<set $time.phases += 3>>
<<elseif $dawg.sleep > 12>>
<<set $time.phases += 4>>
<<endif>>

/%a sleep healing %/

<<set $dawg.health += ($dawg.sleep / 2), $dawg.stamina += ($dawg.sleep / 2)>>

/%a correct for health and stamina overruns %/

<<if $dawg.health > $dawg.maxHealth>>
<<set $dawg.health = $dawg.maxHealth>>
<<endif>>

<<if $dawg.stamina > $dawg.maxStamina>>
<<set $dawg.stamina = $dawg.maxStamina>>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a print sleep flavor text %/

<<if $dawg.sleep eq 0>>
<p><<print $dawg.name>> doesn't sleep.</p>
<<elseif $dawg.sleep eq 1>>
<p><<print $dawg.name>> sleeps an hour.</p>
<<elseif $dawg.sleep gt 1>>
<p><<print $dawg.name>> sleeps <<print $dawg.sleep>> hours.</p>
<<endif>>

<ul>
<li>[[wake|dawg][$dawg.dispo = "waking"]]</li>
/%a check for dreams %/
<<set $dawg.dream to random(1, 2)>>
<<if $dawg.dream eq 1>>
<li>[[dream...|dreaming]]</li>
<<endif>>
</ul>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() gt 1>>
<p><<print either("been here before...","this is the time...","this is the place...")>></p>
<<endif>>

<<if visited() gt 2>>
<p><<print either("...smelled on the wind...","...seen in the sun...","...touched to say hello...")>></p>
<<endif>>

<<if visited() gt 4>>
<<print either("", "", "")>>
<<endif>>

<<if visited() gt 6>>
<<print either("", "", "")>>
<<endif>>

<ul>
<li>[[what?!|dawg]]</li>
</ul>

<p>lived <<print $time.clock>> hours in the wasteland</p>
 
<p>
<<if $dawg.bodycount eq 0>>
never tasted blood.
<<elseif $dawg.bodycount eq 1>>
killed one wastelander.
<<elseif $dawg.bodycount gte 2>>
killed <<print $dawg.bodycount>> wastelanders.
<<endif>>
</p>

<ul>
<li>[[return|dawg][$dawg.dispo = "thinking"]]</li>
</ul>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a remember...                                  %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<p>lived <<print $time.clock>> hours in the wasteland</p>
 
<p>
<<if $dawg.bodycount eq 0>>
never tasted blood.
<<elseif $dawg.bodycount eq 1>>
killed one wastelander.
<<elseif $dawg.bodycount gte 2>>
killed <<print $dawg.bodycount>> wastelanders.
<<endif>>
</p>

<p><<print ($dawg.notoriety - 1) * 20>> people know your name.</p>

<p>visited <<print $env.log>>.</p>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather debug                                %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<p>
<<print $time.season>>
<br>
<<print $weatherChance.cold>> cold, 
<<print $weatherChance.cool>> cool, 
<<print $weatherChance.mild>> mild, 
<<print $weatherChance.warm>> warm, 
<<print $weatherChance.hot>> hot, 
<<print $weatherChance.scorching>> scorching. 
<br>
<<print $weatherChance.rain>> rain, 
<<print $weatherChance.snow>> snow. 
<br>
<<print $weatherChance.calm>> calm, 
<<print $weatherChance.breezy>> breezy, 
<<print $weatherChance.windy>> windy, 
<<print $weatherChance.gusty>> gusty. 
<br>
<<print $weatherChance.clear>> clear, 
<<print $weatherChance.hazy>> hazy, 
<<print $weatherChance.cloudy>> cloudy, 
<<print $weatherChance.overcast>> overcast. 
</p>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a dawg stats debug panel                       %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<div class=""><h1><<print $dawg.name>></h1><ul><li><<print $dawg.health>> health</li><li><<print $dawg.stamina>> stamina</li><li><<print $dawg.agility>> agility</li><li><<print $dawg.aggression>> aggression</li><li><<print $dawg.curiosity>> curiosity</li><li><<print $dawg.boldness>> boldness</li><li><<print $dawg.notoriety>> notoriety</li><li><<print $time.clock>> time total</li><li><<print $time.hour>> time of day</li><li><<print $time.hourSeason>> time of season</li></ul></div>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a bandit stats debug panel                     %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<div class=""><h1><<print $bandit.name>></h1><ul><li><<print $bandit.health>> health</li><li><<print $bandit.stamina>> stamina</li><li><<print $bandit.agility>> agility</li><li><<print $bandit.aggression>> aggression</li><li><<print $bandit.curiosity>> curiosity</li><li><<print $bandit.boldness>> boldness</li><li><<print $bandit.friendliness>> friendliness</li><li><<print $checkFriends>> adjusted</li><li><<print $checkInitiative>> initiative</li></ul></div>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<ul>
<li>[[advance one month|dawg][$time.clock += 719]]</li>
<li>[[advance one week|dawg][$time.clock += 167]]</li>
<li>[[advance one day|dawg][$time.clock += 23]]</li>
<li>[[return to the wasteland|dawg]]</li>
</ul>


<<set $timeclock = random(1, 720)>>
<p>hours : <<print $timeclock>></p>

<<set $timeday = $timeclock / 24>>
<p>days : <<print $timeday>></p>

<<set $timemonth = $timeday / 30>>
<p>months : <<print $timemonth>></p>

<p>
<<if $timeclock % 720 lt 12>>new
<<elseif $timeclock % 720 gt 12 and $timeclock % 720 lt 168>>waxing crescent
<<elseif $timeclock % 720 gt 168 and $timeclock % 720 lt 192>>first quarter
<<elseif $timeclock % 720 gt 192 and $timeclock % 720 lt 348>>waxing gibbous
<<elseif $timeclock % 720 gt 348 and $timeclock % 720 lt 372>>full
<<elseif $timeclock % 720 gt 372 and $timeclock % 720 lt 538>>waning gibbous
<<elseif $timeclock % 720 gt 538 and $timeclock % 720 lt 552>>last quarter
<<elseif $timeclock % 720 gt 552 and $timeclock % 720 lt 708>>waning crescent
<<elseif $timeclock % 720 gt 708>>new
<<endif>>
 moon</p>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

<<if $timeclock % 720 lt 7.5>>
waxing crescent
<<endif>>

180 = first quarter moon
360 = full
540 = last quarter
720 = new

lunar cycles 
30 day clock 
modulo 30? 
phases, divided by 4-8 
night visibility

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $time = {
	season: "",
	seasonCount: ""
}>>

<<set $time.seasonCount to either("0", "1", "2", "3")>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather variables                            %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $weatherChance = {

	temp: "",
	cold: "",
	cool: "",
	mild: "",
	warm: "",
	hot: "",
	scorching: "",

	precip: "",
	rain: "",
	snow: "",

	wind: "",
	calm: "",
	breezy: "",
	windy: "",
	gusty: "",

	sky: "",
	clear: "",
	hazy: "",
	cloudy: "",
	overcast: ""

}>>

<<set $weather = {

	tempCount: "",
	temp: "",
	precipCount: "",
	precip: "",
	windCount: "",
	wind: "",
	skyCount: "",
	sky: ""

}>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather probabilities                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a weather chance randomization %/

<<set $weatherChance.temp to random (1, 100)>>
<<set $weatherChance.precip to random (0, 100)>>
<<set $weatherChance.wind to random (1, 100)>>
<<set $weatherChance.sky to random (1, 100)>>

/%a number of expected days of weather per season %/

<<if $time.seasonCount eq 0>>
	<<set $time.season = "spring">>
	<<set $weatherChance = {
		cold: 0,
		cool: 14,
		mild: 36,
		warm: 19,
		hot: 22,
		scorching: 0,
		rain: 6,
		snow: 1,
		calm: 0,
		breezy: 66,
		windy: 11,
		gusty: 15,
		clear: 51,
		hazy: 5,
		cloudy: 15,
		overcast: 10
	}>>

<<elseif $time.seasonCount eq 1>>
	<<set $time.season = "summer">>
	<<set $weatherChance = {
		cold: 0,
		cool: 0,
		mild: 0,
		warm: 1,
		hot: 12,
		scorching: 78,
		rain: 11,
		snow: 1,
		calm: 53,
		breezy: 12,
		windy: 12,
		gusty: 15,
		clear: 55,
		hazy: 5,
		cloudy: 14,
		overcast: 4
	}>>

<<elseif $time.seasonCount eq 2>>
	<<set $time.season = "autumn">>
	<<set $weatherChance = {
		cold: 0,
		cool: 12,
		mild: 22,
		warm: 22,
		hot: 35,
		scorching: 1,
		rain: 8,
		snow: 2,
		calm: 59,
		breezy: 32,
		windy: 1,
		gusty: 1,
		clear: 57,
		hazy: 4,
		cloudy: 12,
		overcast: 9
	}>>

<<elseif $time.seasonCount eq 3>>
	<<set $time.season = "winter">>
	<<set $weatherChance = {
		cold: 52,
		cool: 38,
		mild: 1,
		warm: 0,
		hot: 0,
		scorching: 0,
		rain: 5,
		snow: 9,
		calm: 80,
		breezy: 10,
		windy: 0,
		gusty: 0,
		clear: 57,
		hazy: 3,
		cloudy: 12,
		overcast: 12
	}>>

<<endif>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather debug                                %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<p>
<<print $time.season>>
<br>
<<print $weatherChance.cold>> cold, 
<<print $weatherChance.cool>> cool, 
<<print $weatherChance.mild>> mild, 
<<print $weatherChance.warm>> warm, 
<<print $weatherChance.hot>> hot, 
<<print $weatherChance.scorching>> scorching. 
<br>
<<print $weatherChance.rain>> rain, 
<<print $weatherChance.snow>> snow. 
<br>
<<print $weatherChance.calm>> calm, 
<<print $weatherChance.breezy>> breezy, 
<<print $weatherChance.windy>> windy, 
<<print $weatherChance.gusty>> gusty. 
<br>
<<print $weatherChance.clear>> clear, 
<<print $weatherChance.hazy>> hazy, 
<<print $weatherChance.cloudy>> cloudy, 
<<print $weatherChance.overcast>> overcast. 
</p>




<<set $weatherChance.temperature = $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot + $weatherChance.scorching>>

<<set $weatherChance.precipitation = $weatherChance.rain + $weatherChance.snow>>

<<set $weatherChance.wind = $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy + $weatherChance.gusty>>

<<set $weatherChance.sky = $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy + $weatherChance.overcast>>


<p>
<<print $weatherChance.temperature>> temperature chance, 
<<print $weatherChance.precipitation>> precipitation chance, 
<<print $weatherChance.wind>> wind chance, 
<<print $weatherChance.sky>> sky chance.
</p>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather descriptors                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a temperature descriptors %/

<<if $weather.tempCount>>
<<set $weather.temp = "cold">>
<<elseif>>
<<set $weather.temp = "cool">>
<<elseif>>
<<set $weather.temp = "mild">>
<<elseif>>
<<set $weather.temp = "warm">>
<<elseif>>
<<set $weather.temp = "hot">>
<<elseif>>
<<set $weather.temp = "scorching">>
<<endif>>

/%a precipitation descriptors %/

<<if $weather.precipCount>>
<<set $weather.precip = "">>
<<elseif>>
<<set $weather.precip = "rain">>
<<elseif>>
<<set $weather.precip = "snow">>
<<endif>>

/%a wind descriptors %/

<<if $weather.windCount>>
<<set $weather.wind = "calm">>
<<elseif>>
<<set $weather.wind = "breezy">>
<<elseif>>
<<set $weather.wind = "windy">>
<<elseif>>
<<set $weather.wind = "gusty">>
<<endif>>

/%a sky descriptors %/

<<if $weather.skyCount>>
<<set $weather.sky = "clear">>
<<elseif>>
<<set $weather.sky = "hazy">>
<<elseif>>
<<set $weather.sky = "cloudy">>
<<elseif>>
<<set $weather.sky = "overcast">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather output                               %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<p>
<<print $weather.sky>>, <<print $weather.temp>>. 
<<print $weather.wind>> <<print $weather.precip>>.
</p>




<p>
<<print ($weatherChance.hazy / (2191 / 24)) * 100>>% chance.hazy
</p>

<<set $time = {
	season: "",
	seasonCount: ""
}>>
<<set $weather = {
sky: ""
}>>
<<set $time.seasonCount to either("0", "1", "2", "3")>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather probabilities                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a number of expected days of weather per season %/

<<if $time.seasonCount eq 0>>
	<<set $time.season = "spring">>
	<<set $weatherChance = {
		cold: 0,
		cool: 14,
		mild: 36,
		warm: 19,
		hot: 22,
		scorching: 0,
		rain: 6,
		snow: 1,
		calm: 0,
		breezy: 66,
		windy: 11,
		gusty: 15,
		clear: 51,
		hazy: 5,
		cloudy: 15,
		overcast: 10
	}>>

<<elseif $time.seasonCount eq 1>>
	<<set $time.season = "summer">>
	<<set $weatherChance = {
		cold: 0,
		cool: 0,
		mild: 0,
		warm: 1,
		hot: 12,
		scorching: 78,
		rain: 11,
		snow: 1,
		calm: 53,
		breezy: 12,
		windy: 12,
		gusty: 15,
		clear: 55,
		hazy: 5,
		cloudy: 14,
		overcast: 4
	}>>

<<elseif $time.seasonCount eq 2>>
	<<set $time.season = "autumn">>
	<<set $weatherChance = {
		cold: 0,
		cool: 12,
		mild: 22,
		warm: 22,
		hot: 35,
		scorching: 1,
		rain: 8,
		snow: 2,
		calm: 59,
		breezy: 32,
		windy: 1,
		gusty: 1,
		clear: 57,
		hazy: 4,
		cloudy: 12,
		overcast: 9
	}>>

<<elseif $time.seasonCount eq 3>>
	<<set $time.season = "winter">>
	<<set $weatherChance = {
		cold: 52,
		cool: 38,
		mild: 1,
		warm: 0,
		hot: 0,
		scorching: 0,
		rain: 5,
		snow: 9,
		calm: 80,
		breezy: 10,
		windy: 0,
		gusty: 0,
		clear: 57,
		hazy: 3,
		cloudy: 12,
		overcast: 12
	}>>

<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather chance randomization                 %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a temperature chance %/

<<set $weatherChance.temp = $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot + $weatherChance.scorching>>
<<set $weatherChance.tempRoller to random(1, $weatherChance.temp)>>

/%a precipitation chance %/

<<set $weatherChance.precip = $weatherChance.clear + $weatherChance.rain + $weatherChance.snow>>
<<set $weatherChance.precipRoller to random(1, $weatherChance.precip)>>

/%a wind chance %/

<<set $weatherChance.wind = $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy + $weatherChance.gusty>>
<<set $weatherChance.windRoller to random(1, $weatherChance.wind)>>

/%a sky chance %/

<<set $weatherChance.sky = $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy + $weatherChance.overcast>>
<<set $weatherChance.skyRoller to random(1, $weatherChance.sky)>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather descriptors                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a temperature descriptors %/

<<if $weatherChance.tempRoller lte $weatherChance.cold>>
<<set $weather.temp = "cold">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool>>
<<set $weather.temp = "cool">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild>>
<<set $weather.temp = "mild">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm>>
<<set $weather.temp = "warm">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot>>
<<set $weather.temp = "hot">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot>>
<<set $weather.temp = "scorching">>
<<endif>>

/%a precipitation descriptors %/

<<if $weatherChance.precipRoller lte $weatherChance.clear>>
<<set $weather.precip = "dry">>
<<elseif $weatherChance.precipRoller gt $weatherChance.clear and $weatherChance.precipRoller lte $weatherChance.clear + $weatherChance.rain>>
<<set $weather.precip = "rain">>
<<elseif $weatherChance.precipRoller gt $weatherChance.clear + $weatherChance.rain>>
<<set $weather.precip = "snow">>
<<endif>>

/%a wind descriptors %/

<<if $weatherChance.windRoller lte $weatherChance.calm>>
<<set $weather.wind = "calm">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm and $weatherChance.windRoller lte $weatherChance.calm + $weatherChance.breezy>>
<<set $weather.wind = "breezy">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm + $weatherChance.breezy and $weatherChance.windRoller lte $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy>>
<<set $weather.wind = "windy">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy>>
<<set $weather.wind = "gusty">>
<<endif>>

/%a sky descriptors %/

<<if $weatherChance.skyRoller lte $weatherChance.clear>>
<<set $weather.sky = "clear">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear and $weatherChance.skyRoller lte $weatherChance.clear + $weatherChance.hazy>>
<<set $weather.sky = "hazy">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear + $weatherChance.hazy and $weatherChance.skyRoller lte $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy>>
<<set $weather.sky = "cloudy">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy>>
<<set $weather.sky = "overcast">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a weather output                               %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<p>
<<print $weather.temp>>. <<print $weather.sky>>. <<print $weather.wind>>. <<print $weather.precip>>.
</p>

add classes to spans, create persistent UI space with css trickery 
layers of dog for each dispo 
weather, light, moon, interactions 

<p>beast doesn't move.</p>

<ul>
<li>[[leave|dawg][$npc.present = false]]</li>
</ul>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() eq 1>>
<p>rose eyes <<print $dawg.name>>.</p>

<p class="rose">"Hello there. What's your name?"</p>

<ul>
<li>[[pant|rose][$dawg.dispo = "panting"]]</li>
<li>[[bark|rose][$dawg.dispo = "barking"]]</li>
<li>[[growl|rose][$dawg.dispo = "growling"]]</li>
</ul>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() eq 2>>

<<if $dawg.dispo is "panting">>
<p class="rose">"Well aren't you a sweetie. You want this?"</p>

<p>rose offers a treat. it smells good, like fresh smoky hide and salt.</p>

<ul>
<li>[[take treat|rose][$dawg.health += 1, $dawg.dispo = "snacking", $npc.present = false]]</li>
<li>[[leave|dawg][$dawg.dispo = "leaving", $npc.present = false]]</li>
</ul>

<<elseif $dawg.dispo is "barking">>
<p class="rose">"Now no need for that. You hungry?"</p>

<p>rose offers a treat. it smells good, like fresh smoky hide and salt.</p>

<ul>
<li>[[take treat|rose][$dawg.health += 1, $dawg.dispo = "snacking", $npc.present = false]]</li>

<li>[[leave|dawg][$dawg.dispo = "leaving", $npc.present = false]]</li>
</ul>

<<elseif $dawg.dispo is "growling">>
<p class="rose">"There ain't no call for that. Get on outta here!"</p>

<ul>
<li>[[leave|dawg][$dawg.dispo = "leaving", $npc.present = false]]</li>
</ul>
<<endif>>

<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() eq 3>>
<p class="rose">"Bye for now."</p>

<ul>
<li>[[leave|dawg][$dawg.dispo = "leaving", $npc.present = false]]</li>
</ul>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() eq 4>>
<p>rose extends an open hand to <<print $dawg.name>>. it smells like herbs and dirt and spice and blood and sulphur.</p>

<p class="rose">"I am gathering ingredients for my special soup. Will you help me?"</p>

<ul>
<li>[[sniff bowl|dog with two bones]]</li>
<li>[[bite rose|dawg][$npc.present = false]]</li>
<li>[[leave|dawg][$npc.present = false]]</li>
</ul>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() gt 4>>
<p>rose stares blankly into the distance.</p>

<ul>
<li>[[leave|dawg][$dawg.dispo = "confused", $npc.present = false]]</li>
</ul>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<print $npc.name>> shows you his wares. nothing interests you. 

[[leave|dawg][$npc.present = false]]

<p class="rose">"Take the road. The road will lead you to a garden. You will meet Joshua there. He will give you bones. Take this letter to Joshua. Bring me back the bones. If you do, I will share my soup with you."</p>

<ul>
<li>[[take letter|dawg][$quest.active = "bones", $dawg.dispo = "questing", $npc.present = false]]</li>
<li>[[leave|dawg][$quest.active = "none", $dawg.dispo = "leaving" $npc.present = false]]</li>
</ul>

quests based on location. find the nearest refinery, do X, get Y

quest.giver
quest.giverLocation
quest.reward

level up based on stats
if curiosity gt 4
get bonus
elseif curiosity gt 9
bigger bonus 
else
no bonus
etc


chapters 
semi defined sequence of environments and encounters. 
unlock upgrades 
powers during combat 
insert lists, script injection 
if dawg. enhancement gt 0
enable menu

leveled up

after taking n damage and sleeping n hours 
after n visits to dawg page
after n seasons

time travel to advance seasons 
freeze dawg for hours to upgrade? 

cryostasis, have to be in safe place 
environment types need flags for this math 

maul rage, kill errthang

full moon werewolf powers


run fast, environment selection maybe 

have to do something serious to unlock this 

 
if $dawg.dispo eq "wagging" 
if $dawg.dispo eq "jumping" 
if $dawg.dispo eq "cowering" 

if $dawg.dispo eq "growling" 
if $dawg.dispo eq "barking" 
if $dawg.dispo eq "howling" 
if $dawg.dispo eq "whining" 

if $dawg.dispo eq "biting" 
if $dawg.dispo eq "scratching" 


link to combat flow as needed
based on reactions 



































/%a%%%%%%%%


the
dawg
         %/

/%a<h1 class="top">[[1D0G|dawg]]</h1>
[img[1dawg][dawg]]%/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a               instantiate the universe               %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a clocks %/
<<set $time = { clock: random(0,8764) }>>
<<set $time.alive = 0>>

/%a variables %/
<<set $exterior = { style: "endless" }>>
<<set $weather = { sky: "void" }>>


/%a import creation %/
<<display "time">>
<<display "firmament">>
<<display "season">>
<<display "weather">>
<<display "exterior">>

/% update checks %/
<<display "visibility">>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                    create dawg                       %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $dawg = {

	name: "dawg",
	doing: "appearing",

	health: random(2, 10),
		healthMax: random(8, 12),
	stamina: random(1, 8),
		staminaMax: random(6, 10),
	agility: random(1, 8),
		agilityMax: random(6, 10),
	aggression: random(1, 6),
	curiosity: random(1, 6),
	boldness: random(1, 6),

	notoriety: 1,
	bodycount: 0,
	sleep: 0,

}>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/



/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                                                      %/
/%a                                                      %/
/%a                        print                         %/
/%a                                                      %/
/%a                                                      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<h1 class="top">1D0G</h1>

<<print $dawg.name>> <<print $dawg.doing>>.
 
<<print $exterior.style>> <<print $exterior.zone>>. 

<<print $time.season>> <<print $time.sun>>. 

<<print $weather.temp>>. <<print $weather.wind>>. <<print $weather.sky>>. 

<<if $time.astronomy eq true>><<print $time.moon>> moon.<<endif>>




[[*|debug]]

/%a assume dawg exists in the universe %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                         time                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $time.day = $time.clock % 24>>
<<set $time.month = $time.clock % 720>>
<<set $time.year = $time.clock % 8764>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                         sun                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if $time.day gte 0 and $time.day lte 5>>
	<<set $time.sun to "night">>
<<elseif $time.day gte 6 and $time.day lte 7>>
	<<set $time.sun to "dawn">>
<<elseif $time.day gte 8 and $time.day lte 11>>
	<<set $time.sun to "morning">>
<<elseif $time.day gte 12 and $time.day lte 15>>
	<<set $time.sun to "afternoon">>
<<elseif $time.day gte 16 and $time.day lte 19>>
	<<set $time.sun to "evening">>
<<elseif $time.day gte 20 and $time.day lte 21>>
	<<set $time.sun to "twilight">>
<<elseif $time.day gte 22 and $time.day lte 24>>
	<<set $time.sun to "night">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                        moon                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if $time.month gte 0 and $time.month lte 89>>
	<<set $time.moon = "new">>
<<elseif $time.month gte 90 and $time.month lte 179>>
	<<set $time.moon = "crescent">>
<<elseif $time.month gte 180 and $time.month lte 269>>
	<<set $time.moon = "first quarter">>
<<elseif $time.month gte 270 and $time.month lte 359>>
	<<set $time.moon = "gibbous">>
<<elseif $time.month gte 360 and $time.month lte 449>>
	<<set $time.moon = "full">>
<<elseif $time.month gte 450 and $time.month lte 539>>
	<<set $time.moon = "disseminating">>
<<elseif $time.month gte 540 and $time.month lte 629>>
	<<set $time.moon = "last quarter">>
<<elseif $time.month gte 630 and $time.month lte 720>>
	<<set $time.moon = "balsamic">>
<<endif>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                       season                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if $time.year gte 0 and $time.year lte 2191>>
	<<set $time.season to "summer">>
	<<set $weatherChance = {
		cold: 0, cool: 0, mild: 0, warm: 1, hot: 12, scorching: 78, 
		rain: 11, snow: 1,
		calm: 53, breezy: 12, windy: 12, gusty: 15,
		clear: 55, hazy: 5, cloudy: 14, overcast: 4
	}>>
<<elseif $time.year gte 2192 and $time.year lte 4382>>
	<<set $time.season to "autumn">>
	<<set $weatherChance = {
		cold: 0, cool: 12, mild: 22, warm: 22, hot: 35, scorching: 1,
		rain: 8, snow: 2,
		calm: 59, breezy: 32, windy: 1, gusty: 1,
		clear: 57, hazy: 4, cloudy: 12, overcast: 9
	}>>
<<elseif $time.year gte 4383 and $time.year lte 6572>>
	<<set $time.season to "winter">>
	<<set $weatherChance = {
		cold: 52, cool: 38, mild: 1, warm: 0, hot: 0, scorching: 0,
		rain: 5, snow: 9,
		calm: 80, breezy: 10, windy: 0, gusty: 0,
		clear: 57, hazy: 3, cloudy: 12, overcast: 12
	}>>
<<elseif $time.year gte 6573 and $time.year lte 8764>>
	<<set $time.season to "spring">>
	<<set $weatherChance = {
		cold: 0, cool: 14, mild: 36, warm: 19, hot: 22, scorching: 0,
		rain: 6, snow: 1,
		calm: 0, breezy: 66, windy: 11, gusty: 15,
		clear: 51, hazy: 5, cloudy: 15, overcast: 10
	}>>
<<endif>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                    temperature                       %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $weatherChance.temp = $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot + $weatherChance.scorching>>
<<set $weatherChance.tempRoller to random(1, $weatherChance.temp)>>

<<if $weatherChance.tempRoller lte $weatherChance.cold>>
	<<set $weather.temp = "cold">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool>>
	<<set $weather.temp = "cool">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild>>
	<<set $weather.temp = "mild">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm>>
	<<set $weather.temp = "warm">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm and $weatherChance.tempRoller lte $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot>>
	<<set $weather.temp = "hot">>
<<elseif $weatherChance.tempRoller gt $weatherChance.cold + $weatherChance.cool + $weatherChance.mild + $weatherChance.warm + $weatherChance.hot>>
	<<set $weather.temp = "scorching">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     precipitation                    %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $weatherChance.precip = $weatherChance.clear + $weatherChance.rain + $weatherChance.snow>>
<<set $weatherChance.precipRoller to random(1, $weatherChance.precip)>>

<<if $weatherChance.precipRoller lte $weatherChance.clear>>
	<<set $weather.precip = "dry">>
<<elseif $weatherChance.precipRoller gt $weatherChance.clear and $weatherChance.precipRoller lte $weatherChance.clear + $weatherChance.rain>>
	<<set $weather.precip = either("rain", "thunderstorm")>>
<<elseif $weatherChance.precipRoller gt $weatherChance.clear + $weatherChance.rain>>
	<<set $weather.precip = either("snow", "blizzard")>>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                         wind                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $weatherChance.wind = $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy + $weatherChance.gusty>>
<<set $weatherChance.windRoller to random(1, $weatherChance.wind)>>

<<if $weatherChance.windRoller lte $weatherChance.calm>>
	<<set $weather.wind = "calm">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm and $weatherChance.windRoller lte $weatherChance.calm + $weatherChance.breezy>>
	<<set $weather.wind = "breezy">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm + $weatherChance.breezy and $weatherChance.windRoller lte $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy>>
	<<set $weather.wind = "windy">>
<<elseif $weatherChance.windRoller gt $weatherChance.calm + $weatherChance.breezy + $weatherChance.windy>>
	<<set $weather.wind = "gusty">>
<<endif>>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                         sky                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $weatherChance.sky = $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy + $weatherChance.overcast>>
<<set $weatherChance.skyRoller to random(1, $weatherChance.sky)>>

<<if $weatherChance.skyRoller lte $weatherChance.clear>>
	<<set $weather.sky = "clear">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear and $weatherChance.skyRoller lte $weatherChance.clear + $weatherChance.hazy>>
	<<set $weather.sky = "hazy">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear + $weatherChance.hazy and $weatherChance.skyRoller lte $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy>>
	<<set $weather.sky = "cloudy">>
<<elseif $weatherChance.skyRoller gt $weatherChance.clear + $weatherChance.hazy + $weatherChance.cloudy>>
	<<set $weather.sky = "overcast">>
<<endif>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     visibility                       %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if $time.day gte 20 or $time.day lte 6>>
	<<if $weather.sky eq "clear" or $weather.sky eq "hazy">>
		<<set $time.astronomy = true >>
	<<endif>>
<<else>>
	<<set $time.astronomy = false >>
<<endif>>


/%a%%%%%%%%


core
loops
           %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                        dawg                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a dawg health %/
/%a sleeping %/
/%a dreaming %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                        time                          %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a clock %/
/%a sun %/
/%a day %/
/%a moon %/
/%a season %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     environment                      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a weather %/
/%a sky %/
/%a  %/
/%a  %/
/%a  %/
/%a  %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                      location                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a type %/
/%a zone %/
/%a style %/
/%a here %/
/%a next %/
/%a log %/
/%a  %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                        quest                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a check for active quest %/
/%a show quest details %/
/%a  %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                        npc                           %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a check for npc %/
/%a show npc text %/
/%a  %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     encounter                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a chance %/
/%a count %/
/%a class %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                                                      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a  %/
/%a  %/
/%a  %/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/








/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                                              %/
/%a                 outputs                      %/
/%a                                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<h1 class="uppercase"><<print $env.here>>.</h1>

<p>
<<print $weather.wind>>, <<print $weather.sky>>, <<print $weather.temp>> <<print $time.season>> <<print $time.light>>. 

<<if $weather.precip is not "dry">>
<<print $weather.precip>>. 
<<endif>>

<<if $time.phases gt 3 or $time.phases lt 2>>
<<if $weather.sky eq "clear" or $weather.sky eq "hazy">>
<<print $time.moon>> moon. 
<<endif>>
<<endif>>

<<print $dawg.wounds>> <<print $dawg.name>> <<print $dawg.dispo>>. 

<<if $encounter.chance gt 0 and $npcHere.present eq true>>
<<print $npcHere.name>> the <<print $npcHere.class>> is here.
<<endif>>

</p>

<ul>
<li>[[walk|environment][$dawg.dispo = "exploring", $npcHere.present = false]]</li>
<<if visited() gt 1>>
<<if $encounter.chance gt 0>>
<li>[[encounter|encounter][$dawg.dispo = "seeking"]]</li>
<<endif>>

<<if $npcHere.civilized eq true>>
<<if $time.phases gte 2 and $time.phases lte 4>>
<li>[[shop]]</li>
<<endif>>
<<endif>>
<<if $npcHere.present eq true>>
<li>[[socialize]]</li>
<<endif>>
<<endif>>
<li>[[rest|sleep][$dawg.dispo = "sleeping"]]</li>
<<if visited() gt 2>>
<li>[[remember][$dawg.dispo = "thinking"]]</li>
<<endif>>
/%a<li>[[Ø|debug][$dawg.dispo = "in a cyber trance"]]</li>%/
</ul>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/



/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     environment                      %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/


<<set $env = {
	type: "road",
	zone: "highway",
	style: "dusty",
	here: "dusty highway",
	next: "",
	log: "dusty highway"
}>>



/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     encounters                       %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/




<<if $quest.active eq true>>

	<<if $weather.sky eq "clear" or $weather.sky eq "hazy">>
		<<set $time.astronomy = true >>
	<<endif>>

<<else>>

	<<set $time.astronomy = false >>

<<endif>>


DEBUG ####################

seed time <<print $time.clock>>. 
it is <<print $time.day>>:00 in the wasteland. 
<<print $time.month>> hours into this month. 
<<print $time.year>> hours into this year. 
lived <<print $time.alive>> hours.

[[>restart|Start]]





/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                                              %/
/%a                 outputs                      %/
/%a                                              %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<if visited() eq 1>>
<p>leaving <<print $env.here>>.</p>
<<endif>>
<p><<print $dawg.dispo>> <<print $env.next>>. 
<<if $encounter.chance gt 0>>someoane is here.<<endif>></p>

<ul>

<li>[[keep walking|environment][$env.passing = $env.next, $time.clock += random(1,3)]]</li>

<li>[[stop here|dawg][$env.here = $env.next, $env.log += ", " +$env.next]]</li>

<<if $dawg.home eq true>>
<li>[[go home|home][$time.clock += random(1,12)]]</li>
<<endif>>

</ul>






/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     exterior                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $exterior.type = either("road", "wastes", "natural", "urban")>>

<<if $exterior.type is "road">>
	<<set $exterior.zone = either("highway", "trail", "path", "bridge", "sidewalk", "street", "ditch", "parking lot")>>
	<<set $exterior.style = either("dusty", "long", "cracked", "lonely")>>
<<elseif $exterior.type is "urban">>
	<<set $exterior.zone = either("farm", "ranch", "checkpoint", "suburbs", "downtown", "boardwalk", "market")>>
	<<set $exterior.style = either("gritty", "bustling", "crowded", "vacant","abandoned")>>
<<elseif $exterior.type is "natural">>
	<<set $exterior.zone = either("hill", "plain", "forest","pine forest","dense scrub","sparse scrub","canyon", "crater", "foothills", "mountain", "marsh", "lake", "river", "stream")>>
	<<set $exterior.style = either("wet", "dry", "dusty", "lonely", "wide")>>
<<elseif $exterior.type is "wastes">>
	<<set $exterior.zone = either("dust", "mud flats", "salt flats", "scrub", "battlefield", "sands", "dunes", "ashland")>>
	<<set $exterior.style = either("windy", "wide", "long", "lonely", "desolate", "ruined", "still")>>
<<endif>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     exteriors                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<display "exterior">>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                    interiors                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<display "interior">>

/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                    encounters                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/



/%a

CHECK FOR ACTIVE QUEST

CHECK FOR ZONE PORTAL

CHECK FOR NPC

CHECK FOR ENCOUNTER CHANCE
LOAD ENCOUNTER TYPE
SHOW LINK TO ENCOUNTER


<<set $env.next = $env.style + " " + $env.zone>>

<<set $encounter = {
	chance: random(0, 2),
	count: random(0, 5),
}>>

THINK MORE ABOUT QUESTS AND HOW THEY CAN BE UPDATED ELSEWHERE, THEN LOADED BASED ON CHECKS HERE

IF QUEST
IF NPC
KINDS OF ENCOUNTERS
INTERIOR / EXTERIOR
ALSO WIN STATES
\%/

/%a
notes: 

encounter type based on environment type 
humans, animals, machines 
different name classes

either bobcat, bear, 
either farmer, guard 
either sentry, drone
etc 

store individual log of environments to return and continue encounters?

%/



/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                     interior                         %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $interior.type to either("dwelling", "scary", "industrial", "portal")>>

<<if $interior.type is "dwelling">>
	<<set $interior.zone to either("farm", "ranch", "camp", "caravan", "lodge", "house", "mansion", "garden", "trailer", "rv", "wreck", "shacks", "radio station")>>
	<<set $interior.style to either("dusty", "cramped", "rundown", "old", "rusty" ,"overgrown")>>

<<elseif $interior.type is "scary">>
	<<set $interior.zone to either("cave", "nest", "sewer", "tunnel", "dungeon", "bunker", "hold", "basement")>>
	<<set $interior.style to either("dank", "dry", "wet", "black", "glistening", "reeking")>>

<<elseif $interior.type is "industrial">>
	<<set $interior.zone to either("mine", "oil well", "power plant", "steel mill", "refinery", "control room", "slum")>>
	<<set $interior.style to either("gritty", "smoky", "putrid", "hazy", "humid", "tense")>>

<<elseif $interior.type is "portal">>
	<<set $interior.zone to either("door", "grate", "vent", "gate", "hole")>>
	<<set $interior.style to either("dusty", "cramped", "old", "rusty","overgrown")>>


<<endif>>


/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/
/%a                        health                        %/
/%a%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%/

<<set $dawg.woundedness = $dawg.health / $dawg.maxHealth>>
<<if $dawg.woundedness lte 0.2>>
<<set $dawg.wounds = "beaten">>
<<elseif $dawg.woundedness lte 0.5>>
<<set $dawg.wounds = "exhausted">>
<<elseif $dawg.woundedness lte 0.7>>
<<set $dawg.wounds = "wounded">>
<<elseif $dawg.woundedness lte 0.9>>
<<set $dawg.wounds = "sore">>
<<elseif $dawg.woundedness eq 1>>
<<set $dawg.wounds = "healthy">>
<<endif>>


<<set $npc = { present: false }>>

/%a  spawn carlos %/
/%a  he's always open for business %/
<<if $env.zone is "shop">>
<<set $npc = {
	name: "carlos",
	type: "human",
	class: "trader",
	pronoun: "he",
	friendliness: 1,
	health: 4,
	stamina: 3,
	agility: 3,
	aggression: 2,
	curiosity: 4,
	boldness: 3,
	present: true,
	civilized: true,
}>>
<p class="carlos">¡!¡!??</p>
<<endif>>

/%a  spawn rose %/
/%a  sometimes you see her on the road %/
<<if $env.type is "road">>
<<set $npc = {
	name: "rose",
	pronoun: "she",
	type: "human",
	class: "wanderer",
	friendliness: 2,
	health: 9,
	stamina: 6,
	agility: 5,
	aggression: 3,
	curiosity: 4,
	boldness: 6,
	present: true
}>>
<p class="rose">!?<3¡!</p>
<<endif>>

/%a  spawn beast %/
/%a  never know where he'll be %/
<<if $env.type is "natural" or $env.type is "wasteland">>
<<set $npc = {
	name: "beast",
	pronoun: "he",
	type: "animal",
	class: "beast",
	friendliness: -1,
	health: 18,
	stamina: 6,
	agility: 4,
	aggression: 6,
	curiosity: 6,
	boldness: 0,
	present: true,
}>>
<p class="beast">?¿!!!!¡</p>
<<endif>>



<<if $quest.active eq true>>

<<if $quest.name eq "bones" and $env.zone eq "garden">>
<<set $npc = {
	name: "joshua",
	pronoun: "he",
	type: "human",
	class: "gardener",
	friendliness: 1,
	health: 6,
	stamina: 3,
	agility: 2,
	aggression: 3,
	curiosity: 6,
	boldness: 4,
	present: true
}>>
<<set $encounter.chance = 0>>
<p class="rose">?¿?!¿¡</p>
<<endif>>

<<endif>>





























/%a housekeeping %/

<<set
$time += 1>>
<<print $time>> hours

$envHere

$envNext

/%a%%%%%%%%%%%%%%%%%%%%%/
select a random environment type

set $envType either
"road, natural, wastes, urban, dwelling, scary,  industrial, "

/%a%%%%%%%%%%%%%%%%%%%%%/
select a thematic zone from environment type

if $envType = road
set $envZone either
"highway, trail, path, bridge, sidewalk, street, " 

elseif = urban
"suburbs, downtown, checkpoint, boardwalk, capitol, campus, shop, "

elseif = dwelling
"farm, ranch, camp, caravan, lodge, house, mansion, garden, trailer, rv, wreck, shacks, radiostation, "

elseif = natural 
"hill, plain, pine, canyon, crater, foothills, mountain, "

elseif = wastes
"dust, mud, salt, scrub, battlefield, sand, " 

elseif = industrial
"mine, oilwell, powerplant, steelmill, refinery, controlroom, slum, "

elseif = scary
"cave, nest, sewer, tunnel, dungeon, bunker, hold, basement, "

/%a%%%%%%%%%%%%%%%%%%%%%/

print $envType 
print $envZone

/%a%%%%%%%%%%%%%%%%%%%%%/

choose stylistic keywords based on zone

if $envZone = road
set $envVibe =
dusty, long, 

elseif = cave
dank, dry, wet, black, glistening, reeking, 

elseif = 

/%a%%%%%%%%%%%%%%%%%%%%%/

[[prony $envStyle $envType][set $envHere = $envType]] 





time

clock

days

moon

seasons

weather

environment
 
 
- interior 
- exterior 
- home
- unique

npc
 
- unique
- random 
- combat
- socializing 

quests
 
- chapters
-
random 










pipelines
environment
encounter
stats



npc.present 
npc.type
npc.home











time
-seasons 
-moon
weather
home
npc
combat
socializing 







npc
unique
random

npc.present 
npc.type
npc.home







song player 
play a song, music to something 


shopkeeper
treats and gossip 
quest giver


guard
parody of stock vanilla characters 
messes up the scripts 


rose
potential human companion 


vending machine 
nonverbal, makes noises 


login terminal
robot font


the beast
dirty font 
grudging respect


radio host

if env type eq "radio station" 



quest


bandits camped out in a lonely place 

if env.flavor eq "lonely" 

intimidation 
howl
scare them off
opportunity to kill
level up one stat
a little more scripted

get a thing 
carry it back, slimy, slightly gross, enthusiastic 
or bite

no not ok



let's talk
reactions 

randomness to a minimum, more invisible quiet intermediate actions 

body language 
scents 
wind dispersion 


visibility 
best at twilight, plus n points 






seed encounters on environment generation: 
set $env.encounterTimer random(0, 5)


something for environments and dawg passages:
if $env.encounterTimer gt 0

someone is here.
[[seek|encounter]]

else

no one is here. 
[[leave|dawg]] 

endif



put this somewhere at the end of encounters, maybe on exit links:
set $env.encounterTimer -= 1


on environment generation give option to stay 

housebuilding / crafting flows


weather based on $env.season
winter: cold, chilly, tepid, freezing
spring: warm, chilly, wet, clear
summer: hot, dry, muggy, clear
autumn: fresh, crisp, chilly, hot


hanging out somewhere, bring sticks, find mate, reproduce, decorations, trophies, 

human companion 

refractor bandit script to be helpful
add options for more than one on one combat 

things to do with your time 
more friendly / neutral options. 
lick, wag, scratch, bark, howl

link to combat flow
based on reactions 

store individual log of environments to return and continue encounters 

need an infinite encounter, permanent NPCs

store keeper 

maybe add an option on the main menu 

if encounter . permanent etc

encounter type based on environment type 

humans, animals, machines 

different name classes

either bobcat, bear, 
either farmer, guard 
either sentry, drone
etc

chapters 
semi defined sequence of environments and encounters. 
unlock upgrades 
powers during combat 
insert lists, script injection 
if dawg. enhancement gt 0
enable menu

leveled up

after taking n damage and sleeping n hours 
after n visits to dawg page
after n seasons

time travel to advance seasons 
freeze dawg for hours to upgrade? 

cryostasis, have to be in safe place 
environment types need flags for this math 

maul rage, kill errthang

full moon werewolf powers


run fast, environment selection maybe 

have to do something serious to unlock this 

 

lunar cycles 

30 day clock

time.day = time.clock / 24
modulo 30?
phases, divided by 4-8
night visibility


add classes to spans, create persistent UI space with css trickery 

layers of dog for each dispo 


weather, light, moon, interactions 


human minions

shopkeeper

add index for persistent entities 

entity.home, entity.npc
entity.companion
how to store new entities and keep old ones? 
return to locations? 

quests based on location. find the nearest refinery, do X, get Y

quest.giver
quest.giverLocation
quest.reward

level up based on stats
if curiosity gt 4
get bonus
elseif curiosity gt 9
bigger bonus 
else
no bonus
etc

encounters at home
bend chances about what spawns based on environment


if $dawg.dispo eq "wagging" 
if $dawg.dispo eq "scratching" 
if $dawg.dispo eq "jumping" 
if $dawg.dispo eq "howling" 
if $dawg.dispo eq "barking" 
if $dawg.dispo eq "growling" 
if $dawg.dispo eq "biting" 
if $dawg.dispo eq "whining" 
if $dawg.dispo eq "cowering" 
licking



 
reaction * notoriety 

faction alignment for flavor 


md biz

weather 

but even 

spaces



seed encounters on environment generation: 
set $env.encounterTimer random(0, 5)


something for environments and dawg passages:
if $env.encounterTimer gt 0

someone is here.
[[seek|encounter]]
[[leave|dawg]] 

else

no one is here. 
[[leave|dawg]] 

endif


put this somewhere at the end of encounters, maybe on exit links:
set $env.encounterTimer -= 1


on environment generation give option to stay 

housebuilding / crafting flows


weather based on $env.season
winter: cold, chilly, tepid, freezing
spring: warm, chilly, wet, clear
summer: hot, dry, muggy, clear
autumn: fresh, crisp, chilly, hot


hanging out somewhere, bring sticks, find mate, 

human companion 

refractor bandit script to be helpful
add options for more than one on one combat 

things to do with your time 
more friendly / neutral options. 
lick, wag, scratch, bark, howl

link to combat flow 

store individual log of environments to return and continue encounters 

need an infinite encounter, permanent NPCs

store keeper 

maybe add an option on the main menu 

if encounter . permanent etc

encounter type based on environment type 

humans, animals, machines 

different name classes

either bobcat, bear, 
either farmer, guard 
either sentry, drone
etc

chapters 
semi defined sequence of environments and encounters. 
unlock upgrades 
powers during combat 
insert lists, script injection 
if dawg. enhancement gt 0
enable menu

leveled up

after taking n damage and sleeping n hours 
after n visits to dawg page
after n seasons

time travel to advance seasons 
freeze dawg for hours to upgrade? 

cryostasis, have to be in safe place 
environment types need flags for this math 

maul rage, kill errthang


run fast, environment selection maybe 

have to do something serious to unlock this 

add house creation too 

add cooldown to sleeping?


time
weather
environment 

location
indoor environment 

visibility 

smellability
wind
dispersing scents 

persistent locations

quests 

health
dawg










npc.type

animal
human 
machine 

n
atypical mechanism 

strange attractors 









juan at the power plant 

carlos in the shop

rose on the road

joshua in the garden

dana at the radio station 

jesse with the rv

cecil at the bowling alley 

soda machine in the desert 

lilly in the mountains 

ginger in the lab

door lock at the bunker 

doctor with the caravan 



guard at the facility

guards everywhere 

dogs in the city 

in nature :
bears
bobcats
badgers
skunks 
armadillo 
deer
prarie dogs
mountain lions
antelope 
fox
snakes

at water
geese
ducks
frogs
beaver

npc class
animals ranked by class
nDn






