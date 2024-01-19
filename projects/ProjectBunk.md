---
layout: project
type: project
image: img/JustBunkImage1.PNG
title: "Project Bunk"
date: 2020
published: true
labels:
  - AutoCad
  - Fusion360
  - Wood Working
summary: "The journey of designing a functional bunkbed in fusion 360 using widely available wood sizes."
---

<div class="text-center p-4">
  <img width="300px" src="../img/JustBunkImage1.PNG" class="img-thumbnail" >
  <img width="300px" src="/img/BunkAndRoom.PNG" class="img-thumbnail" >
</div>

This was a personal project of mine I did in 2020. At the peak of the pandemic I found myself with lots of time on my hands, and also a very cramped room. It fit a small desk and a bed with barely any walking space. So one night I started making a very rough design for bunk bed on fusion 360. I knew nothing about standard wood sizes so I began researching about wood sizes, prices, and general strength. It was very interesting to learn how 2 by 4's are actually 1.5 by 3.5 inches and that this pattern was very consistent across every wood size. From there I measured my room and thought of all the different combinations to explore. There really wasn't many viable orientations since my room is shaped like a reverse Z tetris block.

<img width="400px" src="/img/BunkAndRoom.PNG" class="img-thumbnail" >

Here is some code that illustrates how we read values from the line sensors:

```cpp
byte ADCRead(byte ch)
{
    word value;
    ADC1SC1 = ch;
    while (ADC1SC1_COCO != 1)
    {   // wait until ADC conversion is completed   
    }
    return ADC1RL;  // lower 8-bit value out of 10-bit data from the ADC
}
```

You can learn more at the [UH Micromouse News Announcement](https://manoa.hawaii.edu/news/article.php?aId=2857).
