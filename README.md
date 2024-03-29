# Phoenix Engine

An evolving, lightweight 2d game engine.

---

### Libraries
- entt (entity component system)
- Sfml (graphics amd input handling)
- Box2D (2d physics)
- spdlog (logging)

### Build

#### Requirements

- gcc compiler
- GNU make
- cmake 3.20 or higher

<br>

1. Clone the repository:
```
git clone https://github.com/Karan-Semwal/SFGame.git
```

2. Open a terminal into cloned repository.

3. Generate build using *cmake*
```bash
$ cmake -S . -B build -G "Unix Makefiles"
```

4. Build
```bash
$ cmake --build build
```

5. Run the executable generated at root of the repository (*app.exe* or *app*)
