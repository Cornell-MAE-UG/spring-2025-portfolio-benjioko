---
layout: project
title: Axolotl Animatronic
description: An Interactive Animatronic
technologies: [Fusion 360, Arduino]
image: /assets/images/axolotl/shell1.jpeg
---

As the Mechanical Lead of the Cornell Entertainment Engineering and Design Club, I primarily lead the design of an animatronic axolotl that act as the centerpiece of an interactive scavenger hunt called "The LOTL Games". Participants go around the engineering buildings to look for worms to feed our Axolotl so it doesn’t die at the end of the day(almost like a Tamagotchi). The person with the who feeds the Axolotl the most, wins a special prize from the club.

## 🔧 Responsibilities
- Project planning & timeline development
- Constraint and design coordination across subteams
- Mechanical design of frame, tail, and water-spraying systems
- Oversaw CAD development and part sourcing

Although I oversaw the entire design of the animatronic, here are a few noteable mechanisms we worked on.

## 🏛️ The Frame
![Frame Notes]({{ "/assets/images/axolotl/frame2.jpeg" | relative_url }}){: .inline-image-r style="width: 180px" }
Made from cut Aluminium Extrusions (wanted to avoid welding at all costs). Amazing for mounting.
We used 2 variations of extrusions:
- 1 in main frame - easy to add 1in together
- 20 mm arms - a lighter and smaller alternative

### Design Considerations
➔ Electrical Component Placement
➔ Stomach Housing
➔ Eye Mechanism (scrapped)
➔ Weight (torque, beam deformation, and buckling stress)

## ⚙️ The Tail
![Tail Prototype]({{ "/assets/images/axolotl/tail1.jpg" | relative_url }}){: .inline-image-r style="width: 180px" }
![Tail Mechanism Design]({{ "/assets/images/axolotl/tail2.jpeg" | relative_url }}){: .inline-image-r style="width: 180px" }
This was a Cable and Disk System that redistributes tensions in a cable to control the motion of the tail.

We started with a servo on each cable, but the electrical team couldn’t sync servo motion at the time (unreliable). Then we moved to a motor and gear system to control vertical and horizontal motion, but there wasn't much room in body due to the stomach. We then settled on a vertical servo and gear system that isolates vertical and horizontal motion while leaving space 😁.

### Design Considerations
➔ Isolation of Vertical and Horizontal Motion
➔ Small footprint
➔ Strong enough Cables
➔ Tail Design with flexible motion

### Engineers
Arabella, Elise, and myself

## 🌊 The Water Spritz
![Water Sprtiz Testing]({{ "/assets/images/axolotl/waterspritz1.jpeg" | relative_url }}){: .inline-image-r style="width: 180px" }
One of the exciting features of our LOTL is its ability to spray water from one its arms to get a passerby’s attention.
This is done through a custom water pump and some software and electrical work for a camera to sense hand motion that triggers the water to spray.

## Design Considerations
➔ Water Proofing
➔ Mounting
➔ Compatible Hardware

### Engineers
Jason and myself

## 🤔 The Eyes (what went wrong)
![Dream Eyes]({{ "/assets/images/axolotl/eyedream.jpg" | relative_url }}){: .inline-image-r style="width: 180px" }
An early idea was to have an eye move about a “socket” like a regular eye with a camera built into one of the eye caps.

### Problems
➔ Team of different skill sets
➔ Initial mechanism was too large for the flap on the frame
➔ Time

### Engineers
Elaine, Brianna, and myself

## 😰 Main Challenges
![Me Working]({{ "/assets/images/axolotl/meworking.JPG" | relative_url }}){: .inline-image-r style="width: 180px" }
### 1. Ambition vs. Skill
This was a very ambitious project with several moving parts and 3⁄4 of our team hadn’t touched a CAD software before working on the project. This led to a lot of working time teaching people how to use the software to a point where they felt confident

### 2. Being Students and Communication
We’re all students. Stuff happens. There were several times people weren’t able to come in for a week or had something unexpected pop-up. While I truly don’t mind, it meant I had to pick up a lot of the slack.

## 💡 Lessons Learned
- Not everything can be 3D Printed
- Scope projects based on available skills
- Communicate proactively when team bandwidth changes
- Use early physical prototyping (e.g., cardboard) before CAD