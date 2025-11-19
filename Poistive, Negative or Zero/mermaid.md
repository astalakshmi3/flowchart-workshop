flowchart TD
A([Start]) --> B[/Input num/]
B --> C{num > 0?}
C -->|Yes| D[/Display "Positive"/]
C -->|No| E{num < 0?}
E -->|Yes| F[/Display "Negative"/]
E -->|No| G[/Display "Zero"/]
D --> H([End])
F --> H
G --> H
