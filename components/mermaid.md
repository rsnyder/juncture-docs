# Mermaid Diagram Viewer

<style> 
    .markdown-section h3 ~ p > strong > a { color: crimson; font-size: 110%; text-decoration: none; }
    .markdown-section table { 
        margin-left:3rem; 
        width: calc(100% - 6rem); 
        border:1px solid #555;
    }
    .markdown-section td, .markdown-section th {
        border:1px solid #555;
        padding: 8px;
        line-height: 1.2;
    }
    .markdown-section th {
        background-color:#E2F0F7;
        font-weight:bold !important;
        text-align:center !important;
    }
</style>

The `ve-mermaid` tag uses the [Mermaid.js](https://mermaid.js.org/) JavaScript library to create diagram visualizations. With this tag, you can create charts and diagrams with Markdown-inspired text definitions used by Mermaid. [This page](https://mermaid.js.org/intro/#diagram-types) will show you the different diagram types supported by Mermaid that you can include in your visual essay.

### Diagram Syntax
To create your visualization using `ve-mermaid`, write a diagram or chart following the syntax of Mermaid JS. Below is a list of guides to writing different diagrams on  [Mermaid.js](https://mermaid.js.org/). Once you have your diagram code, include it underneath the `.ve.mermaid` tag with one right indent. (Note: if the diagram code is not indented to the right of  `.ve-mermaid` , the diagram will not show.) 

- [MermaidJS Diagram Syntax Structure Overview](https://mermaid.js.org/intro/n00b-syntaxReference.html)
- [Flowchart Syntax](https://mermaid.js.org/syntax/flowchart.html)
- [Sequence Diagram Syntax](https://mermaid.js.org/syntax/sequenceDiagram.html)
- [Class Diagram Syntax](https://mermaid.js.org/syntax/classDiagram.html)
- [State Diagram Syntax](https://mermaid.js.org/syntax/stateDiagram.html)
- [Pie Chart Syntax](https://mermaid.js.org/syntax/pie.html)
- [Mind Map Syntax](https://mermaid.js.org/syntax/mindmap.html)

## Examples

<ve-snippet collapsible label="Basic Mermaid diagram">
```
mermaid
graph TD
    A((Indigenous Amazonians)) --- B((Ayahuasca))
    F((New Age Practitioners)) --- B
    G((Syncretic Religions)) --- B
    H((Tourists)) --- B
    I((Western Researchers)) --- B
    A --- C((RELIGIOUS OR SPIRITUAL))
    A --- D((MEDICINAL))
    A --- E((ECONOMIC))
    F --- C
    F --- D
    F --- E
    G --- C
    G --- D
    H --- C
    H --- D
    H --- E
    I --- D
```
</ve-snippet>

Below is an example of a pie chart

<ve-snippet collapsible label="Mermaid Pie Chart example">
```
mermaid
pie title Pets adopted by volunteers
    "Dogs" : 386
    "Cats" : 85
    "Rats" : 15
```
</ve-snippet>

Below is an example of a mind map

<ve-snippet collapsible label="Mermaid Mind Map example">
```
mermaid
mindmap
root
  A
    B
    C
```
</ve-snippet>
