# bar-ideas

### area effects

I like the "area mex" idea, but sometimes the circle will also have some mexes that cannot be reached (high up on hill or behind river -- see first map as an example). therefore, it'd be nice to have the ability to "draw" the area much like you can with the tilde button: draw the outline of the area, and then it'll close the area automatically with a straight line.

the next thing that would be really cool to have is to set area effects for attack, that way a unit can be told to attack anyone coming into that area.

finally, I think area effects shmould be the default for most commands. for example, if I want to reclaim a part of my base, I have to go and click on each building individually; however, if I can just draw the area that I want to reclaim (or simply swipe across some buildings), that would be a lot easier.

### everything costs energy

this is an idea more for the future, but all actions (moving, shooting, reclaiming) costs some amount of energy. this makes it so that large scale battles actually require a good power infrastructure (or a significant amount of energy storage) to be successful.

### small things

- when a map is downloading, it should disable/grey out the "start" button and show a progress bar of the download, then enable/green the button
- also, after pressing "start", there is also quite a bit of lag between when it starts and when the button is pressed, however the interface shows no confirmation that the button has been pressed (like changing the text to "starting" and disable the button).
- the top metal/energy bars should say "sharing metal/energy" unless there's nobody to share it to before saying "wasting energy"
- when observing, the resource bars on the top right are really small and hard to see. also I'm not sure what's happening, but the font seems to be clipped.
  - it'd be cool to be able to resize those even, for casters to show the economic situation of both teams a little easier

### bigger ideas (not fully thought out)

- patrol area (have units move around in an area, with attempt to spead out such that the whole area is visible)
- multiple area commands (with priority).
  - also ability to tell units to run away (or take some other defensive stance) under some conditions (like enemies enter into an area).
- I want to build my base layout without a cons, then as cons are built they'll just automatically build those buildings (instead of individually commanding them to build).
  - this has a problem with building a building really far away and all the cons try to go to do that, so probably it'd be best to make cons have a working area (defined by you when starting, this is "my" base?), and all cons just build things automatically in that area unless otherwise commanded.
  - this allows me to plan out (ahead of time) a few different base "modules" (blueprints) which I can just slap down (like say 4 kbot labs with nanoturrets behind them)
  - the minute the constructor is built, it just goes about to the (highest priority -> nearest) item to be built.
  - all buildings that don't have requisite (like T3 cons), have some sort of indicator saying that requisites aren't met yet.

### 2023-03-28 17:33 - supplies, economics, and tactics

one of the things that I want to do is somehow fuse bar and coi together. right now, it's called metal and energy, but obviously not *all* of the creation is metal; in fact, some may be electronics and stuff. supcom gets around this in a very clever way by calling it "mass" instead of metal. I always envisioned that as assembling individual atoms (think charging them up so they're anything from hydrogen to the heaviest of elements -- and mass is just like a prototype atom waiting to be infused with "energy"). I like that concept.

one of the things that I drempt of in coi was the idea of going all the way from trucks and iron, copper, and limestone mountains, all the way to building a commander, in which one would get to a bar-like interface where now you're a command you you have all of these production resources on the factory in the island to pump out robots and stuff. the system was basically the same, where you'd go from trucks to small flying drones, to nano bots, all the way to per-atom assembly. once things are built on nano/atomic scale, then construction could happen "on the field" like in TA.

therefore, I've been trying to figure out how to make a bridge between bar/TA and coi, and (even though mass is the obvious solution) it still got me thinking about another game that's influenced my thinking which is xcom. they use "supplies" -- a generic way to define something like "mass" does. however when thinking about the gameplay, I noticed that xcom is a perfect way to "train" or build up combat tactics for the individual units: imagine a bunch of battlefield moments where the units manouveres are less than optimal you load up that scenario, and then turn-based go thruogh the steps that the unit should take in an optimal combat. the symbols/commands/movements that this mode produces will get stored into the "brain" of the unit of that same type out on the battle field and they'll be able to start doing things like dodge stots, shoot in a more optimal aiming, jukes and things like that. obviously units with bigger brains will perform better as they're able to pick the symbol/action/movement set that best matches their situational goal.
