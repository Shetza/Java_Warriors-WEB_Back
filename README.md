# Java_Warriors_WebService
⚔️Projet jeu de combat POO en Java (Version WEB)

## Iteration 8 du jeu Java_Warriors

NetBeans :
* File > Open Project > NetBean
* Run Project (F6)
* Une page s'ouvre avec le message : ``En route !!!``
* Accés a la route :
  * [GET / POST](http://localhost:8080/Netbean/api/game)
  * GET : lecture du fichier qui contient tout les éléments de la partie (Map / Héro / statut de la partie) via un fichier .json
  * POST : permet de lancer la partie et redonne les éléments du jeu au WebService
  * Pour le POST :
    * Content-Type: application/x-www-form-urlencoded
    * Body = key game :
```javascript
{
	"map": {
		"name": "map2",
		"size": 10,
		"cases": [
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 0,
				"isHeroHere": true
			},
			{
				"name": "SORT ECLAIR",
				"life": 0,
				"power": 2,
				"type": "MAGIE",
				"position": 1,
				"isHeroHere": false
			},
			{
				"name": "ARC",
				"life": 0,
				"power": 1,
				"type": "ARME",
				"position": 2,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 3,
				"isHeroHere": false
			},
			{
				"name": "SORT ECLAIR",
				"life": 0,
				"power": 2,
				"type": "MAGIE",
				"position": 4,
				"isHeroHere": false
			},
			{
				"name": "MASSUE",
				"life": 0,
				"power": 3,
				"type": "ARME",
				"position": 5,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 6,
				"isHeroHere": false
			},
			{
				"name": "POTION MINEURE",
				"life": 1,
				"power": 0,
				"type": "POTION",
				"position": 7,
				"isHeroHere": false
			},
			{
				"name": "SORT ECLAIR",
				"life": 0,
				"power": 2,
				"type": "MAGIE",
				"position": 8,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 9,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 10,
				"isHeroHere": false
			},
			{
				"name": "ARC",
				"life": 0,
				"power": 1,
				"type": "ARME",
				"position": 11,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 12,
				"isHeroHere": false
			},
			{
				"name": "POTION MINEURE",
				"life": 1,
				"power": 0,
				"type": "POTION",
				"position": 13,
				"isHeroHere": false
			},
			{
				"name": "ARC",
				"life": 0,
				"power": 1,
				"type": "ARME",
				"position": 14,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 15,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 16,
				"isHeroHere": false
			},
			{
				"name": "SORT ECLAIR",
				"life": 0,
				"power": 2,
				"type": "MAGIE",
				"position": 17,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 18,
				"isHeroHere": false
			},
			{
				"name": "ARC",
				"life": 0,
				"power": 1,
				"type": "ARME",
				"position": 19,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 20,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 21,
				"isHeroHere": false
			},
			{
				"name": "MASSUE",
				"life": 0,
				"power": 3,
				"type": "ARME",
				"position": 22,
				"isHeroHere": false
			},
			{
				"name": "SORT ECLAIR",
				"life": 0,
				"power": 2,
				"type": "MAGIE",
				"position": 23,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 24,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 25,
				"isHeroHere": false
			},
			{
				"name": "ARC",
				"life": 0,
				"power": 1,
				"type": "ARME",
				"position": 26,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 27,
				"isHeroHere": false
			},
			{
				"name": "POTION MINEURE",
				"life": 1,
				"power": 0,
				"type": "POTION",
				"position": 28,
				"isHeroHere": false
			},
			{
				"name": "POTION MINEURE",
				"life": 1,
				"power": 0,
				"type": "POTION",
				"position": 29,
				"isHeroHere": false
			},
			{
				"name": "GOBELIN",
				"life": 6,
				"power": 1,
				"type": "ENNEMY",
				"position": 30,
				"isHeroHere": false
			},
			{
				"name": "POTION STANDARD",
				"life": 2,
				"power": 0,
				"type": "POTION",
				"position": 31,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 32,
				"isHeroHere": false
			},
			{
				"name": "POTION MINEURE",
				"life": 1,
				"power": 0,
				"type": "POTION",
				"position": 33,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 34,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 35,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 36,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 37,
				"isHeroHere": false
			},
			{
				"name": "MASSUE",
				"life": 0,
				"power": 3,
				"type": "ARME",
				"position": 38,
				"isHeroHere": false
			},
			{
				"name": "POTION STANDARD",
				"life": 2,
				"power": 0,
				"type": "POTION",
				"position": 39,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 40,
				"isHeroHere": false
			},
			{
				"name": "GRANDE POTION",
				"life": 5,
				"power": 0,
				"type": "POTION",
				"position": 41,
				"isHeroHere": false
			},
			{
				"name": "EPEE",
				"life": 0,
				"power": 5,
				"type": "ARME",
				"position": 42,
				"isHeroHere": false
			},
			{
				"name": "POTION STANDARD",
				"life": 2,
				"power": 0,
				"type": "POTION",
				"position": 43 ,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 44,
				"isHeroHere": false
			},
			{
				"name": "DRAGON",
				"life": 15,
				"power": 4,
				"type": "ENNEMY",
				"position": 45,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 46,
				"isHeroHere": false
			},
			{
				"name": "SORCIER",
				"life": 9,
				"power": 2,
				"type": "ENNEMY",
				"position": 47,
				"isHeroHere": false
			},
			{
				"name": "SORT BOULE DE FEU",
				"life": 0,
				"power": 7,
				"type": "MAGIE",
				"position": 48,
				"isHeroHere": false
			},
			{
				"name": "SORT BOULE DE FEU",
				"life": 0,
				"power": 7,
				"type": "MAGIE",
				"position": 49,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 50,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 51,
				"isHeroHere": false
			},
			{
				"name": "DRAGON",
				"life": 15,
				"power": 4,
				"type": "ENNEMY",
				"position": 52,
				"isHeroHere": false
			},
			{
				"name": "EPEE",
				"life": 0,
				"power": 5,
				"type": "ARME",
				"position": 53,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 54,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 55,
				"isHeroHere": false
			},
			{
				"name": "DRAGON",
				"life": 15,
				"power": 4,
				"type": "ENNEMY",
				"position": 56,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 57,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 58,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 59,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 60,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 61,
				"isHeroHere": false
			},
			{
				"name": "DRAGON",
				"life": 15,
				"power": 4,
				"type": "ENNEMY",
				"position": 62,
				"isHeroHere": false
			},
			{
				"name": "",
				"life": 0,
				"power": 0,
				"type": "NONE",
				"position": 63,
				"isHeroHere": false
			}
		]
	},
	"hero": {
		"name": "hero1",
		"life": 5,
		"attackLevel": 5,
		"maxLife": 10,
		"maxAttackLevel": 10,
		"image": "image1",
		"type": "GUERRIER"
	},
	"gameState": {
		"dice": 3,
		"status": "IN_PROGRESS"
	}
}

```
