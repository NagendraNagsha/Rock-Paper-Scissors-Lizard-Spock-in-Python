ROCK PAPER SCISSORS LIZARD SPOCK



step 1:

ask user for how many rounds do they want to play  -- using input()
based on given input give range for loop

step2:

accept for both uppercase and lowercase as same

	cond:
		wheather given data is digit or a string --> give invalid data if the given input is a digit

step 3:
	use functions like random to generate random strings from (ROCK,PAPER,SCISSORS,IZARD,SPOCK)
	
	COND:
	take the input from user and random input generated
	
	assign 0 | 1 for the each list item
	seq:			ROCK-->PAPER-->SCISSORS-->LIZARD-->SPOCK
	FOR:ROCK---------T------0---------1----------1-------0---
		PAPER--------1------T---------0----------0-------1---
		SCISSORS-----0------1---------T----------1-------0---
		LIZARD-------0------1---------0----------T-------1---
		SPOCK--------1------0---------1----------0-------T---
		
	code: use nested dictionary i.e,  ex:  ROCK KEY HAS SET OF ROCK KEY WITH T VAL,PAPER KEY WITH 0 VAL ,SCISSORS KEY WITH 1 VAL    etc..
	
step 4:
	check count of 1's in the list 
	--the list which is having more 1's wins other looses ,if both are equal tie

  
