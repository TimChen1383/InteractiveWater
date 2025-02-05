# InteractiveWater
Unreal Engine version : 5.5

### Basic Concept
- Create distance mask with X direction sine movement and Y direction sine movement
![WaterMask](https://github.com/user-attachments/assets/df8cc412-c2ce-43ce-8f4d-ed96ac5fc927)
- Record current frame's location and previous frame's location for calculate object movement
- Multiply noise texture to create water splash like mask. Water splash's strength driven by calculated object movement
![NoiseMask](https://github.com/user-attachments/assets/0557327f-083a-485c-a048-c7d79d3200ca)
- Add bubble. Bubble amount driven by calculated object movement. Bubble amount fade to 0 after few seconds
 
![InteractiveWater](https://github.com/user-attachments/assets/7569ea89-d388-4fbe-873c-10343c82eb89)
