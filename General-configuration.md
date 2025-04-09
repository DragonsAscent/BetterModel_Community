### General configuration
We uses config.yml to configure BetterModel.
```yaml
debug:
  hitbox: false
  exception: false
module:
  model: true
  player-animation: true
metrics: true
sight-trace: true
item: leather_horse_armor
max-sight: 45
min-sight: 5
lock-on-play-animation: true
namespace: "bettermodel"
pack-type: folder #folder, zip
build-folder-location: BetterModel/build
disable-generating-legacy-models: false
follow-mob-invisibility: true
animated-texture-frame-time: 10
create-pack-mcmeta: true
use-purpur-afk: true
```
- **debug** - toggles debug option.
- **module** - toggles plugin features.
- **metrics** - toggles should BetterModel send your server's info at [bStats](https://bstats.org/plugin/bukkit/BetterModel/24237).
- **sight-trace** - toggles entity culling by player sight.
- **item** - this item type will be used as model.
- **max-sight** - any model animation will not be sent when player is out of this range.
- **min-sight** - any model animation will always be sent when player is in this range.
- **lock-on-play-animation** - base entity's rotation will be ignored when external animation is on play.
- **pack-type** - generated pack type (folder, zip)
- **build-folder-location** - generated pack location
- **disable-generating-legacy-models** - should BetterModel not generate legacy client's resource pack. (<=1.21.3)
- **follow-mob-invisibility** - should model will be invisible when base entity is invisible.
- **animated-texture-frame-time** - frametime of animated texture.
- **create-pack-mcmeta** - should generate pack.mcmeta in generated resource pack.
- **use-purpur-afk** - toggles entity culling by afk when server platform is [Purpur](https://purpurmc.org/)