---
title: Aromatic Adventures💐👃
author: Yosias Suparno
date: 2023-01-21
category: Jekyll
layout: post
cover: /assets/perfume/banner.jpg
---

![image info](/assets/perfume/infia_fact2.jpg)
It is a fact that most women are attracted to men with pleasant scents. Choosing which one is the most attractive to them is difficult for me. So, I scraped out perfume data in [this](https://fragrantica.com) site to find some insights about choosing the best perfume for me. The first question that comes up to my mind is:

## What perfume is popular?
No label on the website tells me which one is popular. So, I have decided that the more reviews a perfume has, the more popular it is. I visualized the data for male, unisex, and female perfumes, as I thought you might be curious just like me.

![image info](/assets/perfume/popular.png)

The chart above shows that Aventus from the brand Creed is the most popular among men.


I thought, *"If I buy a popular perfume, does that mean I will blend in with the crowd?"*. So, I looked for a brand that might has suitable one for me.

## What brand is making well-liked perfume?
The data luckily contains the year when each perfume was produced, allowing me to analyze trends in popular brands and identify which ones have consistently released well-liked products over time.

![image info](/assets/perfume/male-brand.png)
The table above indicates that **Dior** has consistently released well-liked products over time.

![image info](/assets/perfume/unisex-brand.png)
The table suggests that **Maison-Francis-Kurkdjian** has a pattern of producing popular product among consumers over the years.

![image info](/assets/perfume/female-brand.png)
The table displays that **Mugler** has a history of consistently putting out popular perfumes throughout the years.

I just realized that some of the products are too expensive, and choosing an unsuitable one would be a waste of money. Then I wonder...

## What kind of harmony in perfume scent is popular?
![image info](/assets/perfume/54a2c98834913eeac40829878acabf0f.jpg)
We can call harmony in perfume scent as **perfume accord**, such as woody, warm, sweet, fruity, and many more. Choosing cheaper perfume with same accord type will help me reduce my expense. 

We know that perfumes are made from different combinations of accords, each with unique blends of ingredients. The chart below will tell you what accord types are commonly blended into perfumes.

![image info](/assets/perfume/popular-accord.png)

**Woody** is the most common blended accord on a perfume. From the chart I can tell male perfumes are more **spicy and aromatic**, and female perfumes are more **floral and powdery**. 

If some perfumes have a good combination, that means some do not. I am curious to know 
which accords are not well-suited to be combined.

I calculated the correlation between accords to identify which ones tend to be combined more frequently.
![image info](/assets/perfume/accord-correlation.png)

A negative correlation indicates which accords are less likely to be paired together, while a positive correlation shows which accords are commonly combined. For example **green** will tend to be combined with **metallic, smoky, tobacco** and less with **marine, yellow floral, iris**.

The accord describes the overall aroma of a perfume. **Perfume notes** will tell the aroma in a more specific way. So..

## Which perfume notes are the most popular?
Pefume notes made of herbs, flower, fruit or any other stuff that smells unique.
A perfume tipically composed of three types of notes: top, middle and base. The **top notes** were the initial scents we applied the first time. **Middlw notes** are the heart of the perfume. We will smell the aroma after the top notes have evaporated. **Base notes** is the scent that last longer in our skin or clothes.

Pie chart below will tell you favorite notes in perfume products.
![image info](/assets/perfume/male-notes.png)
![image info](/assets/perfume/unisex-notes.png)
![image info](/assets/perfume/female-notes.png)
We learn that **bergamot** is favorite top notes, **jasmine** is favorite middle notes, and **musk** is favorite base notes.

As we know, I have data that tells when the perfume is released, so I can show you perfume notes trend over the years.

![image info](/assets/perfume/male-notes-trend.png)
**Citrus** type of notes became most favorite male top notes for five years. Middle notes composed with more **aromatic** accord. Base notes smell **woody** for five years.

![image info](/assets/perfume/unisex-notes-trend.png)
**Bitter** top notes, **floral** middle notes, and **woody** base notes are popular in the unisex perfume for over five years.

![image info](/assets/perfume/female-notes-trend.png)
Female top notes similar to male, but middle notes tend to **floral** and **vanilla** as base notes.

## Conclusion
![image info](/assets/perfume/piramid-frag.jpg)

We have learn how perfume composed. There are **unlimited posibility** to create an adored perfume from dozen herbs, flowers and any other fragrance. Insights above will help you find or give you references about perfumes. We can dig deeper into the data to get more insight. In other hand, we can train some model to classify which combination will become popular. Or even predict what will become popular notes in the future.

![image info](/assets/perfume/Versace-Eros-2-copy.jpg)
In the end, I consider to buy Versace Eros because the bottle looks cool🙉

I put stuff in [this](https://github.com/yosiasm/perfume-scraper-eda) repo.

