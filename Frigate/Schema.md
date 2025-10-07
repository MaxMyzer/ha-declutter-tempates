## Schema
### Requirements 
- `auto-entities`, `expander-card`, `mushroom-entity-card`
- I used `groups` to combine sounds into categories. You will need to adjust these (see `card.yaml`), since they depend on your naming.
- I used a `template` helper to check if the sound level has changed recently, as a "stale data" sensor.

### Entity name format
- Sound level: `{device}_sound_level`
- Sound group: `{device}_{group}__sounds_all`
- Sound stale: `{device}__sound_stale`

This *should* be all that is required for it to work. 