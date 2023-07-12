# Psitegrad's Status Effect Rebalance for Made in Abyss BSFD

A mod that aims to rebalance status effect in this game.  
The abyss should be an arduous environment for inexperienced or insufficiently prepared delvers.

Note that this is my personal preference, too often I find them easy to ignore as the penalty is relatively mild.  
Now there is an incentive to prepare for these lest the resources used to recover snowballs later.  
Of course you could just not get hit 😉


### Description

+ Doubled blue poison hunger penalty.  
[The very hunger for discovery that drived you into further depths, is now the one eating at you.]

+ Altered red poison effect, no longer an infinite Dot but hits hard enough that it will impair resources if not treated before the body purges it.  
[With your own vitality abandoning you, will your persist with grit or wisdom ?]

+ Slightly increased effects of red and blue poisons on enemy.  
[In time you will master the weapon used against you.]

+ Merged Heatnixx' Curse Balancing Mod, as it would have created conflicts.
  
+ Reduced curse effect time in layers that you've mastered.  
[Those who braved the Abyss long enough to adorn new whistles find their very body twisted by it, yet amidst hardships blessings overflow.]

+ Increased curse effect time in layers lower than you should be in.  
[The search parties gave up long ago, yet your dead companions whispers will follow long after.]

+ Gradual increase in curse effects penalties the deeper you go instead of fixed values shared across some layers (keep in mind each layer has a cap). The curve is gentler until Layer 4.  
[The ceilings of the past will be the floors of the future.]


### Compatibility
Will conflict with any mods that edit the following files:
+ BP_AbnormalInfomation
+ BP_CharaStatusSetting
+ DT_AbnormalSetting
+ DT_EnemyAbnormalSetting


### Download
[https://github.com/Psitegrad/Psitegrad-Status-Effect-Rebalance](https://github.com/Psitegrad/Psitegrad-Status-Effect-Rebalance/releases/tag/v1.0)


### How to Install
+ Download the file
+ Navigate to C:\Program Files (x86)\Steam\steamapps\common\MadeInAbyss-BSFD\MadeInAbyss-BSFD\Content\Paks
+ Paste the file
+ Make sure the file's name is MadeInAbyss-BSFD-WindowsNoEditor_<Anything>_P.pak; with <Anything> being a number, a name or whatever.  
(I did this for you already, but if you know what you're doing feel free to change it !)
+ Enjoy !


### How to uninstall
+ Navigate to `C:\Program Files (x86)\Steam\steamapps\common\MadeInAbyss-BSFD\MadeInAbyss-BSFD\Content\Paks`
+ Remove my mod .pak file
+ Done !


### Full Changelog

*Player Abnormal Status Effects:*

+ Blue Poison:  
Vanilla: 200% hunger consumption until cured  
Modded: 400% hunger consumption & walking speed reduced by 10% until cured

+ Red Poison:  
Vanilla: 1% HP loss every 2 seconds until 1 HP left or cured  
Modded: 30% total HP loss over 20 seconds, ticks every second until 1 HP lef or effect time has elapsed

+ Orb Piercer Poison (Untouched):  
1% HP loss every 2 seconds until 1 HP left or cured & 400% hunger consumption & speed reduced by 10% until death or cured

+ Paralysis:  
Vanilla: Paralysed for 5 seconds  
Modded: Paralysed for 4 seconds

+ Arm Injury:  
Vanilla: Arm incapacited for 30 seconds  
Modded: Arm incapacited for 60 seconds

+ Leg Injury  
Vanilla: Leg incapacited for 30 seconds & speed reduced by 50%  
Modded: Leg incapacited for 60 seconds & speed reduced by 50%

*Enemy Abnormal Status Effects:*

+ Blue Poison:  
Vanilla: 1% HP loss until death or cured  
Modded: 1,5% HP loss until death or cured

+ Red Poison:  
Vanilla: 1% HP loss until death or cured  
Modded: 1,5% HP loss until death or cured

+ Orb Piercer Poison (Untouched):  
No effect ?

+ Paralysis (Untouched):

*Abyss Curse Duration (in seconds):*

+ Red Whistle:  
Layer 1: Left at 10  
Layer 2: From 10 to 15  
Layer 3: From 10 to 20  
Layer 4: From 10 to 20  
Layer 5: From 10 to 20

+ Blue Whistle:
Layer 1: From 8 to 7  
Layer 2: Left at 10  
Layer 3: From 10 to 15  
Layer 4: From 10 to 20  
Layer 5: From 10 to 20

+ Moon Whistle:
Layer 1: From 6 to 3  
Layer 2: From 8 to 6  
Layer 3: Left at 8  
Layer 4: From 10 to 12  
Layer 5: From 10 to 15

+ Black Whistle:
Layer 1: From 4 to 1  
Layer 2: From 6 to 3  
Layer 3: Left at 6  
Layer 4: Left at 8  
Layer 5: Left at 10

+ White Whistle:  
Layer 1: From 4 to 1  
Layer 2: From 4 to 1  
Layer 3: From 4 to 3  
Layer 4: Left at 6  
Layer 5: Left at 8


*Curse of the abyss effects (Keep in mind there is a cap per layer):*

+ Layer 1 (Cap: 50% HP left):  
Life Reduction: 0  
Satiety Reduction: Left at 25 points reduction

+ Layer 2 (Cap: 40% HP left):  
Life Reduction: 0  
Satiety Reduction: From 50 to 31,25 points reduction

+ Layer 3 (Cap: 30% HP left):  
Life Reduction: 0  
Satiety Reduction: From 50 to 39,1 points reduction

+ Layer 4 (Cap: 20% HP left):  
Life Reduction: From 200 to 250 points reduction  
Satiety Reduction: From 50 to 48,83 points reduction

+ Layer 5 (Cap: 10% HP left):  
Life Reduction: From 400 to 500 points reduction  
Satiety Reduction: From 50 to 61 points reduction
