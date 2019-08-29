---
layout: page
subheadline: "Brett Crawford"
title: "XML encoding in Finereader"
teaser: "Seeing through the noise"
date: 2016-12-05
categories:
  - technical issues
author: williamcrawford
tags:
  - shortcuts
header: no
image:
  title: blog-images/crawfordXML.jpg
  thumb: blog-images/crawfordXML.jpg
  homepage: blog-images/crawfordXML.jpg
  caption:
  caption_url:

---
Balancing a logical, accessible, and user friendly xml-encodation of the Egyptian Gazette with preserving its historical visual format is a delicate enterprise. I initially tried to do this with a plaintext editor, and later directly within the Oxygen program itself. I found myself constantly switching between windows on my computer, going back and forth and then back again between the image of the page and the xml-in-progress. By chance, I had to go and re-OCR a page three about a month into the class, and discovered something that greatly decreased the time it took me to structure a page with XML tags.

By placing individual text boxes over individual paragraphs on the page, Finereader would output the OCRed text in a form that was sectionally pre-divided within the plain-text-viewer. By easily distinguishing the divisions with physical space, it allowed me to rapidly go through and paste repetitive structural elements. Additionally, the image of the page (that would automatically relocate to the plain text's location when I selected it) that was always visible aided me in determining how exactly to structure the divisions to both best maintain the paper's original appearance and take advantage of the power of XML coding to analyze it. I then used Oxygen to functionally check and edit the code. Combined, I found that these factors greatly reduced the amount of time it took me to structurally code the text.
