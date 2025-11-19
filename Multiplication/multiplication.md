flowchart TD

A([Start]) --> B[/Input num/]
B --> C[i = 1]
C --> D{Is i <= 10?}
D -->|Yes| E[/Display num × i/]
E --> F[i = i + 1]
F --> D
D -->|No| G([End])
