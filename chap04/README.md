# 築基功法

* 基本功法
* 五弓大展
* 

```sequence
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow
```

```sequence-hand
Title: Here is a title
A->B: Normal line
B-->C: Dashed line
C->>D: Open arrow
D-->>A: Dashed open arrow
```


```mermaid
graph LR
    A[Square Rect] -- Link text --> B((Circle))
    A --> C(Round Rect)
    B --> D{Rhombus}
    C --> D
```



```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```


```mermaid
graph TD
id1
id1[This is the text in the box]
id1(This is the text in the box);
 id1((This is the text in the circle));
    id1>This is the text in the box]
        id1{This is the text in the box}

```

```mermaid
graph LR
A-->B
A --- B
A-- This is the text --- B
A---|This is the text|B;
-.->
==>
```

```mermaid
graph TB
    sq[Square shape] --> ci((Circle shape))

    subgraph A subgraph
        od>Odd shape]-- Two line<br>edge comment --> ro
        di{Diamond with <br/> line break} -.-> ro(Rounded<br>square<br>shape)
        di==>ro2(Rounded square shape)
    end

    %% Notice that no text in shape are added here instead that is appended further down
    e --> od3>Really long text with linebreak<br>in an Odd shape]

    %% Comments after double percent signs
    e((Inner / circle<br>and some odd <br>special characters)) --> f(,.?!+-*ز)

    cyr[Cyrillic]-->cyr2((Circle shape Начало));

     classDef green fill:#9f6,stroke:#333,stroke-width:2px;
     classDef orange fill:#f96,stroke:#333,stroke-width:4px;
     class sq,e green
     class di orange
     
```



| 0:0 | 1:0 | 2:0 | 3:0 | -- |
| -- | -- | -- | -- | -- |
| 0:2 | 1:2 | 2:2 | 3:2 | 4:2 |
| 0:3 | 1:3 | 2:3 | 3:3 | 4:3 |
| 0:4 | 1:4 | 2:4 | 3:4 | 4:4 |
| 0:5 | 1:5 | 2:5 | 3:5 | 4:5 |
