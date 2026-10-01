# Hoard

Fabric mod for Minecraft 26.2 (Java 25).

- Every night, a horde of zombies spawns in a ring 24-48 blocks around each player.
- Horde zombies **do not burn in daylight** and don't despawn. Vanilla zombies are unchanged.
- Each night survived makes hordes bigger, tougher and a little faster (capped).
- Horde zombies hunt from ~59 blocks away and break wooden doors on any difficulty.
- Warning sound + "A horde is approaching..." action-bar message.

## Config

`config/hoard.json` is created on first launch. Options: horde size, spawn distance,
spawn chance, per-player and world caps, health/speed scaling, door breaking,
`despawnAtDawn`, message and sound toggles.

The night counter is stored per world in `hoard_state.json` (delete it to reset escalation).

## Build

```
./gradlew build
```

The jar is in `build/libs/` (use the one without `-sources`). Requires JDK 25.

## License

CC0 (from the Fabric example mod template).
