# How to make a legit config for Galaxy Arduino and Raspberry

###### this document has the intent to explain how the cheat configuration works so no one needs to spend money on something they can easily make themselves.

### Cheat explantion

Both Galaxy Arduino and Raspberry are color bots, so they use the color of the enemy team player outline as a reference point so the aimbot knows where to aim and the trigger bot knows when to shoot, this causes it to also aim at anything that has this same color causing some problems.

Knowing this is essential so we can **solve some commom problems**, like:

- The aim assist and aimbot trying to aiming at deady body's.
  
- Aim pulling to Killjoy's util like granades and turret.
  
- Aim pulling to Astra smokes.
  

Those are some of the most commom things you're going to encounter while using color based aimbots.

**Solving these commom problems**, is quite easy most of them can be solved with just a little of game knowledge and setting up the cheat, as explained below.

### The basics of setting legit configs

If you want to have a good legit config is essential that you remember the basics:

- The lower the fov the less likely you are to just accidentally flicking to someones head and end up looking suspicius.
  
- The more smoothing you have the slower your aim will pull to the enemy.
  
- On triggerbot the lower the delay the faster the cheat will shoot for you.
  

Having this in mind you can start making your own config.

---

### Aimbot

The aimbot works only when you have the key you set it up pressed, knowing this is really important so you can define how big you fov is going to be since it's only going to try to find something to aim at when you have the aimbot key pressed.

- **FOV:** `"AimbotFovX": 45,` `"AimbotFovY": 40,`, i always recommend having the Y fov lower than the X fov, why you may ask ? it's so when you are shooting at the enemy the chances of your aim being dragged down because there was util or a dead body on the ground are significantly lower.

- **Aimbot Smooth:** `"AimbotSmooth": 3.0,` smooth is a really important setting it's essentially what defines how legit you will be while playing, it is **important** to always remember that your **dpi and in game sensitivity** are a big factor on how much smooth you will need to use.

- **Antishake:** `"AimbotAntishake": 15.0,` i don't always mess arround with this setting because my aim never got shaky but if your's get just make the value higher.


### Aimassist
Aimassist works by always having your aim getting pulled to your enemy, but remember the since it's always on it will also going to be pulled to anything that has the purple color (or any other you end up choosing) like dead bodys and util, knowing this we can set up the settings in an smarter way so there are no annoying aim pulling throughout your gameplay.

- **FOV:** `"AimassistFovX": 25,` `"AimassistFovY": 20,`, just like the aimbot i always recommend having the Y fov lower than the X fov, you want to maintain your fov close to the enemy and away fromanything that the aimbot might think it's the enemy aka purple colered things.

- **Aimassist Smooth:** `"AimassistSmooth": 3.0,`, having your smooth setting dialed up in aimassist is **really** important if you have it too **high** it can end up doing nothing, but if you have it too **low** every time you aim away from the enemy your aim will kinda of shake and try to stay at the enemy and your crosshair movement becomes completely unnatural. A great way of becoming extremely suspicious in one play.

- **Antishake:** `"AimassistAntishake": 25.0,`, without any doubt antishake will make the most difference and be more useful in aimassist, just like it was said in the Aimbot section, if needed play arround with it, try lowering it first and raise it accoording to your needs.  

### Triggerbot

The Triggerbot works by constantly cheking to see if the crosshair is lined up to an enemy and as soon as a enemy get in front of your crosshair it will shoot for you in an impressive response time, theres not much to talk about the triggerbot only a few safety measures so you don't look obvious.

- Try not to use it in super closed corners and somewhere the normal legit player wouldn't be holding.

- **FOV:** `"TriggerbotFovX": 12,` `"TriggerbotFovY": 12,`, i recommende that both fov's should remains the same value.

- **Triggetbot Delay:** `"TriggerbotDelay": 10,`, the delay is the time it will take to the triggerbot to shoot for you when it sees the enemy, having it lower






