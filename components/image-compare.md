# Image Compare

<style> 
    .markdown-section h2 ~ p > strong > a { color: crimson; font-size: 110%; text-decoration: none; }
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

The `ve-image-compare` creates a viewer that is able to display 2 high-resolution in a stacked compare viewer.

## Examples

<ve-snippet collapsible label="Bedroom in Arles">
```
compare caption="Comparison of Van Gogh Sketch and Painting"
wc:Vincent_van_Gogh_-_Vincent's_Bedroom_in_Arles_-_Letter_Sketch_October_1888.jpg
wc:Vincent_van_Gogh’s_famous_painting,_digitally_enhanced_by_rawpixel-com_49.jpg
```
</ve-snippet>
