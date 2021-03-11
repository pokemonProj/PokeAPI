# :cherries: PokeAPI :cherries:

--- 


## :cherries: Overview
NÓS NOS BASEAMOS NO ![imagem](https://github.com/Templarian/slack-emoji-pokemon/blob/master/emojis/ditto.png?raw=true) DITTOCUJO
---


## :cherries: Abilities

---
### Format

```json
"abilities": 
[
    {
       "ability": 
          {
            "name": "limber",
            "url": "https://pokeapi.co/api/v2/ability/7/"
          },
       "is_hidden": false,
       "slot": 1
    },
    {
       "ability": 
          {
             "name": "imposter",
             "url": "https://pokeapi.co/api/v2/ability/150/"
          },
       "is_hidden": true,
       "slot": 3
    }
] 
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Dictionary**  |  **```ability```** |
| **String**  |   |**```name```** |Name of the ability|
| **Link**  |   | **```url```**  |Ability description link|
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








## :cherries: held_items 

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
| **Dictionary**  |  **```type```** | |
| **String**  |   | **```name```**  |Pokemon type name(s)|
| **Link**  |   | **```url```**  | Link to pokemon type description|





## :cherries: Stats 

---
### Format

```json
"stats": 
[
    {
        "base_stat": 48,
        "effort": 1,
        "stat": 
            {
                "name": "hp",
                "url": "https://pokeapi.co/api/v2/stat/1/"
            }
    },
    {
        "base_stat": 48,
        "effort": 0,
        "stat": 
            {
                "name": "attack",
                "url": "https://pokeapi.co/api/v2/stat/2/"
            }
    },
    {
        "base_stat": 48,
        "effort": 0,
        "stat": 
            {
                "name": "defense",
                "url": "https://pokeapi.co/api/v2/stat/3/"
            }
    },
    {
        "base_stat": 48,
        "effort": 0,
        "stat": 
            {
                "name": "special-attack",
                "url": "https://pokeapi.co/api/v2/stat/4/"
            }
    },
    {
        "base_stat": 48,
        "effort": 0,
        "stat": 
            {
                "name": "special-defense",
                "url": "https://pokeapi.co/api/v2/stat/5/"
            }
    },
    {
        "base_stat": 48,
        "effort": 0,
        "stat": 
            {
                "name": "speed",
                "url": "https://pokeapi.co/api/v2/stat/6/"
            }
    }
]
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```base_stat```** | | Default base stats |
| **Integer**  |  **```effort```** | | EV - Increases the base stats of Pokemon |
| **Dictionary**  |   **```stat```** | |
| **String**  |   | **```name```**  | Type of the base stats |
| **Link**  |   | **```url```**  | Link to description of stats|







## :cherries: Types 

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






## :cherries: Weight 

---

Weight of pokemon


### Format

```json
"weight" : 40
```

### Description 🛫

| Type   | Key  | Value | Value Description| 
|:---:|:---:|:---:|:---:|
| **Integer**  |  **```weight```** |  | Weight of pokemon|




