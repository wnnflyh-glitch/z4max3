# Gang War Matching

## Overview

The **Gang War Matching System** uses a **Single Elimination Tournament** format.

The top **16 Gangs** with the highest amount of **Club Silver Coins** will qualify for the tournament. These Gangs will then be **seeded (ranked)** and matched against each other in the first round.

**Match format:**

```
16 Teams → 8 → 4 → 2 → Champion
```

***

### **Seeding System (Ranking)**

After registration closes, the system will rank Gangs based on their total contribution to determine matchups for the first round.

**Match format:**

```
Club Silver Coins Registered
```

From highest → lowest

**Example:**

<table><thead><tr><th width="105">Rank</th><th>Gang</th><th>Coin</th></tr></thead><tbody><tr><td>1</td><td>Gang 1</td><td>1200</td></tr><tr><td>2</td><td>Gang 2</td><td>750</td></tr><tr><td>3</td><td>Gang 3</td><td>500</td></tr><tr><td>4</td><td>Gang 4</td><td>400</td></tr><tr><td>5</td><td>...</td><td>300</td></tr><tr><td>...</td><td>...</td><td>...</td></tr><tr><td>16</td><td>Gang 16</td><td>100</td></tr></tbody></table>

## Bracket Matching Logic

**Seed vs Reverse Seed**

```
1 vs 16
2 vs 15
3 vs 14
4 vs 13
5 vs 12
6 vs 11
7 vs 10
8 vs 9
```

## Visual Bracket Model

```
          ┌─1──
      ┌───┤     ┤─── Winner
      │   └─16─
  ┌───┤
  │   │   ┌─8──
  │   └───┤     ┤─── Winner
  │       └─9──
──┤
  │       ┌─4──
  │   ┌───┤     ┤─── Winner
  │   │   └─13─
  └───┤
      │   ┌─5──
      └───┤     ┤─── Winner
          └─12─
          ┌─3──
      ┌───┤     ┤─── Winner
      │   └─14─
  ┌───┤
  │   │   ┌─6──
  │   └───┤     ┤─── Winner
  │       └─11─
──┤
  │       ┌─2──
  │   ┌───┤     ┤─── Winner
  │   │   └─15─
  └───┤
      │   ┌─7──
      └───┤     ┤─── Winner
          └─10─
          
```
