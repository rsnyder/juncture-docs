# Video Player

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

The `ve-video` tag creates a viewer that is able to play video content, including streaming video from YouTube and Vimeo.

## Attributes

### Resource attributes

**[alt](#examples)** (_string_):  The text to use in the _alt_ tag used by screen readers.  If not provided an _alt_ tag is automatically generated from the IIIF manifest label property or inferred from the filename.

**[autoplay](examples)** (_boolean_):  Automatically play video resource when the media viewer is loaded.

**[caption](#examples)** (_string_): Defines the text to use for a caption that is displayed below the video player.

**[end](#examples)** (_number_): Time position to stop playing resource.

**[id](#examples)** (_number_): The YouTube or Vimeo ID of the image to stream.

**[muted](#examples)** (_boolean_):  Mute resource when initially played.

**[poster](#examples)** (_string_): Image displayed in viewer before video plays.

**[src](#examples)** (_url_) :  The URL to the IIIF manifest for a video file to play.

**[start](#examples)** (_number_):  Time position to begin playing resource.

## Examples

<ve-snippet collapsible label="YouTube video">
`video Zy3K2Lcw7hQ`
</ve-snippet>

<ve-snippet collapsible label="YouTube video with autoplay">
`video Zy3K2Lcw7hQ autoplay`
</ve-snippet>

<ve-snippet collapsible label="YouTube video with autoplay and start/end times">
`video Zy3K2Lcw7hQ autoplay start=60 end=70`
</ve-snippet>
