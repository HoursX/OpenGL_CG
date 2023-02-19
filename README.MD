# OpenGL_CG

## Game Engine Layer

five Layers + One 3rd Party Libraries

### Tool Layer

> Chain of Editors

### Function Layer

> Make It Visible, Movable and Playable.

1. How to Make the World Alive.

2. Dive into Ticks.

```cpp

void tickMain(float delta_time)
{
    while(!exit_flag)
    {
        tickLogic(delta_time);
        tickRender(delta_time);
    }
}

```

3. Heavy-duty Hotchpotch.

4. Multi-Threading.

Entry      - Fixed Thread

Mainstream - Thread Fork/Join

Advanced   - JOB System

### Resource Layer

> Data and Files

1. How to Access My Data.

2. Runtime Asset Manager.

3. Manage Asset Life Cycle.

### Core Layer

> Swiss Knife of Game Engine

1. Math Library.

2. Math Effciency.

3. Data Structure and Containers.

4. Memory Management.

### Platform Layer

> Launch on Different Platforms

### 3rd Party Libraries

> Middleware and 3rd Party Libraries
