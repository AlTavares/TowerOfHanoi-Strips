# TowerOfHanoi-Strips

## Implementação para 4 discos

```
1   MOVE_disk4_disk3_pegB
2   MOVE_disk3_disk2_pegC
3   MOVE_disk4_pegB_disk3
4   MOVE_disk2_disk1_pegB
5   MOVE_disk4_disk3_disk1
6   MOVE_disk3_pegC_disk2
7   MOVE_disk4_disk1_disk3
8   MOVE_disk1_pegA_pegC
9   MOVE_disk4_disk3_disk1
10  MOVE_disk3_disk2_pegA
11  MOVE_disk4_disk1_disk3
12  MOVE_disk2_pegB_disk1
13  MOVE_disk4_disk3_pegB
14  MOVE_disk3_pegA_disk2
15  MOVE_disk4_pegB_disk3
2609 entries in hash table, 3763 hash hits, avg set size 12.
6386 total set-creation steps (entries + hits + plan length - 1).
5260 actions tried
  0.14 secs

```

## Implementação para 5 discos
```
1   MOVE_disk5_disk4_pegC
2   MOVE_disk4_disk3_pegB
3   MOVE_disk5_pegC_disk4
4   MOVE_disk3_disk2_pegC
5   MOVE_disk5_disk4_disk2
6   MOVE_disk4_pegB_disk3
7   MOVE_disk5_disk2_disk4
8   MOVE_disk2_disk1_pegB
9   MOVE_disk5_disk4_disk2
10  MOVE_disk4_disk3_disk1
11  MOVE_disk5_disk2_disk4
12  MOVE_disk3_pegC_disk2
13  MOVE_disk5_disk4_pegC
14  MOVE_disk4_disk1_disk3
15  MOVE_disk5_pegC_disk4
16  MOVE_disk1_pegA_pegC
17  MOVE_disk5_disk4_pegA
18  MOVE_disk4_disk3_disk1
19  MOVE_disk5_pegA_disk4
20  MOVE_disk3_disk2_pegA
21  MOVE_disk5_disk4_disk2
22  MOVE_disk4_disk1_disk3
23  MOVE_disk5_disk2_disk4
24  MOVE_disk2_pegB_disk1
25  MOVE_disk5_disk4_disk2
26  MOVE_disk4_disk3_pegB
27  MOVE_disk5_disk2_disk4
28  MOVE_disk3_pegA_disk2
29  MOVE_disk5_disk4_pegA
30  MOVE_disk4_pegB_disk3
31  MOVE_disk5_pegA_disk4
239778 entries in hash table, 526783 hash hits, avg set size 19.
766591 total set-creation steps (entries + hits + plan length - 1).
606252 actions tried
  9.82 secs
```

## Implementação para 6 discos


```
1   MOVE_disk6_disk5_pegB
2   MOVE_disk5_disk4_pegC
3   MOVE_disk6_pegB_disk5
4   MOVE_disk4_disk3_pegB
5   MOVE_disk6_disk5_disk3
6   MOVE_disk5_pegC_disk4
7   MOVE_disk6_disk3_disk5
8   MOVE_disk3_disk2_pegC
9   MOVE_disk6_disk5_disk3
10  MOVE_disk5_disk4_disk2
11  MOVE_disk6_disk3_disk5
12  MOVE_disk4_pegB_disk3
13  MOVE_disk6_disk5_pegB
14  MOVE_disk5_disk2_disk4
15  MOVE_disk6_pegB_disk5
16  MOVE_disk2_disk1_pegB
17  MOVE_disk6_disk5_disk1
18  MOVE_disk5_disk4_disk2
19  MOVE_disk6_disk1_disk5
20  MOVE_disk4_disk3_disk1
21  MOVE_disk6_disk5_disk3
22  MOVE_disk5_disk2_disk4
23  MOVE_disk6_disk3_disk5
24  MOVE_disk3_pegC_disk2
25  MOVE_disk6_disk5_disk3
26  MOVE_disk5_disk4_pegC
27  MOVE_disk6_disk3_disk5
28  MOVE_disk4_disk1_disk3
29  MOVE_disk6_disk5_disk1
30  MOVE_disk5_pegC_disk4
31  MOVE_disk6_disk1_disk5
32  MOVE_disk1_pegA_pegC
33  MOVE_disk6_disk5_disk1
34  MOVE_disk5_disk4_pegA
35  MOVE_disk6_disk1_disk5
36  MOVE_disk4_disk3_disk1
37  MOVE_disk6_disk5_disk3
38  MOVE_disk5_pegA_disk4
39  MOVE_disk6_disk3_disk5
40  MOVE_disk3_disk2_pegA
41  MOVE_disk6_disk5_disk3
42  MOVE_disk5_disk4_disk2
43  MOVE_disk6_disk3_disk5
44  MOVE_disk4_disk1_disk3
45  MOVE_disk6_disk5_disk1
46  MOVE_disk5_disk2_disk4
47  MOVE_disk6_disk1_disk5
48  MOVE_disk2_pegB_disk1
49  MOVE_disk6_disk5_pegB
50  MOVE_disk5_disk4_disk2
51  MOVE_disk6_pegB_disk5
52  MOVE_disk4_disk3_pegB
53  MOVE_disk6_disk5_disk3
54  MOVE_disk5_disk2_disk4
55  MOVE_disk6_disk3_disk5
56  MOVE_disk3_pegA_disk2
57  MOVE_disk6_disk5_disk3
58  MOVE_disk5_disk4_pegA
59  MOVE_disk6_disk3_disk5
60  MOVE_disk4_pegB_disk3
61  MOVE_disk6_disk5_pegB
62  MOVE_disk5_pegA_disk4
63  MOVE_disk6_pegB_disk5
25720650 entries in hash table, 66513810 hash hits, avg set size -18.
92234522 total set-creation steps (entries + hits + plan length - 1).
71522661 actions tried
  118 min, 44 seconds
```