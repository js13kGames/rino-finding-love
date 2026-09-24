---
genres:
  - platformer
  - adventure
post: 
video: https://youtu.be/o0LkxiKJXlg
directors_cut: 
---

You are a special rhinoceros, on a journey worthy of a book. In which you will find love on the other side of dangers, struggles, and unknown lands.

## Controls

| Key | Action |
| --- | --- |
| <kbd>←</kbd> <kbd>→</kbd> | Walk. Hold them down to speed up. |
| <kbd>↑</kbd> | Jump. It’s a rhino; jumping isn’t its strong suit. During the jump, horizontal move is faster, but you can't rotate. |
| <kbd>Space</kbd> | Dash! Jump + spacebar to dash at a 45-degree angle. |

## Relevant Technical Details

  * Procedural illustration — I didn't use sprites. This allows for smoother animation and avoids the pixelated look found in most games, given the competition file size constraints.
  * A portion of state management and all physics runs inside a Web Worker, allowing a better canvas FPS.
