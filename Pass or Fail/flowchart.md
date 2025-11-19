flowchart TD
A([Start]) --> B[/Input average/]
B --> C{average >= 50?}
C -->|Yes| D[/Display "Pass"/]
C -->|No| E[/Display "Fail"/]
D --> F([End])
E --> F