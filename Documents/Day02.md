
<img src = /Images/R4R_header.png>

### Day 02: Biological Data Analysis Using R

### Time & Date: 

9am to 6pm on Feb 25, 2019

### Venue: 
Casuarina Hall <a href = https://www.indiahabitat.org/>India Habitat Centre, New Delhi</a>

### Instructors: 

<a href= http://www.nipgr.res.in/research/dr_gyadav.php>Dr Gitanjali Yadav | University of Cambridge/NIPGR</a>

<a href=https://www.cruk.cam.ac.uk/author/ashley-sawle>Dr Ashley Sawle | Cancer Research UK</a>

### Helpers: 

* Mr. Nagendra Singh, <a href=http://www.nipgr.ac.in/home/home.php>NIPGR</a>
* Mr. Priyesh Agarwal, <a href=http://www.nii.res.in/>NII</a>
* Ms. Saumya Priyadarshini, <a href=https://jnu.ac.in/scis>SCIS, JNU</a>

### General Information
  
###### <a href="http://datacarpentry.org">Data Carpentry</a> workshops are for any researcher who has data they want to analyze, and no prior computational experience is required. Participants will be encouraged to help one another and to apply what they have learned to their own research problems. The course is aimed at graduate students and other researchers.
  
###### ** *You don't need to have any previous knowledge of the tools that will be presented at the workshop*.
 
  
 ###### This hands-on workshop module under the <a href=/Images/Rollerbanner.jpg>TIGR2ESS R4R workshop</a> is a slight modification of the Data Carpentry Course at CRUK, University of Cambridge, and we hope to teach basic concepts, skills and tools for working more effectively with data.
  
  ###### We will cover Data organization in spreadsheets, and learn how to use the statistical program R.
  
  
### Requirements:
 ###### Participants will bring their own laptop with a Mac, Linux, or Windows operating system (not a tablet, Chromebook, etc.) that they have administrative privileges on. They should have a few specific software packages installed (listed <a href="#setup">below</a>). This can also be done after the course to re-engage with the materials. 

###### Participants are also required to abide by Data Carpentry's <a href="https://software-carpentry.org/blog/2012/12/code-of-conduct.html">Code of Conduct</a>

### Accessibility:
###### We are committed to making this workshop accessible to everybody. Please get in touch (using contact details below) if you have any special requirements.

###### Materials will be provided in advance of the workshop and large-print handouts are available if needed by notifying the organizers in advance.  If we can help making learning easier for you (e.g. sign-language interpreters, lactation facilities) please get in touch and we will attempt to provide them.

### Contact:
###### Please email <a href="mailto:gy@nipgr.ac.in">gy@nipgr.ac.in</a> for more information.

### Schedule
<img src=/Images/Day02.png alt=overview width=800 />

## BEFORE WE START

Data files for the lesson are available 
	  <a href="https://ndownloader.figshare.com/files/2252083">here</a>

<ol>
  <li><a href=/Documents/Day02_Intro.md>Introduction</a> (18 mins)</li>
  <li><a href=/Documents/Day02_Format.md>Formatting data</a> (35 mins)</li>
  <li><a href=/Documents/Day02_Problems.md>Common formatting problems</a> (20 mins)
  <li><a href=/Documents/Day02_Dates.md>Dates as data</a> (13 mins)</li>
  <li><a href=/Documents/Day02_Qty.md>Quality control</a> (20 mins)</li>
  <li><a href=/Documents/Day02_Exports.md>Exporting data</a> (10 mins)</li>
</ol>

## DATA ANALYSIS WITH R ( )

<ol>
  <li><a href="http://www.datacarpentry.org/R-ecology-lesson/00-before-we-start.html">Overview of R and Rstudio</a> </li>
  <li><a href="http://www.datacarpentry.org/R-ecology-lesson/01-intro-to-r.html">Introduction to R</a></li>
  <li><a href="http://www.datacarpentry.org/R-ecology-lesson/02-starting-with-data.html">Working with tabular data in R</a> </li>
</ol>

<hr>

## Setup

###### To participate in a Data Carpentry workshop, you will need access to the software described below. In addition, you will need an up-to-date web browser.

###### We maintain a list of common issues that occur during installation as a reference for instructors that may be useful on the <a href="https://github.com/swcarpentry/workshop-template/wiki/Configuration-Problems-and-Solutions">Configuration Problems and Solutions wiki page</a>.

## R 
###### <a href="http://www.r-project.org">R</a> is a programming language that is especially powerful for data exploration, visualization, and statistical analysis. 
###### To interact with R, we use <a href="http://www.rstudio.com/">RStudio</a>

### Windows 
###### <a href="https://www.youtube.com/watch?v=q0PjTAylwoU">See Video Tutorial</a> 
###### Install R by downloading and running <a href="http://cran.r-project.org/bin/windows/base/release.htm">this .exe file</a> from <a href="http://cran.r-project.org/index.html">CRAN</a> 
###### Also, please install the <a href="http://www.rstudio.com/ide/download/desktop">RStudio IDE</a>

###### [Note that if you have separate user and admin accounts, you should run the installers as administrator (right-click on .exe file and select "Run as administrator" instead of double-clicking). Otherwise problems may occur later, for example when installing R packages.]
 ### MacOS
 ###### <a href="https://www.youtube.com/watch?v=5-ly3kyxwEg">See Video Tutorial</a> 
 ###### Install R by downloading and running <a href="http://cran.r-project.org/bin/macosx/R-latest.pkg">this .pkg file</a>from <a href="http://cran.r-project.org/index.html">CRAN</a>. 
 ###### Also, please install the <a href="http://www.rstudio.com/ide/download/desktop">RStudio IDE</a>
  ### Linux
  ###### You can download the binary files for your distribution from <a href="http://cran.r-project.org/index.html">CRAN</a>. 
  ###### Or you can use your package manager:
  ###### (e.g. for Debian/Ubuntu run <code>sudo apt-get install r-base</code> 
  ###### and 
  ###### for Fedora run <code>sudo dnf install R</code>).  
  ###### Also, please install the <a href="http://www.rstudio.com/ide/download/desktop">RStudio IDE</a>
      
## End of Day 02
---
<a href="../Readme.md"><span class="glyphicon glyphicon-menu-left" aria-hidden="true"></span><span class="sr-only">Back To Main Menu R4R </span></a> | <a href="/Documents/Day01.md"><span class="glyphicon glyphicon-menu-right" aria-hidden="true"></span><span class="sr-only">Go To Previous Day</span></a> | <a href="/Documents/Day03.md"><span class="glyphicon glyphicon-menu-right" aria-hidden="true"></span><span class="sr-only">Go To Next Day</span></a>
--- | --- | ---


---


## Copyright &copy; 2016	
<a href="https://software-carpentry.org">Software Carpentry Foundation</a>
	<a href="mailto:lessons@software-carpentry.org">[Contact]</a>
     
