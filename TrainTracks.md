```
flowchart LR
    A[Cobble] --> B
    B[Smelter] --> C
    A --> C2
    C[RailAssembly] -->D[Output]
    C2[GrindWheelsx2] -->D2
    D2[Washing] --> E2
    D2 --> E22
    E2[Nuggets] --> C
    E22[Flint] --> Trash
```
