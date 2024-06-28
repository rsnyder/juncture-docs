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
