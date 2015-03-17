Slug: floating-boxes-in-rows
Date: 2007-07-24
Title: Floating Boxes in Rows
layout: post

Last week I ran into an IE6/7 CSS bug, but in 5 hours of research did not find a solution I liked. In a nutshell, IE incorrectly implements, or incorrectly interprets, the CSS 2.1 float spec:

>The outer top of a floating box may not be higher than the outer top of any block or floated box generated by an element earlier in the source document. [CSS 2.1 Visual formatting model, rule 5](http://www.w3.org/TR/CSS21/visuren.html#flow-control)

Read more about it in the bug demo page: [Float Boxes in Rows](
http://static.monkinetic.com/files/tmp/css/floated-box-rows.html). I&#39;d really appreaciate some feedback in the comments if you have any ideas.

<p style="background-color:#fdd; padding: 10px; color: #333; font-size: 9pt;">UPDATE: It appears that Bruno Fassino has a <a href="http://www.brunildo.org/test/ImgThumbIBL.html">thumbnail page that may demonstrate a way to solve this problem</a>, though I&#39;ve not yet had time to inspect it carefully enough that I&#39;d feel comfortable implementing it.</p>