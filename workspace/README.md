TO DO....

Study and improve the checkmate algorithm. It's not technically correct. It will not register a checkmate if a potential blocker/ capturer is pinned.
Also, look closely at var friendly squares. all friendly_squares should include squares the king attacks for capturing the checking piece, but not 
to block the checking piece. This is not correctly implemented at this time, in this version. 


Parse user input better. Figure out a clever way to work with existing functions. Or refactor. Right now out of bounds inputs break my code :(


Test castling ------ Does the program force you to castle if you have the option?

Castling ---- disallow castling across squared that are attacked by enemy pieces. 


Implement en passant 


Figure out a stalemate Algorithm 


Implement Queening/Knighting 