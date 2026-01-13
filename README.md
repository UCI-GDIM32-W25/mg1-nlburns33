[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/MjLLqDcN)
# HW1
## Devlog
Nolan Burns, he/him

In the MG1 plan, we planned four different GameObjects: the UI text, the background, the player, and the plants. The background and plants ended up not needing any code, the plants just needed to be made into a prefab. The background was effectively created by the Main Camera GameObject. The seeds planted and seeds remaining variables were originally planned to be in a class connected to the UI text, but it ended up making more sense for them to be member variables in the Player class connected to the Player GameObject. The planned actions of movement and planting seeds for the player were implemented through the Update and PlantSeed methods. Instead of updating the UI text in Update for the UI, I used the UpdateSeeds method in the PlantCountUI class, which was attached to the Canvas GameObject.


## Open-Source Assets
If you added any other outside assets, list them here!
- [Sprout Lands sprite asset pack](https://cupnooble.itch.io/sprout-lands-asset-pack) - character and item sprites
