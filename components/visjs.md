# VisJS Diagram Viewer

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

<ve-snippet collapsible label="Basic VisJS diagram">

    |id |     label     |
    |---|---------------|
    | 1 | Node 1        |
    | 2 | Node 2        |
    | 3 | Node 3        |
    | 4 | Node 4        |
    | 5 | Node 5        |
    `#nodes`

    |from|to |
    |----|---|
    | 1 | 3  |
    | 1 | 2  |
    | 2 | 4  |
    | 2 | 5  |
    | 3 | 3  |
    `#edges`

    `ve-visjs edges=edges nodes=nodes caption="VisJS Graph"`

</ve-snippet>
