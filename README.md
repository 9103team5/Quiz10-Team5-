# Quiz10-Team5-
# Quiz10 Final Project

---

## Part1: Projection Direction

### Project Path

We are creating an original interactive artwork inspired by Rain Room.

### Vision and Inspiration

Our project transforms the immersive experience of Rain Room into a calming digital weather simulation using p5.js. At the beginning, rain falls vertically with ambient thunder and wind sounds in the background. As thunder becomes louder, the rain intensity increases and the storm appears heavier. Stronger wind sounds cause the rain to tilt left or right, simulating natural weather movement. The experience runs as a looping 40–60 second atmospheric scene with constantly changing rain patterns and lighting conditions.

We were inspired by the immersive atmosphere and environmental interaction of Rain Room. Instead of preventing rain from touching the user, our project focuses on creating a responsive ASMR-style digital environment that can be used as a relaxing background experience for focus, meditation, or ambience.

---

## The image of Art inspiration sources

### Images 1
![example 1](https://jackalopehotels.com/wp-content/uploads/2023/10/Rain_Room-1924x1250-1-1.jpg)

### Images 2
![example 1](https://jackalopehotels.com/wp-content/uploads/2019/09/JKLP_RainRoom_02.jpg)

## Part 2: Mechanics

### Audio  
### Responsible for Zhendong Song

The audio mechanic controls the atmosphere and behaviour of the rain using environmental sound. Our project uses thunder and wind audio tracks as the main drivers of the visual system. Using the p5.sound library, the program analyses the volume and frequency of the sound in real time. When the thunder becomes louder, the rain intensity increases, creating heavier rainfall and a stronger storm effect. Wind sounds control the direction and angle of the rain, causing the rain to tilt left or right depending on the strength of the wind audio.

Users mainly interact with this mechanic through experiencing the changing soundscape and observing how the visuals respond dynamically. The mechanic supports our project vision by transforming the immersive atmosphere of Rain Room into a calming ASMR-style digital environment. The connection between sound and rain movement helps create a cinematic and relaxing experience similar to ambient weather simulations used for focus, sleep, or meditation.

---

## Sketch Images

### Sketch Images 1
![example 1](assets/Low%20volume,%20light%20rain.JPG)

### Sketch Images 2
![example 2](assets/High%20volume%20Loud%20rain.JPG)

---

## Time-based
### Responsible for Yue Zhao

In our final project, I'd like to use time-based mechanics to create animate rainfall overtime. For instance, the rainfall may change from light rain to heavy storm, or sudden gusts of wind that tilt the falling direction of the rain, also with lighting flashes, so as to visually present the transformation of the rain room. It strengthens the project’s realistic environmental aesthetic and reflects the natural unpredictability of rainstorms.

---

## Sketch Images

### Sketch Images 1
![example 1](assets/rain%201.jpeg)

### Sketch Images 2
![example 2](assets/rain%202.jpeg)

---

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

## Part 3: Putting It Together 