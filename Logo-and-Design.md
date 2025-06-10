# Logo und Design

> [English translation here](/Logo-and-Design_en.md)

## Erste Prompt Ideen

- Prompt 1 (Low Poly Vector Art):
    ```txt
    logo design, an old CRT computer monitor with a simple sad face :( on the screen, low poly vector art, isometric view, geometric shapes, sharp edges, clean minimalist style, modern gradient colors (blue and purple), on a solid dark grey background --no text, a single stray pixel tear
    ```
- Prompt 2 (Retro Pixel Art):
    ```txt
    16-bit pixel art logo, a chunky vintage CRT monitor with a sad face on its glowing green screen, limited color palette, dithering, a single blue pixel tear rolling down the screen, sharp pixels, on a transparent background, sprite sheet style
    ```
- Prompt 3 (Minimalist Monoline Icon):
    ```txt
    minimalist icon logo, a single continuous black line forming the outline of an old tube monitor, inside the screen is a simple sad face :( , monoline vector style, black on white background, ultra-clean, perfect for a favicon, negative space
    ```
- Prompt 4 (Detailed Glitch Art / Retro-Futurism):
    ```txt
    logo for a tech group, a photorealistic 80s beige CRT monitor, powered on in a dark room. The screen shows a sad face made of glowing green phosphor ASCII characters. The image is distorted by scan lines and a heavy digital glitch effect, cinematic lighting, retro-futurism, vintage electronics
    ```

## Erste Generation

- Modell: [flux.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)
- ComfyUI-Workflow: [flux.1-dev-workflow](assets/flux.1-dev-workflow.json)

### Prompt 1

![prompt-1-pic-1](/assets/gen1/prompt-1-pic-1.png)
![prompt-1-pic-2](/assets/gen1/prompt-1-pic-2.png)
![prompt-1-pic-3](/assets/gen1/prompt-1-pic-3.png)
![prompt-1-pic-4](/assets/gen1/prompt-1-pic-4.png)

### Prompt 2

![prompt-2-pic-1](/assets/gen1/prompt-2-pic-1.png)
![prompt-2-pic-2](/assets/gen1/prompt-2-pic-2.png)
![prompt-2-pic-3](/assets/gen1/prompt-2-pic-3.png)
![prompt-2-pic-4](/assets/gen1/prompt-2-pic-4.png)

### Prompt 3

![prompt-3-pic-1](/assets/gen1/prompt-3-pic-1.png)
![prompt-3-pic-2](/assets/gen1/prompt-3-pic-2.png)
![prompt-3-pic-3](/assets/gen1/prompt-3-pic-3.png)
![prompt-3-pic-4](/assets/gen1/prompt-3-pic-4.png)

### Prompt 4

![prompt-4-pic-1](/assets/gen1/prompt-4-pic-1.png)
![prompt-4-pic-2](/assets/gen1/prompt-4-pic-2.png)
![prompt-4-pic-3](/assets/gen1/prompt-4-pic-3.png)
![prompt-4-pic-4](/assets/gen1/prompt-4-pic-4.png)

## Prompt Verbesserung v1

- Prompt 1 (Low Poly Vector Art):
    ```txt
    logo design, an old CRT computer monitor in the low poly art style, rendered from a dramatic isometric perspective. The monitor is constructed from a clear mesh of geometric polygons, creating a faceted, papercraft-like appearance. The screen displays a simple, angular sad face :(. A single, sharp polygon represents a tear. The color palette uses a gradient of cool tones, like blues and purples, across the facets to simulate lighting. The image is clean, sharp, and has a 3D-on-2D feel, set against a solid dark background. --style raw --no text --ar 1:1
    ```
- Prompt 2 (Retro Pixel Art):
    ```txt
    Authentic 16-bit pixel art logo of a chunky, beige CRT computer monitor. The screen emits an eerie, phosphorescent green glow, displaying a sad face :( composed of bright green pixels. The monitor's case uses a limited color palette with dithering for shading, giving it a nostalgic, retro feel. A single, bright blue pixel tear drips from the corner of the screen. Every pixel is sharp and perfectly aligned to the grid. Isolated on a black background for high contrast. --no text
    ```
- Prompt 3 (Minimalist Monoline Icon):
    ```txt
    An ultra-minimalist, single-line icon logo. A single, continuous black line of uniform thickness (monoline) artfully draws the entire shape of a vintage CRT monitor and, without lifting, forms a simple sad face :( within the screen's boundary. The design is elegant, clever, and highly simplified, using negative space effectively. Presented as a clean vector graphic, black on a pure white background. Perfect for a favicon or app icon. --no photorealism, text, or shading
    ```
- Prompt 4 (Detailed Glitch Art / Retro-Futurism)):
    ```txt
    A moody, cinematic logo. A photorealistic, dusty 1980s computer monitor sits in a dark, atmospheric room. The screen is alive with a sad face :( constructed from blinking green ASCII terminal text. The entire image is heavily corrupted by a digital glitch art effect: vibrant chromatic aberration, flickering horizontal scan lines, and distorted data moshing. The scene is lit only by the monitor's eerie glow, reflecting off the worn plastic casing. Retro-futuristic, analog horror aesthetic. --ar 1:1 --no text
    ```

## V1 Generation

- Modell: [flux.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)
- ComfyUI-Workflow: [flux.1-dev-workflow](assets/flux.1-dev-workflow.json)

### Prompt 1

![prompt-1-pic-1](/assets/gen2/prompt-1-pic-1.png)
![prompt-1-pic-2](/assets/gen2/prompt-1-pic-2.png)
![prompt-1-pic-3](/assets/gen2/prompt-1-pic-3.png)
![prompt-1-pic-4](/assets/gen2/prompt-1-pic-4.png)

### Prompt 2

![prompt-2-pic-1](/assets/gen2/prompt-2-pic-1.png)
![prompt-2-pic-2](/assets/gen2/prompt-2-pic-2.png)
![prompt-2-pic-3](/assets/gen2/prompt-2-pic-3.png)
![prompt-2-pic-4](/assets/gen2/prompt-2-pic-4.png)

### Prompt 3

![prompt-3-pic-1](/assets/gen2/prompt-3-pic-1.png)
![prompt-3-pic-2](/assets/gen2/prompt-3-pic-2.png)
![prompt-3-pic-3](/assets/gen2/prompt-3-pic-3.png)
![prompt-3-pic-4](/assets/gen2/prompt-3-pic-4.png)

### Prompt 4

![prompt-4-pic-1](/assets/gen2/prompt-4-pic-1.png)
![prompt-4-pic-2](/assets/gen2/prompt-4-pic-2.png)
![prompt-4-pic-3](/assets/gen2/prompt-4-pic-3.png)
![prompt-4-pic-4](/assets/gen2/prompt-4-pic-4.png)

## Prompt Verbesserung v2

- Jetzt wird immer ein Low Poly Vector Art Style genutzt
- Prompt 1:
    ```txt
    logo design, a low poly CRT monitor in the style of a technical hand-drawn sketch. The image is rendered in black ink on textured white paper. The monitor's geometric facets are defined by confident, slightly imperfect outlines. Shading is achieved through meticulous cross-hatching to emphasize the different polygonal planes. The screen displays an angular sad face :(. A single, deliberate ink blot forms a tear. The overall aesthetic is a blend of architectural blueprint and artist's sketchbook. --no color --no gradients --ar 1:1
    ```
- Prompt 2:
    ```txt
    A low poly CRT computer monitor, personified as a small, sad robot, rendered in a 90s retro anime style. The design features sharp cel shading and bold, black ink outlines. The monitor's polygonal body has a matte, plastic texture. The screen glows brightly, displaying a stylized, expressive sad anime face (T_T). The color palette is nostalgic, with muted blues and greys contrasted by a vibrant, glowing screen. A single, large, glistening anime-style tear drips down its face. Set against a simple background with subtle screentone dot patterns. --ar 1:1
    ```
- Prompt 3:
    ```txt
    Minimalist logo of a CRT monitor, reduced to its most essential forms in an ultra-clean low poly style. The design uses a minimal number of large, geometric polygons with razor-sharp edges. The monitor is bathed in a beautiful, smooth gradient transitioning from a deep space blue to an electric purple. The screen is a simple, dark facet with an angular sad face :( cut out. A single, isolated triangular polygon represents a tear, catching the light from the gradient. Clean vector art, isolated on a light grey background. --no textures --no outlines --ar 1:1
    ```
- Prompt 4:
    ```txt
    A low poly CRT monitor designed with a dark, brutalist aesthetic. The monitor appears to be cast from a single, massive block of raw, textured concrete, with visible polygonal facets and chipped, sharp edges. It is lit by a single, harsh top-down light, creating deep, dramatic shadows that emphasize its blocky form. The screen is dark and non-illuminated, with a sad face :( crudely etched or cracked into the glass surface. The entire image is monochromatic, using only shades of dark gray and black. Dystopian, heavy, monolithic. --ar 1:1 --no color
    ```

## V2 Generation

- Modell: [flux.1-dev](https://huggingface.co/black-forest-labs/FLUX.1-dev)
- ComfyUI-Workflow: [flux.1-dev-workflow](assets/flux.1-dev-workflow.json)

### Prompt 1


![prompt-1-pic-1](/assets/gen3/prompt-1-pic-1.png)
![prompt-1-pic-2](/assets/gen3/prompt-1-pic-2.png)
![prompt-1-pic-3](/assets/gen3/prompt-1-pic-3.png)
![prompt-1-pic-4](/assets/gen3/prompt-1-pic-4.png)

### Prompt 2

![prompt-2-pic-1](/assets/gen3/prompt-2-pic-1.png)
![prompt-2-pic-2](/assets/gen3/prompt-2-pic-2.png)
![prompt-2-pic-3](/assets/gen3/prompt-2-pic-3.png)
![prompt-2-pic-4](/assets/gen3/prompt-2-pic-4.png)

### Prompt 3

![prompt-3-pic-1](/assets/gen3/prompt-3-pic-1.png)
![prompt-3-pic-2](/assets/gen3/prompt-3-pic-2.png)
![prompt-3-pic-3](/assets/gen3/prompt-3-pic-3.png)
![prompt-3-pic-4](/assets/gen3/prompt-3-pic-4.png)

### Prompt 4

![prompt-4-pic-1](/assets/gen3/prompt-4-pic-1.png)
![prompt-4-pic-2](/assets/gen3/prompt-4-pic-2.png)
![prompt-4-pic-3](/assets/gen3/prompt-4-pic-3.png)
![prompt-4-pic-4](/assets/gen3/prompt-4-pic-4.png)

## Finales Logo

- Bild `assets/prompt-1-pic-1.png`
- keine weiteren Veränderungen

![Logo](assets/Logo.png)

## Animation

- Modell: Google Veo2 Video
- ComfyUI-Workflow: [veo2-workflow](assets/veo2-workflow.json)
- Bild: Logo
- Prompt:
    ```txt
    A short animation in a black and white sketchy, geometric line art style. An old CRT monitor with a sad face stands on a white background. The single teardrop on its screen slowly rolls down the glass, leaving a faint trail before dripping off the bottom edge of the screen. The monitor's expression remains sorrowful."
    ```
- MP4-File: `assets/Logo-Animation.mp4`

![Logo-Animation](assets/Logo-Animation.gif)
