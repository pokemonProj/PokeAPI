# <div style="text-align:center">:cherries: PokeAPI :cherries:</div>
--- 


## :cherries: Overview

---


## :cherries: Abilities

---

### :page_with_curl: Description: The pokemon's weight

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **String**  |   |**```ability["name"]```** |Name of the ability|
| **Link**  |   | **```ability["url"]```**  |Ability description link|
| **Boolean**  |  **```is_hidden```** | |Tells if the ability it is a hidden ability|
| **Integer**  |  **```slot```** | | Show the pokemon ability slot. 1 and 2 for normal abilities and 3 for hidden ability|






## Base Experience 

---
### Format

```json
"base_experience" : 101
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```base_experience```** |  | Base experience of the pokemon|



## :cherries: Forms 

---

### Format

```json
"forms": 
[
    {
        "name": "ditto",
        "url": "https://pokeapi.co/api/v2/pokemon-form/132/"
    }
]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **String**  |  **```name```** |   | Pokemon name|
| **Link**  |  **```url```** |  |Description link for the pokemon format|







## :cherries: Game Indices 

---
### Format

```json
"game_indices": 
[
  {
    "game_index": 76,
    "version": 
        {
          "name": "red",
          "url": "https://pokeapi.co/api/v2/version/1/"
        }
  },
    {
      "game_index": 76,
      "version": 
        {
          "name": "blue",
          "url": "https://pokeapi.co/api/v2/version/2/"
        }
    },
    {
      "game_index": 76,
      "version": 
        {
          "name": "yellow",
          "url": "https://pokeapi.co/api/v2/version/3/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "gold",
          "url": "https://pokeapi.co/api/v2/version/4/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "silver",
          "url": "https://pokeapi.co/api/v2/version/5/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "crystal",
          "url": "https://pokeapi.co/api/v2/version/6/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "ruby",
          "url": "https://pokeapi.co/api/v2/version/7/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "sapphire",
          "url": "https://pokeapi.co/api/v2/version/8/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "emerald",
          "url": "https://pokeapi.co/api/v2/version/9/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "firered",
          "url": "https://pokeapi.co/api/v2/version/10/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "leafgreen",
          "url": "https://pokeapi.co/api/v2/version/11/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "diamond",
          "url": "https://pokeapi.co/api/v2/version/12/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "pearl",
          "url": "https://pokeapi.co/api/v2/version/13/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "platinum",
          "url": "https://pokeapi.co/api/v2/version/14/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "heartgold",
          "url": "https://pokeapi.co/api/v2/version/15/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "soulsilver",
          "url": "https://pokeapi.co/api/v2/version/16/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "black",
          "url": "https://pokeapi.co/api/v2/version/17/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "white",
          "url": "https://pokeapi.co/api/v2/version/18/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "black-2",
          "url": "https://pokeapi.co/api/v2/version/21/"
        }
    },
    {
      "game_index": 132,
      "version": 
        {
          "name": "white-2",
          "url": "https://pokeapi.co/api/v2/version/22/"
        }
    }
]
```
### Description 🛫

|      Type      |      Key       |     Value      |        Value Description         |
| :------------: | :------------: | :------------: | :------------------------------: |
|  **Integer**   | **```game_index```** |          |    Number of the pokemon on Pokedex     |
| **Dictionary** | **```version```** |                |
|   **String**   |                | **```name```** |       Game name       |
|    **Link**    |                | **```url```**  | Link to game description |








## :cherries: height 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|








## :cherries: Held Items 

---
## :cherries: Held Items 

---
### Format

```json
"held_items": 
[
    {
        "item": 
            {
                "name": "metal-powder",
                "url": "https://pokeapi.co/api/v2/item/234/"
            },
        "version_details": 
            [
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "ruby",
                            "url": "https://pokeapi.co/api/v2/version/7/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "sapphire",
                            "url": "https://pokeapi.co/api/v2/version/8/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "emerald",
                            "url": "https://pokeapi.co/api/v2/version/9/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "firered",
                            "url": "https://pokeapi.co/api/v2/version/10/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "leafgreen",
                            "url": "https://pokeapi.co/api/v2/version/11/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "diamond",
                            "url": "https://pokeapi.co/api/v2/version/12/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "pearl",
                            "url": "https://pokeapi.co/api/v2/version/13/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "platinum",
                            "url": "https://pokeapi.co/api/v2/version/14/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "heartgold",
                            "url": "https://pokeapi.co/api/v2/version/15/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "soulsilver",
                            "url": "https://pokeapi.co/api/v2/version/16/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "black",
                            "url": "https://pokeapi.co/api/v2/version/17/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "white",
                            "url": "https://pokeapi.co/api/v2/version/18/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "black-2",
                            "url": "https://pokeapi.co/api/v2/version/21/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "white-2",
                            "url": "https://pokeapi.co/api/v2/version/22/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "x",
                            "url": "https://pokeapi.co/api/v2/version/23/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "y",
                            "url": "https://pokeapi.co/api/v2/version/24/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "omega-ruby",
                            "url": "https://pokeapi.co/api/v2/version/25/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "alpha-sapphire",
                            "url": "https://pokeapi.co/api/v2/version/26/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "sun",
                            "url": "https://pokeapi.co/api/v2/version/27/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "moon",
                            "url": "https://pokeapi.co/api/v2/version/28/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "ultra-sun",
                            "url": "https://pokeapi.co/api/v2/version/29/"
                        }
                },
                {
                    "rarity": 5,
                    "version": 
                        {
                            "name": "ultra-moon",
                            "url": "https://pokeapi.co/api/v2/version/30/"
                        }
                }
            ]
    },
    {
        "item": 
            {
                "name": "quick-powder",
                "url": "https://pokeapi.co/api/v2/item/251/"
            },
        "version_details": 
            [
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "diamond",
                            "url": "https://pokeapi.co/api/v2/version/12/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "pearl",
                            "url": "https://pokeapi.co/api/v2/version/13/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "platinum",
                            "url": "https://pokeapi.co/api/v2/version/14/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "heartgold",
                            "url": "https://pokeapi.co/api/v2/version/15/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "soulsilver",
                            "url": "https://pokeapi.co/api/v2/version/16/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "black",
                            "url": "https://pokeapi.co/api/v2/version/17/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "white",
                            "url": "https://pokeapi.co/api/v2/version/18/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "black-2",
                            "url": "https://pokeapi.co/api/v2/version/21/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "white-2",
                            "url": "https://pokeapi.co/api/v2/version/22/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "x",
                            "url": "https://pokeapi.co/api/v2/version/23/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "y",
                            "url": "https://pokeapi.co/api/v2/version/24/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "omega-ruby",
                            "url": "https://pokeapi.co/api/v2/version/25/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "alpha-sapphire",
                            "url": "https://pokeapi.co/api/v2/version/26/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "sun",
                            "url": "https://pokeapi.co/api/v2/version/27/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "moon",
                            "url": "https://pokeapi.co/api/v2/version/28/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "ultra-sun",
                            "url": "https://pokeapi.co/api/v2/version/29/"
                        }
                },
                {
                    "rarity": 50,
                    "version": 
                        {
                            "name": "ultra-moon",
                            "url": "https://pokeapi.co/api/v2/version/30/"
                        }
                }
            ]
    }
]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Dictionary**  |  **```item```** |  | |
| **String**  |   | **```name```** | Item name |
| **String**  |   | **```url```**  | Link to item description |
| **List of Dictionaries**  |  **```version_details```** | | |
| **Integer**  |   | **```rarity```** | Item rarity |
| **Dictionary**  |   | **```version```** | Game version |










## :cherries: id 

---

### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|







## :cherries: is_default 

---

### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|







## :cherries: location_area_encounters 

---




## :cherries: moves 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|








## :cherries: name 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|







## :cherries: order 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|







## :cherries: order 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|






## :cherries: species 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|






## :cherries: sprites 

---
### Format

```json
[{"slot" : 1 ,
  "type" : { 
           "name" : "normal",
           "url" : "https://pokeapi.co/api/v2/type/1/"
           }
 }]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | 1 or 2  | Number(s) of pokemon type|
| **String**  |   | **```type["name"]```**  |Pokemon type name(s)|
| **Link**  |   | **```type["url"]```**  | Link to pokemon type description|





## :cherries: Stats 

---

### :page_with_curl: Description: The base stats of Pokemon

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **Integer**  |  **```base_stat```** | | Default base stats |
| **Integer**  |  **```effort```** | | EV - Increases the base stats of Pokemon |
| **Dictionary**  |   **```stat```** | |
| **String**  |   | **```name```**  | Type of the base stats |
| **Link**  |   | **```url```**  | Link to description of stats|


## :cherries: Types 

---


### :page_with_curl: Description: The pokemon's type

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **Integer**  |  **```slot```** | Number(s) of pokemon type|
| **String**  | **```type["name"]```**  |Pokemon type name(s)|
| **Link**  | **```type["url"]```**  | Link to pokemon type description|



## :cherries: Weight 

---

### :page_with_curl: Description: The pokemon's weight

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **Integer**  |  **```weight```** |Weight of pokemon|
