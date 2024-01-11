

- PLAYABLE: bool,
- PROPERTIES: { 
	- HEIGHT: int,
	- WIDHT: int,
	- ADULT_AT_DAY: int,
	- CORPE_DECAY: bool,
	- SLEEPS: bool,
	- },
	
- BEHAVIOUR: {
	- SKINNY_DIPS: int,
	- },

- BIO_FILE: assets/text/race/[[bio]], 
- OPINION_FILE_SCARED: assets/text/race/[[bio]],
- OPINION_FILE_NORMAL: assets/text/race/[[bio]],
- OPINION_FILE_CONFIDENT: assets/text/race/[[bio]],
- KING_FILE: assets/text/race/[[king]],
- WORLD_NAME_FILE: assets/text/names/[[world]],

- TOURIST: {
	- OCCURENCE: float,
	- CREDITS: float,
	- TOURIST_TEXT_FILE: assets/text/race/[[tourist]],
- },

- HOME: assets/init/race/[[home]],

- TECH: [
	- \*,\
- ],

- PREFERRED: {
	- FOOD: [
		- assets/init/[[resource]] 
	- ],
		- STRUCTURE: {
			- MOUNTAIN: 0.2,
			- STONE: 0.7,
			- GRAND: 1,
			- WOOD: 0.5,
			- OUTDOORS: 0.3,
	- },
- },
