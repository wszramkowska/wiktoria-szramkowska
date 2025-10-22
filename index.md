<style>
    body {
        background-color: #111;
        color: #eee;
        font-family: sans-serif;
        padding: 2rem;
        line-height: 1.6;
        text-align: center;
    }

    h1, h2, h3 {
        color: #66ccff;
        margin-top: 2rem;
        margin-bottom: 1rem;
    }

    p {
        max-width: 800px;
        margin: 0.5rem auto;
        text-align: left;
    }

    ul, ol {
        max-width: 9600px;
        margin: 1rem auto;
        text-align: left;
        display: table;
    }

    table {
        margin: 2rem auto;
        border-collapse: collapse;
        width: auto;
        max-width: 90%;
    }

    table th,
    table td {
        border: 1px solid #555;
        padding: 0.5rem 1rem;
        text-align: center;
    }

    video, 
    img {
        width: 90%;
        max-width: 960px;
        display: block;
        margin: 1rem auto;
        border-radius: 8px;
    }

    iframe {
        width: 90%;
        max-width: 960px;
        height: 500px;
        display: block;
        margin: 2rem auto;
        border: none;
        border-radius: 6px;
    }

    iframe.itch-widget {
        height: 167px !important;
        max-width: 960px;
        width: 90%;
        border-radius: 6px;
    }

    iframe.youtube-embed {
        width: 90%;
        max-width: 960px;
        height: 540px;
        display: block;
        margin: 2rem auto;
        border: none;
        border-radius: 6px;
        box-shadow: 0 0 12px rgba(0, 0, 0, 0.5);
    }

    a {
        color: #66ccff;
    }

    a:hover {
        text-decoration: underline;
    }

    pre {
        background-color: #1e1e1e;
        color: #f8f8f2;
        padding: 1rem;
        border-radius: 6px;
        text-align: left;
        max-width: 900px;
        overflow-x: auto;
        margin: 1rem auto;
        display: block;
        font-family: 'Courier New', Courier, monospace;
        font-size: 0.95rem;
        white-space: pre-wrap;
        box-shadow: 0 0 8px rgba(0, 0, 0, 0.4);
    }

    code {
        background-color: #2a2a2a;
        color: #ffecb3;
        padding: 0.2em 0.4em;
        border-radius: 4px;
        font-family: 'Courier New', Courier, monospace;
        font-size: 0.95em;
        white-space: pre-wrap;
    }

</style>

# Wiktoria Szramkowska

Gameplay Programmer

---

## Example GIF

![](assets/demo.gif)

*Figure 1. `demo.gif`, an example animated snippet showing system behaviour.*

GIFs are ideal for demonstrating short sequences, like UI transitions, animation loops, or gameplay snippets. Keep GIFs short and under 10MB where possible.

---

## Demo Video

<video controls>
  <source src="assets/demo.mp4" type="video/mp4">
</video>

*Figure 2. `demo.mp4`, a short embedded video demonstration.*

Videos are useful for showing interactions, effects, or walkthroughs. Use screen capture tools to create `.mp4` recordings of your project and embed them locally using the `<video>` tag.

---

## Blueprint Example

<iframe src="https://blueprintue.com/render/_wo11g40/" allowfullscreen></iframe>

*Figure 3. BlueprintUE embed — useful for sharing Unreal Engine logic visually.*

BlueprintUE is a powerful way to share and discuss Blueprint graphs in a readable format. Ideal for sharing logic behind player controls, mechanics, or UI interaction.

---

## Itch.io Widget

<iframe class="itch-widget" src="https://itch.io/embed/3456580" frameborder="0">
  <a href="https://squlddy.itch.io/alive-below">Alive Below by Wiktoria Szramkowska, anstabo</a>
</iframe>

*Figure 4. Itch.io widget embed — link to downloadable or web-based projects.*

Use the Itch.io embed widget to allow others to play or download your game directly from your submission. This is useful for deployed games or interactive tools.

---

## YouTube Embed

<iframe class="youtube-embed" src="https://www.youtube.com/embed/XwYX2GLu6bU?si=AhM8-7fZvgBTXNOI" allowfullscreen></iframe>

*Figure 5. YouTube video — for trailers, walkthroughs, or demonstrations.*

If your video is hosted externally (e.g. YouTube), you can embed it directly using the iframe tag. This is especially useful for longer-form content or commentary.

---

## Code Snippet

```bash
# Example: clone and run
git clone https://github.com/yourusername/your-project-name
cd your-project-name
open index.html
```

*Figure 6. hello-world.cpp — for your... code...*

---

## Feature Summary

Use a table to summarise what your project contains:

| Feature              | Implemented | Notes                           |
| -------------------- | ----------- | ------------------------------- |
| Core Mechanic        | ✅ Yes      | Demonstrated via GIF/video      |
| UI/UX Functionality  | ✅ Yes      | Simple HUD layout shown         |
| Sound Implementation | 🔶 Partial  | Minimal SFX & Music, no settings|
| Save/Load System     | ❌ No       | Not required for this prototype |
| Gamepad Support      | ✅ Yes      | Tested with Xbox controller     |

*Figure 7. table example — use tables to show case data, features, etc*
