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

## Attributes

**[autoplay](#basic)** (_boolean_) :  

**[caption](#basic)** (_string_) :  The carousel will automatically advance when the `autoplay` attribute is used. To change how long a slide is shown before advancing, set autoplay-interval to the desired number of milliseconds. For best results, use the loop attribute when autoplay is enabled. Note that autoplay will pause while the user interacts with the carousel.

**[height](#basic)** (_number__) :  

**[loop](#basic)** (_boolean_) :  By default, the carousel will not advanced beyond the first and last slides. You can change this behavior and force the carousel to “wrap” with the `loop` attribute.

**[navigation](#basic)** (_boolean_) :  Use the `navigation` attribute to show previous and next buttons.

**[pagination](#basic)** (_boolean_) :  Use the `pagination` attribute to show the total number of slides and the current slide as a set of interactive dots.

**[width](#basic)** (_number__) :  

## Examples

<ve-snippet collapsible label="Basic carousel">
```
carousel navigation caption="A Basic Carousel"
wc:Atrani_(Costiera_Amalfitana,_23-8-2011).jpg "Image 1 caption"
wc:Costiera-amalfitana-_panorama_from_the_sea_129.jpg "Image 2 caption"
wc:Amalfi_Coast_(247891371).jpeg
wc:Amalfi_Coast_(Italy,_October_2020)_-_73_(50557616528).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_72_(50558479917).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_14_(50558382446).jpg
```
</ve-snippet>

<ve-snippet collapsible label="Basic carousel with pagination">
```
carousel navigation pagination caption="A Basic Carousel"
wc:Atrani_(Costiera_Amalfitana,_23-8-2011).jpg "Image 1 caption"
wc:Costiera-amalfitana-_panorama_from_the_sea_129.jpg "Image 2 caption"
wc:Amalfi_Coast_(247891371).jpeg
wc:Amalfi_Coast_(Italy,_October_2020)_-_73_(50557616528).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_72_(50558479917).jpg
wc:Amalfi_Coast_(Italy,_October_2020)_-_14_(50558382446).jpg
```
</ve-snippet>
