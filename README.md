# Trunkle

Truncate block-level DOM elements. There are no enhanced DOM pat-downs in trunkle.

## Examples

    $('article').trunkle();
    $('article').trunkle({collapsedHeight: "5em"});
    $('article').trunkle({collapsedHeight: "250px"});

### Settings

Trunkle provides a few settings you can tweak.

    $('article').trunkle({
      moreText: "MORE MORE MORE",
      lessText: "shrink this",
      expandedClass: "bigger",
      collapsedClass: "smaller",
      contentContainer: '<div class="mega-content"></div>',
      collapsedHeight: "400px",
      expandedHeight: "50em"
    });


#### Defaults

  * moreText: "show more »"
  * lessText: "« show less"
  * expandedClass: "trunkle-expanded"
  * collapsedClass: "trunkle-collapsed"
  * contentContainer: '&lt;div class="truncate-content"&gt;&lt;div&gt;'
  * collapsedHeight: "100px"
  * expandedHeight: $(this).css("height")
