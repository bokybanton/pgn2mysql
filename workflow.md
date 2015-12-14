#Workflow
+ create mysql database for chess games, players and tournaments.
+ convert pgn data to javascript array
+ connect to database
+ check if players and game exists on database
+ add pgn data to mysql database


## Database estructure

### players database
+ id
+ name
+ fide title
+ fide id
+ place birth
+ birth date
+ fide rating

### games database
+ id
+ id tournament
+ round
+ date
+ id white
+ white rating at this game
+ black rating at this game
+ time control starts at
+ white time control ends at
+ black time control ends at
+ pgn data
+ fen snapshot
+ eco code
+ result


