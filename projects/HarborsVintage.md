---
layout: project
type: project
image: img/HarborsVintage_logo.jpg
title: "Harbors Vintage (3rd Space)"
date: 2024
published: true
labels:
  - Community 
  - Rebuilding
  - Networking
summary: "My team developed a safe space for customers to engage in."
---

<div class="text-center p-4">
  <img width="200px" src="../img/micromouse/micromouse-robot.png" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-robot-2.jpg" class="img-thumbnail" >
  <img width="200px" src="../img/micromouse/micromouse-circuit.png" class="img-thumbnail" >
</div>

  Harbors Vintage is a clothing store located in Hawaii, known for offering a curated selection of vintage clothing and accessories. The shop attracts both locals and tourists with its unique, retro inspired pieces that span various decades and styles. Whether shoppers are looking for nostalgic, one of a kind finds or popular streetwear, Harbors Vintage has become a go to destination for fashion enthusiasts in search of timeless and trendy garments.

  The store prides itself on providing high quality vintage items, many of which reflect Hawaii's vibrant culture and history. With a focus on sustainable fashion, Harbors Vintage appeals to those looking for eco-friendly shopping options, offering a more conscious way to refresh wardrobes. The store's inviting atmosphere and knowledgeable staff add to the overall shopping experience, making it a beloved spot in Hawaii's fashion scene.

  Harbors Vintage is not only a Vintage clothing store but it also includes many other things that are beneficial to the community. Harbors Vintage excells at promoting small vendors and businesses which are locally owned. My team created a new outlet branching from Harbors Vintage by which is called "3rd Space". The purpose of the third space is to create a sense of community outside consumerism. These traits include a; community bookshelf, place to lounge, place to enjoy music, place to watch movies, or be connected with the owner, etc. 


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
