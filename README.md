# POKE
classDiagram
    direction TB

    class Pokemon {
        +name: str
        +type: str
        +health_points: int
        +base_strength: float
        +level: int
        +defense_capacity: float
        +appearance: str
        +special_ability: str
        +attacks: list
        +evolution_stage: int

        +attack(target: Pokemon): void
        +defend(): void
        +evolve(): void
    }
