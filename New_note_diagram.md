```mermaid
sequenceDiagram
    participant browser
    participant server

    broswer->>server: GET https://studies.cs.helsinki.fi/exampleapp/notes
    activate server
    server-->>browser: HTML document
    deactivate server

```