# Ironhaven

A medieval kingdom under the shadow of a rising demon lord.

This is a world template for [Journal RPG](https://github.com/CYOAGame/ChooseYourOwnAdventure) — a
procedural RPG where you live out the days of background characters. Fork this repo to your GitHub
account and connect it to the game to start playing.

## World

**Setting:** Medieval fantasy  
**Start year:** 845 A.R.  
**Calendar:** 4 seasons, 30 days each

Life in Ironhaven is ordinary — market days, harvest festivals, neighbors at the well — but the
world is not. A demon lord is gathering forces in the borderlands. You will feel it before you see
it: strange lights on the ridge, travelers arriving frightened, rumors in the tavern that nobody
wants to repeat aloud.

You are not a hero. You are a blacksmith, a merchant, a soldier — someone trying to live their
life while history closes in around them.

## Factions

| Faction | Description | Starting Mood |
|---|---|---|
| Town Guard | The local militia | 5 |
| Craftsmen's Guild | Artisans and makers | 6 |
| Merchant Guild | Traders and shopkeepers | 7 |
| Village Folk | Common townsfolk | 6 |

## Archetypes

- **Blacksmith** — strength-focused, connected to the Craftsmen's Guild
- **Traveling Merchant** — cunning and charisma, connected to the Merchant Guild
- **Soldier** — strength and tactics, connected to the Town Guard

## Questline: The Demon Invasion

The overarching questline tracks the demon threat across four stages:

1. **The Demon Gathers Forces** — tension rises, strange sightings at the border
2. **Heroes Rally** — the threat is real; warriors head north
3. **The Border Falls** — refugees stream in, danger is everywhere
4. **The Final Siege** — the demon army reaches the gates

Your daily choices feed into counters that advance or regress the questline.

## Structure

```
world.yaml          — world config, factions, theme
blocks/
  archetypes/       — character archetypes (blacksmith, merchant, soldier)
  events/           — scene scripts with choices and consequences
  locations/        — tavern, market quarter
  questlines/       — demon invasion arc
state/              — initial world state (factions, questline progress, facts)
theme/              — CSS variables for the game's visual theme
journals/           — player journal entries (populated during play)
players/            — player character sheets (populated during play)
```

## Playing

1. Fork this repo to your GitHub account
2. Go to [Journal RPG](https://github.com/CYOAGame/ChooseYourOwnAdventure) and log in with GitHub
3. Select this repo as your world
4. Create a character and start playing
