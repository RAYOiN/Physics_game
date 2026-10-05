# Physics Game

3D physics sandbox written in C with OpenGL 1.1 and WinAPI.

## Features

- WinAPI window + OpenGL 1.1 context
- FPS camera (mouse look, yaw + pitch)
- Movement: WASD + jump (Space)
- Procedural terrain generation (Perlin noise)
- Biomes: grass, sand, stone, snow
- Rigid body physics: gravity, bounce, friction
- Sphere rolling with angular velocity
- Object orientation along surface normals
- Object grabbing with crosshair (LMB)
- Spawn menu (Tab)
- Material system: density, restitution, friction, hardness

## Controls

| Key | Action |
|-----|--------|
| Mouse | Look around |
| W/A/S/D | Move |
| Space | Jump |
| Tab | Spawn menu |
| Up/Down | Select material |
| Enter | Spawn object |
| LMB | Grab / release |
| Mouse wheel | Push / pull object |
| Esc | Exit |

## Build

Requires Dev-C++ or MinGW.

Linker flags:
-lopengl32 -lglu32 -lgdi32 -luser32 -lkernel32 -lwinmm -lm

## License

MIT
