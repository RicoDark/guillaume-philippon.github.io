---
layout: default
permalink: /:collection/:name.json
location: /characters/kenta.json
data:
    name: Kenta Tananka
    class: Face
    image: /shadowrun-boardgame/images/characters/kenta.png
    background_color: LightCoral
    attributes:
        health: 10
        endurance: 5
        speed: 5
        defense:
            physical:
                - white
            magical:
                - white
    skills:
        social: 6
        stealth: 7
        athletism: 8
        tech: 0
        demolition: 0
    flavor:
        - title: Ambidexter
          action: true
          stress: 1
          text: You can attack with your both gun at the same time. Roll all dice on one target.
        - title: Face
          action: false
          stress: 0
          text: When you interact with a crate, you draw 2 cards instead of 1.
    proficiencies:
        range: 1
        melee: 0
        medicine: 2
        matrice: 1
        magic: 0
---