# let-me-target

Version: 0.2.13

Auto-lockon module.


## Info
 * Auto-lock members from the lowest to highest HP
    * Priest and Mystic basic heal
    * Healing Immersion
 * Auto-lock up to 4 members to cleanse using smart detection
    * Mystic cleanse
    * Can Toggle on/off by command and config file (default: on)
 * Auto-lock boss and finish the skill automatically
    * Arrow Volley and Flaming Barrage (DPS)
    * Energy Stars / Plague / Ishara's Lullaby (Priest)
    * Volley of Curses / Sonorous Dreams / Contagion (Mystic)
    * Auto-finish can be Toggle on/off by command and config file (default: on)
    * Delay to finish can be changed by command and config file (default: 300)
 * Toggle module on/off by command
 * Human Behavior for every lockon skill
    * Can Toggle on/off by command and config file (default: on)
    * Can change min and max time delay in config file (min: 50 / max: 100)
 * Can configure maximum distance for each skill in 'skills.js' file (recommended: 30~35)
 * Can add or remove skills in "skills.js" file
 * Config file: "config.json"

 ## Commands
```
/8 letmelock (Toggle the module on/off)
/8 lockhuman (Toggle human behavior on/off)
/8 smartc (Toggle smart cleanse on/off)
/8 autodps (Toggle auto finish skill on/off)
/8 autodps <num> (Change the delay before finish the skill)
```

