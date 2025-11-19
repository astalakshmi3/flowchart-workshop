flowchart TD
A([Start]) --> B[/Input amount/]
B --> C{amount > 1000?}
C -->|Yes| D[discount = amount × 0.10]
D --> E[final = amount - discount]
C -->|No| F[final = amount]
E --> G[/Display final/]
F --> G
G --> H([End])