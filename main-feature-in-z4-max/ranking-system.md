# 🏆 Ranking System

## Overview

**Ranking System** is a seasonal competitive mode where players compete in 4v4 matches, climbing the ranks using Stars and protecting their rank with Protection Points. It features end-of-season rewards, personal statistics tracking, and is integrated with the Stamina System (–1 per match) to maintain daily gameplay balance.

* **Team Win:** Gain 1 Star
* **Team Loss:** Lose 1 Star (can be protected with Protection Points)

**Match Scoring:**

* **Kill:** +1 point

***

### **Party Rules**

* Players must be friends in-game before forming a party
* Rank difference must not exceed **±2 major tiers**
* Rank is measured by **main tiers** (e.g., Gold, Platinum, Diamond, etc.)

**Example:** A Gold player cannot invite a Master player (the gap exceeds 2 tiers)

***

**Matchmaking — Criteria & Time-Based Relaxation**

**Criteria**

* **Similar Rank** – Players are matched with others of similar rank first (starting with a narrow range, e.g., ±1 major tier, then gradually expanding)
* **Win Streak** – Players with a win streak of **5 or more consecutive wins** are prioritized to be matched against each other
* **Win Rate** – The system attempts to match players with similar win rates to reduce skill gaps
* **Behavior Score** – Players with risky behavior (e.g., AFK, disruptive actions) are grouped together first

***

**Queue Time Adjustment**\
To ensure faster matchmaking while maintaining match quality, the system gradually relaxes criteria over time:

* **After 2 minutes → Relax Win Streak**
  * Expands the acceptable streak difference (high win streak players can be matched with lower streak players more easily)
* **After 5 minutes → Relax Rank**
  * Increases the acceptable rank range (from ±1 → ±2 → further, depending on server settings)
* **After 7 minutes → Relax Behavior Segmentation (one level)**
  * Allows players from different behavior groups to be matched more freely
  * Still avoids matching “best behavior” players with “worst behavior” players to protect player experience

<mark style="color:$danger;">**Note:**</mark> <mark style="color:$danger;"></mark><mark style="color:$danger;">At every stage, the system continues to prioritize matching players with similar win rates as the top priority.</mark>

***

**Team Balancing**

Once enough players are matched, the system will divide them into teams with balanced overall strength:

* **Average Win Streak of Team A ≈ Team B**
* **Average Rank of Team A ≈ Team B**

**Additional Factors:**

* Win Rate
* Behavior Score

These factors are considered to ensure a fair and enjoyable gameplay experience.

***

### Protection Points

To prevent players from dropping ranks too quickly, the system provides **Protection Points (PP)** based on rank.

Players accumulate PP when they lose (with additional bonus PP if they are the MVP on the losing team). Once PP reaches the maximum threshold, players will receive **1 Star Shield**, which prevents the loss of a star in the next defeat. After activation, PP resets to 0.

**Concept:**\
The higher the rank, the harder it is to accumulate PP (higher maximum requirement and lower PP gain per loss). As a result, Star protection becomes less frequent — making player skill more important.

#### Protection Points Table

| Rank Tier    | Points                                | Lose Recieve                          | (MVP)Lose Recieve                     |
| ------------ | ------------------------------------- | ------------------------------------- | ------------------------------------- |
| Rookie I–III | 100                                   | +50                                   | +10                                   |
| Bronze I–III | 100                                   | +50                                   | +10                                   |
| Iron I–V     | 200                                   | +40                                   | +10                                   |
| Silver I–V   | 200                                   | +40                                   | +10                                   |
| Gold I–V     | 200                                   | +30                                   | +10                                   |
| Platinum I–V | 300                                   | +30                                   | +10                                   |
| Diamond I–V  | 400                                   | +20                                   | +10                                   |
| Master I–V   | <mark style="color:$danger;">-</mark> | <mark style="color:$danger;">-</mark> | <mark style="color:$danger;">-</mark> |
| Grand Master | <mark style="color:$danger;">-</mark> | <mark style="color:$danger;">-</mark> | <mark style="color:$danger;">-</mark> |

{% hint style="info" %}
**Note:** Gaining PP does **not** protect a star in the same match you lose. The protection applies to the **next match after reaching the required PP**, to prevent intentional losing for easy star protection
{% endhint %}

***

### Tier & Stars

All ranks are divided into tiers, each requiring a certain number of Stars to progress to the next tier:

| Tier          | Stars (Max)          |
| ------------- | -------------------- |
| Rookie I–III  | 3                    |
| Bronze I–III  | 3                    |
| Iron I–V      | 5                    |
| Silver I–V    | 5                    |
| Gold I–V      | 5                    |
| Platinum I–V  | 7                    |
| Diamond I–V   | 7                    |
| Master I–V    | 10                   |
| Grand Master+ | Top 1% (Leaderboard) |

***

**Ranking Rules Standard (RRS) — Basic Rules**

* **Win:** +1 Star
* **Loss:** –1 Star (can be protected by Protection Points)
* Accumulate the required number of Stars → **Rank Up**
* If Stars drop below 0 → **Rank Down** (except **Rookie I**, which is the lowest tier)
* **Grand Master+**: No Star system; ranking is based on the **Top 1% leaderboard across the server**

***

### **King of Class (KOC) — Parallel Class Ranking**

**Objective:**\
To measure a player’s performance within their **class category**, separate from the main star-based ranking system. This creates a class-based meta and competitive environment.

**Classes:**

* **Street:** Taekwondo, Muay Thai, Boxing, Capoeira
* **Rush:** Pro Wrestling, Judo, Hapkido, Sambo

**KOC Points per Match**\
The system awards **KOC Points** based on individual performance ranking (1st–8th place in a match) and the team’s win/loss result.

**Winner**

* Winning Team — Win Rank → Points per round

| Rank   | 1  | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
| ------ | -- | - | - | - | - | - | - | - |
| Points | 10 | 8 | 6 | 5 | 4 | 3 | 2 | 1 |

**Loser**

ทีมแพ้ – Lose Rank → Point/Round

| คะแนน | 5 | 4 | 2 | 1 | −1 | −2 | −4 | −5 |
| ----- | - | - | - | - | -- | -- | -- | -- |

**Explanation:**\
Even if your team loses, high individual performance (ranked 1st–2nd) will still grant a small amount of positive points. Lower-ranked players on the losing team will lose points to discourage quitting or AFK behavior.

***

### **KOC Leaderboard**

\
KOC Points are accumulated separately by class (**Street / Rush**) throughout the season.

At the end of the season, the top players will be crowned:

* **King of Street**
* **King of Rush**

(these titles are awarded to the highest-ranked players in each class)
