15 puzzle problem using IDA*

INSTALLATION (if some modules dont exist):

pip install func_timeout
pip install psutil

RUNNING THE CODE:
1. Open command prompt here
2. $ python 15puzzle_ida.py

INPUT:
<board configuration separated by a space (0-15)>
<1/2 for number of manhattan distance and number of misplaced tile>


Examples:
python 15puzzle_ida.py
1 0 2 4 5 7 3 8 9 6 11 12 13 10 14 15
1

Output:

Moves:
R D L D D R R
No of Nodes expanded: 12
Time Taken:	0.004s
Memory usage:	28.0 KB
