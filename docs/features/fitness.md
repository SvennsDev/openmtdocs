# Fitheid
Fitheid is een complex systeem voor de virtuele gezondheid van de speler.
Hier onder vindt je de basis informatie over hoe fitheid werkt.

### Hoe werkt fitheid?
Fitheid werkt met een soort punten systeem.
Je moet letten op je voeding en veel bewegen op die manier krijg je de punten.

### Commands

| Command | Omschrijving | Permissie |
|--|--|--|
| /fitness booster \<offlinePlayer> \<aantal> \<verlooptOp>| Geef een booster aan | openminetopia.fitness.booster |

Als je de fitheid van een speler aan te passen moet je nu de speler een booster geven.
 
### Config
Je kan alle settings van het fitheid gemakkelijk aan te passen in de config.

    fitness:
      maxFitnessLevel: 500
      defaultFitnessLevel: 20
      drinking:
        maxFitnessByDrinking: 20
        drinkingPointsPerPotion: 0.05
        drinkingPointsPerWaterBottle: 0.02
        drinkingPointsPerFitnessPoint: 1
        drinkingCooldown: 5
      statistics:
        maxFitnessByWalking: 30
        cmPerWalkingPoint: 1000000
        maxFitnessBySprinting: 40
        cmPerSprintingPoint: 2000000
        maxFitnessByClimbing: 30
        cmPerClimbingPoint: 500000
        maxFitnessBySwimming: 30
        cmPerSwimmingPoint: 600000
        maxFitnessByFlying: 30
        cmPerFlyingPoint: 3000000
      health:
        maxFitnessByHealth: 10
        pointsAbove9Hearts: 60
        pointsBelow5Hearts: -50
        pointsBelow2Hearts: -75
      eating:
        maxFitnessByEating: 20
        pointsForLuxuryFood: 5.0
        pointsForCheapFood: 2.0
        luxuryFood:
        - COOKED_BEEF
        - MUSHROOM_STEW
        - COOKED_PORKCHOP
        - COOKED_SALMON
        - COOKED_COD
        - BAKED_POTATO
        - COOKED_RABBIT
        cheapFood:
        - APPLE
        - BREAD
        - MELON_BLOCK
        - RAW_FISH
        - COOKED_CHICKEN
        - COOKED_MUTTON
        - COOKIE
      deathPunishment:
        duration: 1440
        enabled: true
        amount: -20
      levels:
        1-9:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.1
        10-19:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.12
        20-29:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.15
        30-39:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.16
        40-49:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.17
        50-59:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.19
        60-69:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.19
        70-79:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.2
        80-99:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.22
        100-119:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.235
        120-139:
          effects:
          - JUMP_BOOST:0
          walkSpeed: 0.25
        140-159:
          effects:
          - JUMP_BOOST:1
          walkSpeed: 0.27
        160-179:
          effects:
          - JUMP_BOOST:2
          walkSpeed: 0.29
        180-199:
          effects:
          - JUMP_BOOST:2
          walkSpeed: 0.31
        200-209:
          effects:
          - JUMP_BOOST:3
          walkSpeed: 0.325
        210-225:
          effects:
          - JUMP_BOOST:3
          walkSpeed: 0.335
        226-500:
          effects:
          - JUMP_BOOST:3
          walkSpeed: 0.335
      rainSlowdownEnabled: false
