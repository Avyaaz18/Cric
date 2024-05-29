---
title: "Virat Kohli"
description: "Profile of Virat Kohli"
---

<img src="/images/vk.jpg" alt="Virat Kohli" style="width:50%;">

<table>
  <tr>
    <td><strong>FULL NAME</strong></td>
    <td>Virat Kohli</td>
    <td><strong>BORN</strong></td>
    <td>November 05, 1988, Delhi</td>
    <td><strong>AGE</strong></td>
    <td>35y 205d</td>
  </tr>
  <tr>
    <td><strong>BATTING STYLE</strong></td>
    <td>Right hand Bat</td>
    <td><strong>BOWLING STYLE</strong></td>
    <td>Right arm Medium</td>
    <td><strong>PLAYING ROLE</strong></td>
    <td>Top order Batter</td>
  </tr>
</table>

# TEAMS
- India
- Delhi
- Royal Challengers Bangalore
- India A
- India Blue
- India Emerging Players
- India Red
- India Under-19s
- Indian Board President's XI
- North Zone
- Oil & Natural Gas Corporation
- Rest of India

# Virat Kohli Player Profile

India has given to the world many a great cricketer but perhaps none as ambitious as Virat Kohli. To meet his ambition, Kohli employed the technical assiduousness of Sachin Tendulkar and fitness that was in the league of top athletes in the world, not just cricketers. As a result, Kohli became the most consistent all-format accumulator of his time, making jaw-dropping chases look easy, and finding, in his own words, the safest possible way to score runs. Plenty of them.

This ambition transferred seamlessly to his captaincy: he demanded more than ever of his bowlers especially the quick ones, often sacrificed a batsman for bowling depth, and led India to a long stay at No. 1 in Test rankings and a first-ever series win in Australia. He is well on his way to end up as India's most successful Test captain.

Barring one in Bangladesh, Kohli scored Test hundreds in and against every country he played. He absolutely smashed records for number of matches taken to reach eight, nine, ten and eleven thousand ODI runs, and became the first batter to score 50 hundreds in one-day internationals.

An Under-19 World Cup-winning captain, when he burst onto the scene, Kohli was a precocious talent with a cover drive to kill for. He was destined to be India's next big batsman as the Tendulkar era began to retire, but Kohli wanted to be more: a cricketer whom the opposition would be in awe of, a cricketer whose presence would raise the intensity of the contest. He lived every ball, competed each moment, and made sure he had the fitness and strength to do so. He was widely credited for changing the fitness culture in Indian cricket, introducing endurance tests as a criterion for selection.

Kohli was quite simply India's most powerful captain. Centre of every marketing campaign for Indian cricket, he also happened to lead at a time when the BCCI was run by interim administrators who knew better than to draw the ire of Indian cricket's biggest star. There was never any cause to doubt his intent: to do things that will win matches for India, which they did plenty under him.

# Virat Kohli IPL Factfile

- Virat Kohli is the only player in the Indian Premier League (IPL) to have played all seasons for one team: Royal Challengers Bangalore (RCB).
- He was picked by RCB soon after he captained India to victory in the 2008 Under-19 World Cup and has been retained by them ever since.
- Kohli is the IPL's highest run-scorer and the only one with more than 8000 runs.
- He holds the record for most IPL centuries (8) as well as most runs in a season (973 runs in 2016). He has won the Orange Cap twice - in 2016 and 2024.
- Kohli captained RCB full-time from 2013 to 2021 and led them to the final in the 2016 season, when they lost to Sunrisers Hyderabad.
- Kohli holds the record for the most prolific partnerships in the IPL, with AB de Villiers (3123 runs) and Chris Gayle (2787 runs).
- His popularity has made RCB one of the most followed teams in the IPL, even though they haven't yet won a title.

# Photo Gallery

<style>
    #gallery-container {
      width: 100%;
      overflow-x: hidden;
      position: relative;
    }
  
    #gallery {
      display: flex;
      gap: 10px;
      transition: transform 0.3s ease-in-out;
    }
  
    .gallery-item {
      width: 30%;
    }
  
    #prevBtn,
    #nextBtn {
      position: absolute;
      top: 50%;
      transform: translateY(-50%);
      background-color: rgba(255, 255, 255, 0.5);
      border: none;
      cursor: pointer;
      padding: 10px;
      z-index: 1;
      color: #333; /* Text color */
      font-size: 20px; /* Adjust as needed */
    }
  
    #prevBtn {
      left: 0;
    }
  
    #nextBtn {
      right: 0;
      background-color: rgba(0, 0, 0, 0.5); /* Background color */
      color: white; /* Text color */
    }
  </style>
  
  <div id="gallery-container">
    <button id="prevBtn" onclick="scrollGallery(-1)">❮</button>
    <div id="gallery" style="transform: translateX(0);">
      <img src="/images/image1.jpg" class="gallery-item" alt="Virat Kohli 1">
      <img src="/images/image2.jpg" class="gallery-item" alt="Virat Kohli 2">
      <img src="/images/image3.jpg" class="gallery-item" alt="Virat Kohli 3">
      <img src="/images/image4.jpg" class="gallery-item" alt="Virat Kohli 4">
      <img src="/images/image5.jpg" class="gallery-item" alt="Virat Kohli 5">
      <img src="/images/image6.jpg" class="gallery-item" alt="Virat Kohli 6">
      <img src="/images/image7.jpg" class="gallery-item" alt="Virat Kohli 7">
      <img src="/images/image8.jpg" class="gallery-item" alt="Virat Kohli 8">
    </div>
    <button id="nextBtn" onclick="scrollGallery(1)">❯</button>
  </div>
  
  <script>
    let currentSlide = 0;
    const totalSlides = document.querySelectorAll('.gallery-item').length;
  
    function scrollGallery(direction) {
      const gallery = document.getElementById('gallery');
      const galleryWidth = gallery.clientWidth;
      const galleryItemWidth = document.querySelector('.gallery-item').clientWidth;
      const maxScroll = (totalSlides - 3) * (galleryItemWidth + 10); // 10px gap
      const scrollAmount = (galleryItemWidth + 10) * direction;
      
      currentSlide = Math.max(0, Math.min(currentSlide + direction, totalSlides - 3));
      gallery.style.transform = `translateX(-${currentSlide * (galleryItemWidth + 10)}px)`;
  
      // Disable prev/next buttons if at the end or beginning
      document.getElementById('prevBtn').disabled = currentSlide === 0;
      document.getElementById('nextBtn').disabled = currentSlide === totalSlides - 3;
    }
  </script>
  
  