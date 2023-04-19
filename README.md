# How to make a legit config for Galaxy Arduino and Raspberry

##### this document has the intent to explain how the cheat configuration works so no one needs to spend money on something they can easily make themselves.

### Cheat explantion

Both Galaxy Arduino and Raspberry are color bots, so they use the color of the enemy team player outline as a reference point so the aimbot knows where to aim and the trigger bot knows when to shoot, this causes it to also aim at anything that has this same color causing some problems.

Knowing this is essential so we can **solve some commom problems**, like:

- The aim assist and aimbot trying to aiming at deady body's.
  
- Aim pulling to Killjoy's util like granades and turret.
  
- Aim pulling to Astra smokes.
  

Those are some of the most commom things you're going to encounter while using color based aimbots.

**Solving these commom problems**, is quite easy most of them can be solved with just a little of game knowledge and setting up the cheat.

### The basics of setting legit configs

If you want to have a good legit config is essential that you remember the basics:

- The lower the fov the less likely you are to just accidentally flicking to someones head or looking suspicius.
  
- The more smoothing you have the slower your aim will pull to the enemy.
  
- On triggerbot the lower the delay the faster the cheat will shoot for you
  

Having this in mind you can start making your own config.

---

### Aimbot

The aimbot works only when you have the key you set it up pressed, knowing this is really important so you can define how big you fov is going to be since it's only going to try to find something to aim at when you have the aimbot key pressed.

- **FOV:** `"AimbotFovX": 45,` `"AimbotFovY": 40,`, i always recommend having the Y fov lower than the X fov, why you may ask ? it's so when you are shooting at the enemy the chances of your aim being dragged down because there was util or a dead body on the ground are significantly lower.
  
- **Aimbot Antishake:** `"AimbotAntishake": 15.0,` i don't always mess arround with this setting because my aim never got shaky but if your's get just make the value higher
- **Aimbot Smooth:** `"AimbotSmooth": 3.0,` smooth is a really important setting it's essentially what defines how legit you will be while playing, it is **important** to always remember that your **dpi and in game sensitivity** are a big factor on how much smooth you will need to use.

### Aimassist
Aimassist works by always having your aim getting pulled to your enemy, but remember the since it's always on it will also going to be pulled to anything that has the purple color (or any other you end up choosing) like dead bodys and util, knowing this we can set up the settings in an smarter way so there are no annoying aim pulling throughout your gameplay.

- **FOV:** `"AimassistFovX": 25,` `"AimassistFovY": 20,`, just like the aimbot i always recommend having the Y fov lower than the X fov,  


### Triggerbot


![Aimbot](https://github.com/caissaradev/Galaxy-ConfigTutorial/blob/main/images/IMG_0890.jpeg)
