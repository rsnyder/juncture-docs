# Image Gallery

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

The `ve-gallery` displays an arbitrary number of image thumbnails in a grid.  By default only the thumbnail is displayed.  An image caption cah be shown using the `show-caption` boolean attribute.  When the thumbnail is clicked, the full image is shown in a popup window.

## Gallery Attributes

**[show-captions](#basic)** (_boolean_) : Displays the image caption below the thumbnail in the grid.

## Examples

<ve-snippet collapsible label="Basic gallery">
```
gallery
wc:Atrani_(Costiera_Amalfitana,_23-8-2011).jpg
wc:Costiera-amalfitana-_panorama_from_the_sea_129.jpg
wc:Amalfi_Coast_(247891371).jpeg
wc:Amalfi_Coast_(Italy,_October_2020)_-_73_(50557616528).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_72_(50558479917).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_14_(50558382446).jpg
```
</ve-snippet>

<ve-snippet collapsible label="Gallery with captions enabled">
```
gallery show-captions
wc:Atrani_(Costiera_Amalfitana,_23-8-2011).jpg
wc:Costiera-amalfitana-_panorama_from_the_sea_129.jpg
wc:Amalfi_Coast_(247891371).jpeg
wc:Amalfi_Coast_(Italy,_October_2020)_-_73_(50557616528).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_72_(50558479917).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_14_(50558382446).jpg
```
</ve-snippet>