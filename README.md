# GrillPickup
Allow players to pickup floor grills

Players must be holding a hammer and be looking at a square or triangle floor grill.

The player must then press and hold the USE key (E) for 2 seconds.

Instructions will be sent to the player.

Their main inventory must have space for the grill.

## Permissions
  - grillpickup.use - Allows players to use grill pickup

## Configuration

```json
{
  "RequirePermission": false,
  "ApplyDamage": false,
  "DamageMultiplier": 0.8,
  "Version": {
    "Major": 1,
    "Minor": 0,
    "Patch": 6
  }
}
```

 - RequirePermission - If true, users must have the grillpickup.use permission
 - ApplyDamage - If true, picked up grills will have reduced health
 - DamageMultiplier - If ApplyDamage is true, the condition of a picked up grill will be reduced by this amount.  Since the grill they actually pick up is a new grill, this will not add up over repeated pickups.
