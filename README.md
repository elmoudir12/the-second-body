# The Second Body — Shrine

A single-file 3D puzzle game built with Three.js.

## Run

```bash
python3 -m http.server 8000
```

Then open <http://localhost:8000>. Opening `index.html` directly may also work, but a local server is recommended because assets and the physics module load from a CDN.

## Controls

| Input | Action |
| --- | --- |
| `W` `A` `S` `D` / arrow keys | Move |
| Drag mouse | Look around |
| Mouse wheel | Zoom |
| `E` / `Space` | Interact |
| `Q` | Toggle chalk drawing |
| `Enter` | Finish drawing / continue |
| `C` | Clear current drawing |
| `Tab` | Cycle drawing surface |
| `R` | Restart room |
| `Esc` | Cancel drawing |

## Notes

Everything is contained in `index.html`: geometry, materials, game logic, and levels.
