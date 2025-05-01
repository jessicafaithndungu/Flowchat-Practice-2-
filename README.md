flowchart TD
    A[Start] --> B[Input N]
    B --> C[Initialize i = 1]
    C --> D[Initialize totalSum = 0]
    D --> E[Initialize totalCount = 0]
    E --> F{Is i < N?}
    F -- Yes --> G{Is i odd?}
    G -- Yes --> H[Print i]
    H --> I[Increase totalSum by i]
    I --> J[Increase totalCount by 1]
    J --> K[Increase i by 1]
    K --> F
    G -- No --> L[Increase i by 1]
    L --> F
    F -- No --> M[Print totalSum and totalCount]
    M --> N[End]
