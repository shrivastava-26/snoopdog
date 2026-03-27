```mermaid
flowchart TD
    A[Write code] --> B[Run tests]
    B --> C{Tests pass?}
    C -- Yes --> D[Commit code]
    C -- No --> E[Fix issues]