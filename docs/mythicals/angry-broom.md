---
aliases:
  - angry-broom
---
# Angry broom

The Angry broom is a Mythical Wheat, Angry Broom and Prison Shank were given to miguel and scubasteez for an unknown reason. The two of them were wild killed, dropping the Mythicals.

    Sweeps bugs like flies

Stats:

    Sharpness XXV[1]

Notes:

    This item still exists, however was blue-named by Zouran shortly after being obtained.
    Currently owned by ChristieTwist

## Import information

### multipass

- The multipass is an item that can take the form of many different tools depending on the type of action you are trying to perform with it.

{%
    set angry_broom = {
        "name": "Angry Broom",
        "item_type": "wheat",
        "key_origin": "wheat",
        "enchantments": [
            {
                "name": "sharpness",
                "level": "25",
                "notes": "Hidden"
            }
        ],
        "lore": []
    }
%}

{%
    set cmp_sword = {
        "name": "Snowy Sword",
        "image": "babilu.webp",
        "item_type": "diamond_sword",
        "key_origin": "[[jester key]]",
        "enchantments": [
            {
                "name": "Mending",
                "level": "1",
            },
            {
                "name": "sharpness",
                "level": "30",
                "note": "Enchant is repeated 3 times"
            },
            {
                "name": "Smite",
                "level": "10",
                "hidden": "",
            }
        ],
        "soul_generates": {
            "type": "nature",
            "count": "2"
        },
        "belphegors_blessing": {
            "type": "nature",
            "count": "1"
        },
        "essences": [
            {
                "name": "Arrow Strike",
                "level": "1",
                "locked": ""
            }, {
                "name": "Fatal Strike",
                "level": "1",
                "note": "This has a note"
            }, {
                "name": "Cripple",
                "level": "3"
            },
        ],
        "date": "Christmas 2018",
        "kill_counter": "",
        "soul_bound": "21943second",
        "lore": ["This sword", "is cold or smt"],
    }
%}

{% set item = cmp_sword %}
{% include 'item.md' %}