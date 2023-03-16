```mermaid
sequenceDiagram
    participant browser
    participant server

    browser->>server: POST https://studies.cs.helsinki.fi/exampleapp/new_note_spa
    Note right of browser: The browser send the post request to the server

    server-->>browser: The server send a success code to the browser and no refresh is needed since it use ajax call
```
