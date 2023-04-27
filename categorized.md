# categorised

### for casters

- ability to change colours of the team (and put scores)
- ability to show stats from the last game while the new one is loading
- ability to grab a section of units (say currently in battle) and make that a small window so that viewer can keep tabs on that battle as they move to a different part of the map
- ability to see health bars in cinematic mode
- ability to still see econ stats when switching to player cam
- second screen
  - ability to set music
  - see minimap
    - with hotspots for action

### quality of life

- shared 0 units, 0 energy, 0 metal are all not necessary to display
- transportation planes
  - ablity to tell a transportable unit (like a cons tower) to move to a new location, and then when I have an idle transport, it'll get moved
  - set a pickup zone and dropoff zone. anyone clicking in the zone will get ferried to the dropoff
- when receiving a unit from someone, the notification should higlight the new unit with a coloured thing like the one that goes around the empty metal spots
  - with the colour of the person that gave the unit
  - the highlight should continue until it's clicked
  - if I click on the ("you've received new units") notification, it should centre the viewport on the unit(s).

### priorities

- abolity to set priorities for construction turrets
  - repair
    - units that are being reclaimed
    - damaged units
      - defensive units
    - damaged buildings
      - defensive buildings
      - econ buildings
  - construct
    - buildings
      - lower/higher metal cost buildings prioritised
      - defence/econ building prioritised
    - units
  - reclaim (metal/energy)

### unit ideas

- vehicle/bot that functions like a mobile construction turret, able to reclaim, repair, and (possibly) resurrect as it drives around the map

### building construction

- ability to move the shadow before it starts building (keeps its order in queue) to either add spacing or correct position

### patrol routes

this feature is just a list of patrol routes that are stored. the idea is that units can be added/removed from them, and there are stats to tell you how many are in it.

- when giving a command to a unit with a patrol route assigned:
  - it'll do the command, then when done
  - return back to its nearest next station on the patrol route
- default flight patterns
  - when pulling fighters off to go do something, after they've done that, they can be put back on the patrol route they were on before
  - auto repair priority
- gantrys can set their patrol route route
- gantrys can assign patrol routes per-unit
  - fighters to frontline/base patrol
  - cons to patrol base
  - bombers to sit on ground
  - etc.
