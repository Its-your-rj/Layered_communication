# Layered_communication

HOW DATA ACTUALLY FLOWS IN THIS NETWORK?



1)SNEDER
2)ENCRYPTION
3)COMPRESSION (LZW ALGO)
4)CRC -CHECKER
5)TRANSFER
6)CRC-CHECKER
7)DECOMPRESSION (LZW ALGO)
8)DECRYPTION
9)RECEIVER

ENCRYPTION AND DECRYPTION ALGOS USED HERE

ENCRYPTION TECHNIQUE: GIVEN L AS THE
STRING'S LENGTH, TAKE TWO VALUES: THE FLOOR
OF L (LET'S SAY A) AND THE CEIL OF L (LET'S SAY
B). CREATE A TWO-DIMENSIONAL MATRIX WITH
ROWS = A AND COLUMNS = B.
INCREASE THE VALUE OF AN OR B, WHICHEVER IS
THE MINIMUM, IF ROWS*COLUMNS < L.
SEQUENTIALLY ENTER EACH CHARACTER FROM
THE ORIGINAL STRING INTO THE MATRIX. ONCE
THE MATRIX HAS BEEN OBTAINED, READ IT
COLUMN BY COLUMN AND PRINT THE RESULTANT
STRING.

METHOD OF DECRYPTION: IF L IS THE LENGTH OF
THE ENCRYPTED STRING, THEN ONCE MORE
DETERMINE THE VALUES A AND B, WHERE AN IS
THE STRING'S CEILING VALUE AND B ITS FLOOR
VALUE. TO OBTAIN THE STRING IN ITS ORIGINAL
FORMAT, ESTABLISH A 2D MATRIX AND STORE
THE STRING IN IT COLUMN-WISE. THEN, READ
THE MATRIX ROW-WISE.




