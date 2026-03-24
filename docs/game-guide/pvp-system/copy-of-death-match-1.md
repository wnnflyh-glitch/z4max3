---
hidden: true
---

# Copy of Death Match

## Team Death Match

### Overview

Team Death Match เป็นโหมดที่ผู้เล่นถูกแบ่งออกเป็นสองทีม

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/1773125983802.gif" alt=""><figcaption></figcaption></figure></div>

```
Red Team
Blue Team
```

ผู้เล่นในแต่ละทีมสามารถมีได้สูงสุด **4 คน**

ดังนั้นจำนวนผู้เล่นรวมสูงสุดในห้องคือ

```
8 Players (4 vs 4)
```

ขั้นต่ำในการเริ่มเกมคือ

```
1 vs 1
```

***

## Match Duration

ผู้สร้างห้องสามารถเลือกเวลาแข่งขันได้

| Match Time | Description    |
| ---------- | -------------- |
| 3 Minutes  | Short Match    |
| 5 Minutes  | Standard Match |

เมื่อเวลา

```
Timer = 0
```

ระบบจะคำนวณคะแนนเพื่อหาผู้ชนะ

***

## Scoring System

คะแนนทีมจะเพิ่มเมื่อกำจัดผู้เล่นฝ่ายตรงข้าม

```
Enemy Kill = +1 Team Point
```

ตัวอย่าง Scoreboard

<div data-with-frame="true"><figure><img src="../../../.gitbook/assets/1773126568836.gif" alt="" width="563"><figcaption></figcaption></figure></div>

| Team      | Score |
| --------- | ----- |
| Red Team  | 21    |
| Blue Team | 11    |

ทีมที่มีคะแนนสูงสุดเมื่อเวลาหมดจะเป็นผู้ชนะ

***

## Tie-Break Rule

กรณีคะแนนเท่ากัน

ตัวอย่าง

```
Red Team = 35
Blue Team = 35
```

ระบบจะใช้ **MVP Player** เป็นตัวตัดสิน

กติกา

```
ทีมที่ผู้เล่น MVP อยู่ → ทีมนั้นชนะ
```

ตัวอย่าง

| MVP Player | Team     |
| ---------- | -------- |
| Player A   | Red Team |

ผลลัพธ์

```
Red Team Win
```

***

## Single Death Match

### Overview

Single Death Match เป็นโหมด **Free For All PvP**

ผู้เล่นทุกคนจะต่อสู้กันเอง ไม่มีทีม

จำนวนผู้เล่น

```
1 – 8 Players
```

ขั้นต่ำเริ่มเกม

```
1 vs 1
```

***

## Match Duration

เหมือนกับ Team Death Match

| Match Time | Description    |
| ---------- | -------------- |
| 3 Minutes  | Short Match    |
| 5 Minutes  | Standard Match |

***

## Scoring System

ผู้เล่นจะได้รับคะแนนเมื่อกำจัดผู้เล่นคนอื่น

```
Player Kill = +1 Point
```

ตัวอย่าง scoreboard

| Rank | Player   | Score |
| ---- | -------- | ----- |
| 1    | Player A | 35    |
| 2    | Player B | 33    |
| 3    | Player C | 21    |

ผู้เล่นที่มีคะแนนสูงสุดเมื่อเวลาหมดจะชนะ

***

## Tie-Break Rule

หากผู้เล่นอันดับ 1 และ 2 มีคะแนนเท่ากัน

ตัวอย่าง

```
Rank 1 = 35
Rank 2 = 35
```

ระบบจะใช้ **MVP Player** เป็นตัวตัดสิน

กติกา

```
ผู้เล่นที่ได้รับ MVP → ชนะทันที
```

ตัวอย่าง

| Player   | Score | MVP |
| -------- | ----- | --- |
| Player A | 35    | ✓   |
| Player B | 35    | -   |

ผลลัพธ์

```
Player A Win
```

***

## MVP System

### Overview

MVP (Most Valuable Player) เป็นระบบที่ใช้ประเมิน **ผู้เล่นที่มีผลงานดีที่สุดในแมตช์**

MVP ไม่ได้วัดจาก kill เพียงอย่างเดียว

แต่คำนวณจากหลายองค์ประกอบ

***

### MVP Calculation Factors

องค์ประกอบที่ใช้คำนวณ MVP เช่น

| Factor       | Description   |
| ------------ | ------------- |
| Damage Dealt | ดาเมจที่ทำได้ |
| Kill Count   | จำนวน kill    |

ระบบจะคำนวณ **Performance Score**

ผู้เล่นที่มีคะแนนสูงสุดจะได้รับ MVP

***

## Gameplay Impact of MVP

MVP มีบทบาทสำคัญในระบบ

#### 1. Tie-break decision

ใช้ตัดสินผู้ชนะในกรณีคะแนนเท่ากัน

***

#### 2. Player Recognition

แสดงผู้เล่นที่มีผลงานดีที่สุด

***

#### 3. Performance Reward

บางระบบอาจให้

* EXP bonus
* Gold bonus
