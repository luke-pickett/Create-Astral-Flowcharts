```mermaid
flowchart LR
    Cobble --> Gravel
    Gravel --> Sand
    WetSponge --> Mixer
    Sand --> Mixer

    Mixer --> ClayBlocks
    Mixer --> DrySponge
    DrySponge --> Washer
    Washer --> WetSponge
    ClayBlocks --> Melter

    Gravel --> Flint --> Trash
    Gravel --> Clay
    Clay --> Melter

    Melter --> Brick
    Brick --> Compactor
    Compactor --> BrickBlocks

    Charcoal --> Melter
```
