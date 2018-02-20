Kevin Whitaker
whitakk@gmail.com


SUMMARY OF DATA:
Shot locations and outcomes for Ivy League men's basketball games
Selected games avaliable for 2017-18 and 2016-17 seasons; all games available for 2015-16


DESCRIPTION OF FIELDS:
DATE = date of game (m/d/yyyy)
TEAM = shooting team
OPPONENT = defending team
HALF = half of game (3=OT1, 4=OT2)
TIMEREMAINING = time remaining in half (approximate, not always accurate)
PLAYERID = jersey number of shooter
MAKEMISS = outcome of shot (1=make, 0=miss, 2=shooting foul)

XINT = x-coordinate of shot location, parallel to baseline (in feet, 0 = center of court)
YINT = y-coordinate of shot location, parallel to sideline (in feet, 0 = even with basket)
	NOTE: see included image for x-y coordinates
DISTANCE = approximate distance of shot (DISTANCE = SQRT(X^2 + Y^2))

X = plotted location of x-coordinate - offset by random variance of +/- 0.5
Y = plotted location of y-coordinate - offset by random variance of +/- 0.5
	NOTE: For graphing, recommend using X and Y (offsets points by small random variance to avoid 'clustering' at integer marks)
	      For analysis, recommend using X_INT, Y_INT



All data is manually logged from watching game tape, may not be 100% accurate

NOTES ON 2016 DATA:
-First half of Dartmouth at Princeton missing because video unavailable
-Few shots in first half of Harvard at Yale missing because replay unavaliable

NOTES ON 2017 DATA:
-Few second-half shot locations of Columbia at Princeton are guesses (video cutting in and out)
-First 17:00 of Penn at Yale missing (video unavailable)
