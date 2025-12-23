# Client-side-Image-Cropper

Access the app: https://hilyafesmia.github.io/Client-side-Image-Cropper/

**Original Resolution Preservation**
The cropping calculation uses the ratio between the displayed preview image and the original image's source dimensions. The final canvas draw command uses the high-resolution source coordinates, ensuring no quality loss.

**Cinematic Presets:**
- **1.85:1**  : Standard US Widescreen.
- **2.35:1**  : Classic Anamorphic / CinemaScope.
- **2.6:1**   : Cinematic
- **2.77:1**  : Ultra-wide Cinerama format.
- **Custom**  : Allows you to define any ratio (e.g., 1:1 for social media or 9:16 for stories).

**Interactive Interface:**
- You can grab the highlighted area and move it to find the perfect composition.
- The frame is strictly confined to the image area, preventing "empty" space in your crop.
- Includes a subtle "Rule of Thirds" grid overlay to help with composition.
- All image processing happens in your browser's memory using HTML5 Canvas. No data is sent to a server.

**Instructions:**
1. Upload an image using the selection button.
2. Pick a ratio from the sidebar.
3. Drag the frame in the preview area to adjust your crop.
4. Click Download Crop to save the full-resolution result.
