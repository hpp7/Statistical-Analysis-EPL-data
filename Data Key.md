# Data Key 

### Terminology:

A football match is generally 90 minutes long divided into two halves played between two team (Home team v/s Away team). Whoever is leading the match by the end of 90 minutes Wins the match. If the scores are equal, the match is considered draw. 

1. Corners - A corner kick is the method of restarting play in a game of association football when the ball goes out of play over the goal line, without a goal being scored, and having last been touched by a member of the defending team. The kick is taken from the corner of the field of play nearest to where it went out.

2. Fouls - Fouls and misconduct in football/soccer are acts committed by players which are deemed by the referee to be unfair and are subsequently penalized. An offence may be a foul, misconduct or both depending on the nature of the offence and the circumstances in which it occurs.

3. Yellow and Red Cards - A player who has been cautioned may continue playing in the game; however, a player who receives a second caution in a match is sent off (shown the yellow card again, and then a red card), meaning that he must leave the field immediately and take no further part in the game.


### Some calculated fields:

•	Booking Points = Number of yellow cards * 10 + Number of Red cards * 25

•	Defense Rate = (1 - (Away Team Shots on Target / Away Team Shots)) * 100

•	Keeper Save Accuracy = (1 - (Away Team Goals / Away Team Shots on Target)) * 100

•	Shot Accuracy = (Home Team Shots on Target / Home Team Shots) * 100

•	Goal Conversion = (Home Team Goals / Home Team Shots on Target) * 100


### Data Set 1: Match Level Data 

*(https://github.com/aparnaadiraju92/Statistical-Analysis-EPL-data/blob/master/ProjectMatchleveldata_R.xlsx)

•	Year and Date

•	Home Team and Away Team

•	Type of match (0 = Derby team Home v/s Derby Team Away, 1 = Derby team as Home v/s Non Derby team as Away, 2 = Non Derby team as Home v/s Derby team as Away, 3 = Non Derby team v/s Non Derby Team )	

•	FTHG = Full time Home Goals

•	FTAG = Full time Away Goals

•	FTR = Full time result (H = Home win, A = Away win, D = Draw) = categorical with three categories.

•	HTHG = Half time Home Goals

•	HTAG = Half time Away Goals

•	HTR = Full time result (H = Home lead, A = Away lead, D = Draw) = categorical: three categories.

•	Referee and Referee cluster (

•	HS / AS = Home/Away shots

•	HST / AST = Home/Away shots on Target

•	HF / AF = Home/Away Fouls

•	HC / AC = Home/Away Corners

•	HY/AY = Home/Away Yellow cards

•	HR/AR = Home/Away Red cards

•	HBP/ABP = Home/Away Booking Points = (number of Yellow cards * 10) + (number of Red cards * 25)

•	FTGD/HTGD = Full time/Half time Goal Difference

•	B365A/ B365H/ B365D = Betting odds for Away, Home, Draw – minimum the betting odds, more chance of winning. 

 

### Data Set 2: League Level Data 

*(https://github.com/aparnaadiraju92/Statistical-Analysis-EPL-data/blob/master/ProjectLeagueleveldata.xlsx)

•	W = Wins

•	D = Draw

•	L = Lost

•	GD = Goal difference

•	Pts = Points

•	FI = Fouls

•	Y = Yellow Cards

•	R = Red Cards

•	Sh = Shots 

•	ShT = Shots on Target



