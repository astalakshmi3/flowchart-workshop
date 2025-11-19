flowchart TD
A([Start]) --> B[/Input n/]
B --> C[fact = 1, i = 1]
C --> D{Is i <= n?}
D -->|Yes| E[fact = fact × i]
E --> F[i = i + 1]
F --> D
D -->|No| G[/Display fact/]
G --> H([End])