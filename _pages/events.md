---
title: Events
layout: page
---

<style>
/* Gallery Styles */
.gallery-container {
    max-width: 600px;
    margin: 30px auto;
    position: relative;
    background: #fff;
    border-radius: 12px;
    box-shadow: 0 8px 32px rgba(0,0,0,0.1);
    overflow: hidden;
}

.gallery-image {
    width: 100%;
    height: 400px;
    object-fit: cover;
    display: none;
    transition: opacity 0.3s ease-in-out;
}

.gallery-image.active {
    display: block;
}

.gallery-nav {
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
    background: rgba(255,255,255,0.9);
    border: none;
    border-radius: 50%;
    width: 45px;
    height: 45px;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 18px;
    font-weight: bold;
    color: #333;
    transition: all 0.3s ease;
    z-index: 10;
}

.gallery-nav:hover {
    background: rgba(255,255,255,1);
    transform: translateY(-50%) scale(1.05);
    box-shadow: 0 4px 12px rgba(0,0,0,0.2);
}

.gallery-prev {
    left: 15px;
}

.gallery-next {
    right: 15px;
}

.gallery-indicators {
    display: flex;
    justify-content: center;
    padding: 20px;
    gap: 8px;
    background: linear-gradient(to bottom, transparent, rgba(0,0,0,0.05));
}

.gallery-dot {
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: #ddd;
    cursor: pointer;
    transition: all 0.3s ease;
}

.gallery-dot.active {
    background: #694b93;
    transform: scale(1.2);
}

.gallery-dot:hover {
    background: #999;
}

.gallery-caption {
    position: absolute;
    bottom: 0;
    left: 0;
    right: 0;
    background: linear-gradient(transparent, rgba(0,0,0,0.7));
    color: white;
    padding: 20px;
    text-align: center;
    font-size: 14px;
    opacity: 0;
    transition: opacity 0.3s ease;
}

.gallery-container:hover .gallery-caption {
    opacity: 1;
}

/* Counter */
.gallery-counter {
    position: absolute;
    top: 15px;
    right: 15px;
    background: rgba(0,0,0,0.7);
    color: white;
    padding: 5px 12px;
    border-radius: 20px;
    font-size: 12px;
    font-weight: 500;
}

/* Mobile responsive */
@media (max-width: 768px) {
    .gallery-container {
        margin: 20px 10px;
        max-width: none;
    }
    
    .gallery-image {
        height: 300px;
    }
    
    .gallery-nav {
        width: 40px;
        height: 40px;
        font-size: 16px;
    }
    
    .gallery-prev {
        left: 10px;
    }
    
    .gallery-next {
        right: 10px;
    }
}
</style>

Mel (and Teghan!) love to chat about our books. We'd love to visit your school, bookstore, book festival, conference, or podcast—in person or virtually! Reach out on the [Contact](https://www.melhammondbooks.com/contact) page to get in touch.

<!-- Image Gallery -->
<div class="gallery-container">
    <div class="gallery-counter">
        <span id="current-slide">1</span> / <span id="total-slides">6</span>
    </div>
    
    <img src="images/site/launch_party.jpeg" alt="Mel and Teghan chatting at Lake City Books" class="gallery-image">
    <img src="images/site/lucy_launch_charles.JPG" alt="Mel and Teghan with Charles, wearing a Lucy, Uncensored t-shirt" class="gallery-image active">
    <img src="images/site/all_class.jpg" alt="Mel teaching a class at the Arts + Literature Laboratory" class="gallery-image">
    <img src="images/site/kstate.JPG" alt="Mel and Teghan present their book at Kansas State University" class="gallery-image">
    <img src="images/site/savy_youtube.png" alt="Mel and Teghan chatting with Savy on Zoom" class="gallery-image">
    <img src="images/site/school_visit.jpeg" alt="Mel presents Love the Earth in a classroom" class="gallery-image">
     <img src="images/site/ft_wayne_launch.jpg" alt="Mel and Teghan hold up Lucy, Uncensored in a book store" class="gallery-image">
    
    <div class="gallery-caption" id="gallery-caption">
        Mel and Teghan with Charles, wearing a Lucy, Uncensored t-shirt
    </div>
    
    <button class="gallery-nav gallery-prev" onclick="changeSlide(-1)">‹</button>
    <button class="gallery-nav gallery-next" onclick="changeSlide(1)">›</button>
    
    <div class="gallery-indicators">
        <span class="gallery-dot active" onclick="currentSlide(1)"></span>
        <span class="gallery-dot" onclick="currentSlide(2)"></span>
        <span class="gallery-dot" onclick="currentSlide(3)"></span>
        <span class="gallery-dot" onclick="currentSlide(4)"></span>
        <span class="gallery-dot" onclick="currentSlide(5)"></span>
        <span class="gallery-dot" onclick="currentSlide(6)"></span>
        <span class="gallery-dot" onclick="currentSlide(7)"></span>
    </div>
</div>

### Workshops
Interested in learning to write for young people? Join an upcoming writing workshop! 

**Upcoming Classes:**
- [Writing YA and Middle Grade Novels](https://www.hisawyer.com/arts-literature-laboratory/schedules/activity-set/1561255), Wednesdays 6-8 PM, September 24-October 15, 2025 - Arts + Literature Laboratory, Madison, Wisconsin. 

### Book Events

**Past Events:**
- Monday, September 15, 2025 - 7 PM - [Mel and Teghan spoke at Kansas State University](https://www.facebook.com/share/p/1EXPU2pgyr/) Manhattan, Kansas
- Saturday, June 28, 2025 - 12:45-1:30 - LGBTQIA+ Lives Panel at Stoughton Community Pride Fest, East Side Park, Stoughton, Wisconsin
- Wednesday, June 11, 2025 - 3-4 PM Eastern (2-3 PM Central) - [Virtual Author Teen Q&A at the Thomas Crane Public Library](https://thomascranelibrary.assabetinteractive.com/calendar/teen-meet-the-authors-of-lucy-uncensored/?fbclid=IwY2xjawKmphdleHRuA2FlbQIxMABicmlkETFidTl2NUxRSFJ5R3BhS2toAR4NCMXbKtwnWdRIOajMxw23vchx-qAkaGO4wxneomwkBVW164xXhhyOpYEcMg_aem_JC7EiholMQzNQjLbdNWuBg), Quincy, MA and Virtual
- Saturday, May 10, 2025 - 1-3 PM - Teghan signing books at [Half Price Books](https://www.hpb.com/store?storeid=HPB-102&showMap=true&horizontalView=true&isForm=true&y_source=1_MTExNTM4Mi03MTUtbG9jYXRpb24ud2Vic2l0ZQ%3D%3D), Fort Wayne, IN
- Friday, November 1, 2024 - 6-8 PM - [LUCY, UNCENSORED Launch Party](https://www.facebook.com/events/522726766819520) at [Lake City Books](https://www.lakecitybooks.com/), Madison, Wisconsin
- October 8, 2024 - [Hyde Brothers Booksellers](https://hydebros.com/), Fort Wayne, Indiana
- June 23, 2024 - [Authors Telling Stories](https://www.dailyunion.com/news/jefferson_county_area/story-slam-lake-mills-author-event-raises-funds-for-jefferson-county-literacy-council/article_f1d32cdc-3196-11ef-af63-db7e8b9b65ff.html), Lewis Station, Lake Mills, WI

### Podcasts & Interviews
Mel and Teghan love to talk. Invite us onto your show! 

**Listen here:**
- "Chat with Authors Mel and Teghan Hammond on Working and Revising with a Co-writer" - [A Novel Ending Podcast](https://www.anovelending.com/episode40)
- "Mel and Teghan Hammond" - [Something (Rather Than Nothing) Podcast](https://podcasts.apple.com/us/podcast/mel-and-teghan-hammond/id1473313040?i=1000652795846)
- "I Interviewed the American Girl Author Canceled by the Far Right" - [Savy Writes Books](https://youtu.be/pbcayXOV7Tc?si=J5zsrcT5ineM4Hji)
- "Chapter 44: My Lord and Lady with Mel and Teghan Hammond" - [Jo's Boys: A Little Women Podcast](https://jos-boys-a-little-women-podcast.castos.com/episodes/chapter-44-my-lord-and-lady-with-mel-and-teghan-hammond)

### School Visits
Mel and Teghan can visit your school in person or virtually to discuss LUCY, UNCENSORED and their unique process of cowriting a YA novel as sisters. Mel can also visit your school to discuss climate change, pets, how books are made, and how to write a story.

**Past School Visits:**
- *PETS* school visit, Kindergarten - Cross Plains, Wisconsin
- *LOVE THE EARTH* school visit, fourth grade - Madison, Wisconsin

<script>
// Gallery functionality
let currentSlideIndex = 1;
const totalSlides = 7;

const captions = [
    "Mel and Teghan chatting at Lake City Books",
    "Mel and Teghan with a fan wearing a Lucy, Uncensored t-shirt",
    "Mel teaching a class at the Arts + Literature Laboratory",
    "Mel and Teghan presenting their book at Kansas State University",
    "Mel and Teghan chatting with Savy on Zoom",
    "Mel presenting Love the Earth in a classroom",
    "Mel and Teghan celebrating their book launch in Fort Wayne, Indiana",
];

function showSlide(n) {
    const images = document.querySelectorAll('.gallery-image');
    const dots = document.querySelectorAll('.gallery-dot');
    const caption = document.getElementById('gallery-caption');
    const currentCounter = document.getElementById('current-slide');
    
    if (n > totalSlides) currentSlideIndex = 1;
    if (n < 1) currentSlideIndex = totalSlides;
    
    // Hide all images and remove active class from dots
    images.forEach(img => img.classList.remove('active'));
    dots.forEach(dot => dot.classList.remove('active'));
    
    // Show current image and activate corresponding dot
    images[currentSlideIndex - 1].classList.add('active');
    dots[currentSlideIndex - 1].classList.add('active');
    
    // Update caption and counter
    caption.textContent = captions[currentSlideIndex - 1];
    currentCounter.textContent = currentSlideIndex;
}

function changeSlide(n) {
    currentSlideIndex += n;
    showSlide(currentSlideIndex);
}

function currentSlide(n) {
    currentSlideIndex = n;
    showSlide(currentSlideIndex);
}

// Initialize the gallery
document.addEventListener('DOMContentLoaded', function() {
    document.getElementById('total-slides').textContent = totalSlides;
    showSlide(currentSlideIndex);
});

// Keyboard navigation
document.addEventListener('keydown', function(e) {
    if (e.key === 'ArrowLeft') {
        changeSlide(-1);
    } else if (e.key === 'ArrowRight') {
        changeSlide(1);
    }
});
</script>