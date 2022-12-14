# Git playground
## Diagram JWT
```mermaid
sequenceDiagram
	Client-->>Server: Wants to autenticate,<br>sends over email and password
	Note right of Server: Checks if email and password<br>matches. If so, creates JWT with <br>necessary user and token<br>information, encrypted with<br>secret key, only<br>known by server.
	Server->>Client: Sends back encrypted JWT
	Note left of Client: Stores JWT<br>in browser.
	Client-->>Server: Requests access to webpage
	Note right of Server: Authorizes by checking if<br>header and payload matches<br>signature of recieved JWT when<br>encrypted with secret key.
	Server->>Client: If authorized,<br>sends back requested files
	
```
```javascript
let num = 7;
```

```JAVA
float decimal = 0.5;
```

![giraffe](https://images.unsplash.com/photo-1626548307930-deac221f87d9?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=834&q=80)


[Visit google](https://www.google.com)

|Headline|Headline|
|---|---|
|Text|Text|
|Text|Text|

**This is** bold and *this is* italic

:star: Gold star

---

Horizontal line above

- Item 1
- Item 2
- Item 3

> This is a blockquote

```mermaid
erDiagram
    CUSTOMER ||--o{ ORDER : places
    CUSTOMER {
        string name
        string custNumber
        string sector
    }
    ORDER ||--|{ LINE-ITEM : contains
    ORDER {
        int orderNumber
        string deliveryAddress
    }
    LINE-ITEM {
        string productCode
        int quantity
        float pricePerUnit
    }
```

```mermaid
classDiagram
    Animal <|-- Duck
    Animal <|-- Fish
    Animal <|-- Zebra
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Duck{
        +String beakColor
        +swim()
        +quack()
    }
    class Fish{
        -int sizeInFeet
        -canEat()
    }
    class Zebra{
        +bool is_wild
        +run()
    }
 ```

`This` is a highlighted word.

```mermaid
sequenceDiagram
    Alice->>John: Hello John, how are you?
    John-->>Alice: Great!
    Alice-)John: See you later!
```

