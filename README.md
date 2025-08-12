# Platonic-Slices
Platonic Slices experimental mobile puzzle game by Daniel Sandner

- v0.1.26 (index.html, v26 file in code/)

**Fixed Problems:**
- ✅ Touch controls work on mobile

**Correct Slicing Mechanics:**
- 🔄 **Single Axis Slicing**: Cube is sliced horizontally (along Y-axis)
- 🔄 **Shared Pivot**: Each slice rotates around the same central Y-axis
- 🔄 **Intuitive Rotation**: Drag horizontally to rotate slices like turning pages in a book
- 🔄 **Snap-to-Grid**: Slices snap to 45-degree increments for easier alignment

**How it Works:**
1. **Cube is sliced** into horizontal segments (2, 3, 4, 6, or 8 slices depending on level)
2. **Each slice rotates** around the central vertical axis independently
3. **Goal**: Rotate all slices back to **0° rotation** to restore the original cube
4. **Controls**: 
   - Drag any slice horizontally to rotate it
   - Touch empty space and drag to orbit the camera
   - Slices snap to 45° increments and highlight when correctly aligned

**Visual Feedback:**
- Selected slice becomes brighter and glows
- Correctly aligned slices flash white briefly
- All slices celebrate when puzzle is complete
- Each level has a different harmonious color

The game now properly demonstrates the satisfying "book page" rotation mechanic, where *slices* pivot around a shared axis to restore the platonic solid.
