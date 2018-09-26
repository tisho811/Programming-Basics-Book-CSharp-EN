## Problem: магически числа

Да се напише програма, която въвежда едно цяло **магическо** число и изкарва всички възможни **6-цифрени числа**, за които **произведението на техните цифри е равно на магическото число**.

Example: "Магическо число" &rarr; 2
-	111112 &rarr; 1 \* 1 \* 1 \* 1 \* 1 \* 2 = 2
-	111121 &rarr; 1 \* 1 \* 1 \* 1 \* 2 \* 1 = 2
-	111211 &rarr; 1 \* 1 \* 1 \* 2 \* 1 \* 1 = 2
-	112111 &rarr; 1 \* 1 \* 2 \* 1 \* 1 \* 1 = 2
-	121111 &rarr; 1 \* 2 \* 1 \* 1 \* 1 \* 1 = 2
-	211111 &rarr; 2 \* 1 \* 1 \* 1 \* 1 \* 1 = 2

### Input Data

Входът се чете от конзолата и се състои от **едно цяло число** в интервала [**1 … 600 000**].

### Output Data

На конзолата трябва да се отпечатат **всички магически числа**, разделени с **интервал**.

### Sample Input and Output

| Input | Output | Input | Output | Input | Output |
| --- | --- | --- | --- | --- | --- |
|2|111112 111121 111211 112111 121111 211111|8|111118 111124 111142 111181 111214 111222 111241 111412 111421 111811 112114 112122 112141 112212 112221 112411 114112 114121 114211 118111 121114 121122 121141 121212 121221 121411 122112 122121 122211 124111 141112 141121 141211 142111 181111 211114 211122 211141 211212 211221 211411 212112 212121 212211 214111 221112 221121 221211 222111 241111 411112 411121 411211 412111 421111 811111|531441|999999|