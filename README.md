# Quiz10-Team5-
# Quiz10 Final Project


Digital Rain Room
Part 0: Project Direction

Project Path

We are creating an original interactive artwork inspired by Rain Room.

Vision and Inspiration

Our project transforms the immersive experience of Rain Room into a calming digital weather simulation using p5.js. At the beginning, rain falls vertically with ambient thunder and wind sounds in the background. As thunder becomes louder, the rain intensity increases and the storm appears heavier. Stronger wind sounds cause the rain to tilt left or right, simulating natural weather movement. The experience runs as a looping 40–60 second atmospheric scene with constantly changing rain patterns and lighting conditions.

We were inspired by the immersive atmosphere and environmental interaction of Rain Room. Instead of preventing rain from touching the user, our project focuses on creating a responsive ASMR-style digital environment that can be used as a relaxing background experience for focus, meditation, or ambience.

---
## Part1: Projection Direction

## Part 2: Mechanics
### Audio  
### Responsible for Zhendong Song

I am inspired by the interactive drawing technique in p5.js, where shapes follow the mouse and update in real time. This creates a direct connection between user input and visual output. I want to use this technique to generate moving shapes that respond to interaction. This is beneficial because it makes the work more engaging and dynamic, which fits the requirement of creating interactive and responsive visual media.

---

## Sketch Images

### Sketch Images 1
![example 1](https://happycoding.io/tutorials/processing/images/input-1.gif)

### Sketch Images 2
![example 2](https://happycoding.io/tutorials/processing/images/input-3.gif)


## Time-based
### Responsible for Yue Zhao

In our final project, I'd like to use time-based mechanics to create animate rainfall overtime. For instance, the rainfall may change from light rain to heavy storm, or sudden gusts of wind that tilt the falling direction of the rain, also with lighting flashes, so as to visually present the transformation of the rain room. It strengthens the project’s realistic environmental aesthetic and reflects the natural unpredictability of rainstorms.

---

## Sketch Images

### Sketch Images 1
![example 1](assets/rain%201.jpeg)

### Sketch Images 2
![example 2](assets/rain%202.jpeg)


## Perlin Noise
### Responsible for CHUCHU TANG

In our "Digital Rain Room" project, my mechanic is responsible for transforming basic digital lines into an organic, immersive natural phenomenon. I utilize both `random()` and `noise()` functions to achieve this. First, I use `random()` to initialize each raindrop with varying lengths, weights, and falling speeds. This randomness creates a realistic sense of perspective, giving our 2D canvas a feeling of 3D depth, as some drops appear closer and faster while others are distant and slow. 

More importantly, I use the `noise()` function to simulate the continuous, unseen force of wind. Instead of falling strictly straight down, the horizontal movement of the raindrops is driven by a 1-dimensional Perlin noise value. This ensures the entire rain system sways and drifts smoothly together, mimicking fluid dynamics and avoiding the chaotic jitter of pure randomness. Additionally, I will use 2D Perlin noise to generate a slow-moving, subtle background fog, heavily contributing to the meditative and atmospheric aesthetic of our final piece.

---

### Sketch Images 1 Randomness for Depth (Parallax Rain)
![Parallax Rain Example](assets/The%20Coding%20Train%20-%20Purple%20Rain.png)
*(Reference: The Coding Train - Purple Rain)*

### Sketch Images 2 Perlin Noise for Organic Flow (Wind & Fog)
![Perlin Noise Flow Example](assets/perlin%20noise%20wind%20force.png)
*(Reference: The Coding Train - Perlin Noise Flow Field)*

## User Input
### Responsible for Yue Zhao

In this section, I want audiences to immerse themselves in the rain room and gain interactive abilities. I plan to use the collide() function to create an umbrella or a bowl. Users can move the mouse to hold this prop and physically block the falling raindrops.

---

## Sketch Images

### Sketch Images 1
![example 1](assets/collide%201.jpeg)

### Sketch Images 2
![example 2](assets/collide%202.jpeg)

## Part 3: Putting It Together 