---
layout: post
title: Chrome Tabs Slide With Constant Deceleration
---
After an exciting few days of popular writing, I have to announce, with great sadness, that I have to go back for now. I thought of writing an epilogue to the Uttarakhand series for the sake of completeness, but got bored halfway and turned it into a fictional short story.

So, today, we will be finding out the equations of motion of the tabs of the popular web browser, Google Chrome. Absolute pointlessness.
When you drag a Chrome tab in the same window, and let it go, it slides back to where it was before.
<img src="https://dl.dropboxusercontent.com/u/83489788/c1.png" width="100%</img" >
<img src="https://dl.dropboxusercontent.com/u/83489788/c2.png" width="100%</img" >
My scheme was to drag the tab to one end and take lots of screenshots (like the ones above) as it slid back. I then tracked the tab with these images.
It takes about 0.14 seconds for a tab to slide back to zero position if you leave it from the end. I managed to get 61 screenshots within that time using the GIMP Drawing Kit library. A few minutes later with PIL and matplotlib, I got this:

<img src="https://dl.dropboxusercontent.com/u/83489788/figure_1.png" width="100%" ></img>The x-axis is the time and the y-axis is displacement from the rest position. The smooth curve is the (quadratic) polynomial approximation.?Specifically, the deceleration according to my calculations is 97,449 pixels/second^2. The starting velocity is 13,751 pixels/second.

This was probably not the best way to find this out. If anyone has other ideas, feel free to mock me.

PS: My screen resolution is 1366x768 and refresh rate was 60Hz. I thought of increasing my refresh rate but didn't finally.
