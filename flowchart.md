# Flowchart

### A node (default)
```mermaid
graph LR
    id
```
## Node Shapes

### A node with text
```mermaid
graph LR
    id[This is the text in the box]
```
### A node with round edges
```mermaid
graph LR
    id(This is the text in the box)
```
### A stadium-shaped node
```mermaid
graph LR
    id([This is the text in the box])
```
### A node in a subroutine shape
```mermaid
graph LR
    id[[This is the text in the box]]
```
### A node in a cylindrical shape
```mermaid
graph LR
    id[(Database)]
```
### A node in the form of a circle
```mermaid
graph LR
    id((This is the text in the circle))
```
### A node in an asymetric shape
```mermaid
graph LR
    id>This is the text in the box]
```
### A node (rhombus)
```mermaid
graph LR
    id{This is the text in the box}
```
### A hexagon node
```mermaid
graph LR
    id{{This is the text in the box}}
```
### Parallelogram
```mermaid
graph TD
    id[/This is the text in the box/]
```
### Parallelogram alt
```mermaid
graph TD
    id1[\This is the text in the box\]
```
### Trapezoid
```mermaid
graph TD
    A[/Christmas\]
```
### Trapezoid alt
```mermaid
graph TD
    B[\Go shopping/]
```

## Links between nodes
### A link with arrow head
```mermaid
graph LR
    A-->B
```
### An open link
```mermaid
graph LR
    A --- B
```
### Text on links
```mermaid
graph LR
    A-- This is the text! ---B
```
or
```mermaid
graph LR
    A---|This is the text|B
``` 
### A link with arrow head and text
```mermaid
graph LR
    A-->|text|B
```







```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
    style C fill:#f9f,stroke:#333,stroke-width:4px
    style B fill:#bbf,stroke:#f66,stroke-width:2px,color:#fff,stroke-dasharray: 5 5
```