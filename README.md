# Life HQ — Homestead Prototype

Open `index.html` in a desktop browser with WebGL and internet access. The app uses the existing Three.js CDN and needs no build step. Select **Homestead** to play.

| Control | Action |
| --- | --- |
| W, A, S, D | Walk relative to the camera |
| Mouse drag | Orbit the follow camera |
| Scroll | Zoom |
| Space | Jump |
| E | Open or close the Earthship door when nearby |
| B | Toggle build mode |
| R | Rotate the selected part |
| Left click | Place the preview on the build plot |
| Escape | Exit build mode |

Walk straight ahead from spawn to reach the starter Earthship. Open the door and walk inside. The camera moves closer near walls and ceilings. Use the adjacent build plot to spend tires and earth earned through tasks and habits. A green preview marks a valid placement and a red preview marks an occupied or unaffordable placement.

Each build part has a real-world guide covering planning, installation and verification. Open **Build**, select a part marked **Study**, and pass the question at the end of each section to unlock placement. Unlocks are saved with your progress and included in backups. Use **Review guide** to revisit a completed lesson. Existing builds remain in place when opening an older save. The guides link to primary sources and identify where a real installation needs site-specific design or qualified trades.

The dashboard, habit trackers, progress history, and water, power, and crop simulation use the original `lifehq.v1` browser save. Existing structures retain their original positions and rotations. The starter Earthship is always present and is separate from the resource simulation. Use **Progress** to export and import a backup when moving to another browser or origin.

## Limitations

**Tools** sits beside **Build**. Study each item to unlock it. Equip the tape measure to click two ground points, or use the shovel on the soil patch near spawn. Follow the blue markers around the Earthship to the northeast target range. Unlock the Ruger 10/22 and .22 LR rounds, restock, and click the target from the blue pad. Ammo and hit counts are saved. Press Escape to put away the equipped tool.

Movement is designed for keyboard and mouse. Collision uses simple boxes, including for irregular build parts, and decorative rocks and mesas have no collision. Player position, camera, and door state reset on reload. The simulation is simplified gameplay. Saves are local to the browser and do not synchronize.
