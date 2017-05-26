# TEI Workshop for the ARL Digital Scholarship Institute  

## Prep Before the Workshop

### Download and install Oxygen XML Editor
* http://www.oxygenxml.com/download.html
* See email sent by mdalmau@indiana.edu for the License Key 
* If you need help installing Oxygen, email me so that we can install at the Connors Center before June 8th. 

### Required Browsers
* Firefox
* Internet Explorer
* Safari

*Microsoft Edge or Google Chrome **will not work** for Activity 4.* 

### Reading (Optional)
* [Electronic Texts: Audiences and Purposes](http://www.digitalhumanities.org/companion/view?docId=blackwell/9781405103213/9781405103213.xml&chunk.id=ss1-3-6&toc.depth=1&toc.id=ss1-3-6&brand=9781405103213_brand) by Perry Willett in A Companion to Digital Humanities (2004)

## Workshop Materials

* Link to presentation slides

### Activity 1 (15 minutes)
* Part 1: In groups, observe how the markup impacts the interface and functionality of each site; determine approaches to digital edition-making (7 mins)
  * Chymistry of Isaac Newton: http://chymistry.org
  * Victorian Women Writers Project: http://www.dlib.indiana.edu/collections/vwwp
  * Indiana Authors and Their Books: http://www.dlib.indiana.edu/collections/inauthors  
* Part 2: Re-convene as a whole and discuss observations and findings (8 mins)

### Activity 2 (10 minutes)
* Part 1: Conduct document analysis on the the excerpt of *Jackanapes and the Brownies*; **annotate the handout**. (5 mins)
  * [Page 1 of handout](https://github.com/mdalmau/tei-workshop-arl/blob/master/activity2_jackanapes_VAB6984_docanalysis.pdf)  contains sample questions to aid in document analysis.
* Part 2: Discuss observations and findings (5 mins)

### Activity 3 (30 minutes)
* Encode 2 pages from *Jackanapes and the Brownies* (30 mins)

  1. [Open PDF of Chapter 1 excerpt](https://github.com/mdalmau/tei-workshop-arl/blob/master/activity3_jackanapes_VAB6984_encoding.pdf) for copying and pasting text  
  2. Launch Oxygen XML Editor 
  3. File => New => TEI P5 
  4. Select All [TEI P5]
  5. Save file to your Desktop; name file: **jackanapes.xml**
     * (Brief review Oxygen XML Editor and the TEI Schema)
  6. Begin encoding *all together;* Michelle will walkthrough the encoding with the class

As back-up, you can download a TEI template to open in Oxygen for encoding:
* https://github.com/mdalmau/tei-workshop-arl/blob/master/activity3_template.xml (Right-Click / CTRL-Click link and select "download file as." Download file to Desktop and follow step 5.) 

Finished encoded sample for your review:
* https://github.com/mdalmau/tei-workshop-arl/blob/master/activity3_jackanapes_VAB6984.xml

### Activity 4 (20 minutes)
* Part 1: Publish 2 pages encoded from *Jackanapes and the Brownies* (10 mins)

  1. Download TEI Boilerplate: https://github.com/GrantLS/TEI-Boilerplate
     * Click on the green "Clone or download" button
     * Select "Download Zip"
  2. Go to your Downloads folder and move "TEI-Boilerplate-master" folder to your Desktop
  3. Launch Oxygen XML Editor
  4. File => Open => **jackanapes.xml** (on your Desktop)
  5. Copy and paste the following after ```<?xml version="1.0" encoding="UTF-8"?>```:
     * ```<?xml-stylesheet type="text/xsl" href="teibp.xsl"?>```
  6. File => Save As and navigate to Desktop to the "TEI-Boilerplate-master/dist/content" folder
  7. Launch Firefox, Internet Explorer or Safari
  8. File => Open => and navigate to Desktop to the "TEI-Boilerplate-master/dist/content" folder
  9. Select **jackanapes.xml**
  10. Ta-da! You have "published" the TEI encoding you completed in Activity 3!!
    
As back-up, you can download a TEI-Boilerplate-ready XML file and then follow steps 6-10: 
https://github.com/mdalmau/tei-workshop-arl/blob/master/activity3_jackanapes_VAB6984.xml (Right-Click / CTRL-Click link and select "download file as." Follow steps 6-10.) 

* Part 2: Discussion: Compare two online publications of the same text (20 mins)
  * To see the whole book, *Jackanapes and the Brownies,* encoded and rendered in TEI Boilerplate, download the following file and then follow steps 6-10 above: https://github.com/mdalmau/tei-workshop-arl/blob/master/activity4_jackanapes_VAB6984.xml (Right-Click / CTRL-Click link and select "download file as." Follow steps 6-10.) 
  * Open a NEW Browser Window: http://purl.dlib.indiana.edu/iudl/vwwp/VAB6984

## Reference & Training Resources

### General Intros to Markup, XML and TEI
* Walsh. J. (2014). [A brief introduction to Markup, Part 1](https://www.youtube.com/watch?v=Z2Nsq613uHk) (about 15 minutes).
* Walsh. J. (2014). [A brief introduction to Markup, Part 2](https://www.youtube.com/watch?v=JhhKyyP0e18) (about 14 minutes).
* Exercises referenced in videos can be downloaded: http://dcl.ils.indiana.edu/intromarkup/

### TEI
* [TEI Guidelines](http://www.tei-c.org/release/doc/tei-p5-doc/en/html/)
* [TEI-L Mailing List](https://listserv.brown.edu/archives/cgi-bin/wa?SUBED1=tei-l&A=1)
* [Best Practices for TEI in Libraries] (http://purl.org/TEI/teiinlibraries): a guide for mass digitization, automated workflows, and promotion of interoperability with XML using the TEI
* [Women Writers Project (WWP) Training Resources](https://www.wwp.northeastern.edu/outreach/resources/index.html)
* [TEI by Example](http://teibyexample.org/)
* [TEI Boilerplate Workshop and Sample Exercises](http://dcl.slis.indiana.edu/teibpws/)

### Document Analysis 
* [WWP Document Analysis Worksheet](https://www.wwp.northeastern.edu/outreach/seminars/_current/handouts/document_analysis.xhtml)



