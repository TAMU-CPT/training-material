---
layout: tutorial_hands_on
topic_name: additional-analyses
tutorial_name: How_to_extract_SVG_from_X-Vis_in_Galaxy
---

> ### Agenda
>
> 1. Background
> 2. Procedure
>
{: .agenda}

# Background
The X-Vis from GFF3/FASTA workflow generates an HTML output as shown in figure 1. In order to save this graphic, especially for publication use, it is not sifficient to take a screenshot. A workaround has been found enabling the extraction of an SVG file.

|Figure 1. X-Vis dataset as viewed in Galaxy.|
|:--:|
|![](../../images/How_to_extract_SVG_from_X-Vis_in_Galaxy/1_x-vis_view_galaxy.png)|

# Procedure

1. With the mouse pointer over the HTML image in Galaxy (green bar and arrows in center pane of figure 1), right click and select "Inspect Element". This will bring up a new window with the HTML code as shown in figure 2 (blue arrow). The code describning the field in which the graphic is displayed will be highlighted, as shown in figure 2 (red arrow). The line of code above this, beginning with ">svg width" contains the SVG data. Right click on that line and then select Copy>>Copy Outer HTML as shown in figure 3 red arrow).

|Figure 2. Inspect Element dialog box (blue arrow) showing highlighted element (red arrow).|
|:--:|
|![](../../images/How_to_extract_SVG_from_X-Vis_in_Galaxy/2_inspect_element.png)|

|Figure 3. Copy menu showing "Outer HTML" option.|
|:--:|
|![](../../images/How_to_extract_SVG_from_X-Vis_in_Galaxy/3_copy_outer_HTML.png)|

2. Open your favorite SVG viewer. If you don't have one, you can use [this](https://www.svgviewer.dev/) one. Paste your copied code into the SVG viewer (figure 4) then save it as a .png (blue arrow) file. Some viewers, such as [SVG Viewer](https://www.svgviewer.dev/) also allow you to save the image as a .png file (red arrow). 

|Figure 4. PNG data in SVG Viewer.|
|:--:|
|![](../../images/How_to_extract_SVG_from_X-Vis_in_Galaxy/4_SVGViewer.png)|

