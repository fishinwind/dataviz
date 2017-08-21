
# Your axis labels are too small {#small-axis-labels}

If you take away only one single lesson from this book, make it this one: Pay attention to your axis labels, axis tick labels, and other assorted plot annotations. Chances are they are too small. In my experience, nearly all plot libraries and graphing softwares have poor defaults. If you use the default values, you're almost certainly making a poor choice.

For example, consider the following figure. I see figures like this all the time.
<img src="small_axis_labels_files/figure-html/unnamed-chunk-2-1.png" width="576" style="display: block; margin: auto;" />
The axis labels, axis tick labels, and legend labels are all incredibly small. We can barely see them, and we may have to zoom into the page to distinguish FWD from RWD in the figure legend.

A somewhat better version of this figure would be this one:
<img src="small_axis_labels_files/figure-html/unnamed-chunk-3-1.png" width="576" style="display: block; margin: auto;" />
I think the fonts are still too small, and that's why I have labeled it "ugly". However, we are moving in the right direction, and this figure might be passable under some circumstances. My main criticism with this figure is not so much that the labels aren't legible as that it is not balanced; the text elements are too small compared to the rest of the figure.

The next figure uses the default settings I'm applying throughout this book. I think it is well balanced, the text is clearly visible, and it fits with the overall size of the figure. 
<img src="small_axis_labels_files/figure-html/unnamed-chunk-4-1.png" width="576" style="display: block; margin: auto;" />

Importantly, we can overdo it and make the labels too big:
<img src="small_axis_labels_files/figure-html/unnamed-chunk-5-1.png" width="576" style="display: block; margin: auto;" />
Sometimes we need big labels, in particular if the figure is meant to be reduced in size, but the various elements of the figure (in particular, label text and plot symbols) need to fit together. In the above example, the points used to visualize the data are too small relative to the text. Once we fix this, the figure becomes acceptable again:

<img src="small_axis_labels_files/figure-html/unnamed-chunk-6-1.png" width="576" style="display: block; margin: auto;" />
You may look at this figure and find everything too big. However, keep in mind that it is meant to be scaled down. Scale it down so that it is only an inch or two in width, and the figure looks just fine. In fact, at that scaling this is the only figure in this chapter that looks good.

<div class="rmdtip">
<p>Always look at scaled-down versions of your figures to make sure the axis labels are appropriately sized.</p>
</div>


I think there is a simple psychological reason for why we routinely make figures whose axis labels are too small, and it relates to large, high-resolution computer monitors. We routinely preview figures on the computer screen, and often we do so while the figure takes up a large amount of space on the screen. In this viewing mode, even comparatively small text seems perfectly fine and legible, and large text can seem awkward and overpowering. In fact, if you take the first figure from this chapter and magnify it to the point where it fills your entire screen, you will likely think that it looks just fine. The solution is to always make sure that you look at your figures at a realistic print size. You can either zoom out so they are only three to five inches in width on your screen, or you can go to the other side of your room and check whether the figure still looks good from a substantial distance.