# <div style="text-align:center">:cherries: PokeAPI :cherries:</div>
--- 


## :cherries: Overview

---


## :cherries: Abilities

---

### :page_with_curl: Description: The pokemon's abilities

| Type         | Key                      | Value Description                                                                   | 
|:------------:|:------------------------:|:-----------------------------------------------------------------------------------:|
| **String**   |**```ability["name"]```** |Name of the ability                                                                  |
| **Link**     | **```ability["url"]```** |Ability description link                                                             |
| **Boolean**  |  **```is_hidden```**     |Tells if the ability it is a hidden ability                                          |
| **Integer**  |  **```slot```**          | Show the pokemon ability slot. 1 and 2 for normal abilities and 3 for hidden ability|






## 🍒 Base Experience 

---
### :page_with_curl: Description: The pokemon's base experience

| Type         | Key                        |Value Description              | 
|:------------:|:--------------------------:|:-----------------------------:|
| **Integer**  |  **```base_experience```** | Base experience of the pokemon|



## :cherries: Forms 

---

### :page_with_curl: Description: The pokemon's forms

| Type        | Key             | Value Description                      | 
|:-----------:|:---------------:|:--------------------------------------:|
| **String**  |  **```name```** | Pokemon name                           |
| **Link**    |  **```url```**  | Description link for the pokemon format|



## :cherries: Game Indices 

---

### :page_with_curl: Description: The pokemon's indices in the game versions

|      Type      |      Key                  |       Value Description         |
|:--------------:|:-------------------------:|:------------------------------: |
|  **Integer**   | **```game_index```**      |Number of the pokemon on Pokedex |
|   **String**   | **```version["name"]```** |Game name                        |
|    **Link**    | **```version["url"]```**  |Link to game description         |

## :cherries: Height 

---

### :page_with_curl: Description: The pokemon's height

| Type         |Key                | Value Description     | 
|:------------:|:-----------------:|:---------------------:|
| **Integer**  |  **```height```** | Pokemon's total height|



## :cherries: Held Items 

---

### :page_with_curl: Description: Held itens of pokemon

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **String**  | **```item["name"]```**  | Item name |
| **String**  | **```item["url"]```**  | Link to item description |
| **String**  | **```version_details["rarity"]```**  | Item rarity |
| **String**  | **```version_details["version"]["name"]```**  | Game version name|
| **String**  | **```version_details["version"]["url"]```**  | Link to game version description|



## :cherries: Id 

---

### :page_with_curl: Description: Pokemon name

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **Integer**  | **```id```**  | Pokemon id on pokedex|



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




## :cherries: Name 

---


### :page_with_curl: Description: Pokemon name

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **String**  | **```name```**  |Pokemon name|



## :cherries: Species 

---

### :page_with_curl: Description: Complete description about the pokemon

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **String**  | **```name```**  |Pokemon name|
| **Link**  | **```url```**  | Link to complete description about pokemon|



## :cherries: Spirites 

---

### :page_with_curl: Description: Pokemon images

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **Link**  |  **```<image_name>```** | Link to pokemon image |



## :cherries: Stats 

---

### :page_with_curl: Description: The base stats of Pokemon

| Type   | Key  | Value Description| 
|:---:|:---:|:---:|
| **Integer**  |  **```base_stat```** | Default base stats |
| **Integer**  |  **```effort```** | EV - Increases the base stats of Pokemon |
| **Dictionary**  |   **```stat```** |
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
