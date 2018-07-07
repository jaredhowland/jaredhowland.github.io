---
title: "Small Data Management: Master Data for Better Collection Analysis"
kind: presentation
permalink: /presentations/small-data-erl/
---
# Small Data Management: Master Data for Better Collection Analysis #

## Electronic Resources and Libraries 2018 Conference ##
Jared L. Howland

Given March 2018 in Austin <span class="caps">TX</span>

**Download:** [PowerPoint][] \| [PDF][] \| [Handout][]

![Slide 001][1]

Good afternoon! Thank you all for being here. I’m Jared Howland and I’m the collection development coordinator at Brigham Young University

![Slide 002][2]

Before I begin, I wanted to make sure that everyone who is live streaming this is able to access the files I'll be using today. You can get these by going to the conference scheduler. logging in, and downloading the files from the session page.

![Slide 003][3]

* Like all worthwhile presentations on data management, I want to start today by talking little about ancient Roman history.
* So, in ancient Rome, if Rome took over your country you were not automatically granted legal citizenship

![Slide 004][4]

* Before 212 <span class="caps">AD</span>, the primary way for imperial subjects to gain citizenship was to enlist in the Roman Army and serve for a minimum of 25 years
* After those 25 years, soldiers were granted a Roman military diploma to prove their citizenship. This diploma consisted of three parts:
* The first part was a decree issued by the Roman emperor and housed in the military archive, also at Rome

![Slide 005][5]

The second and third parts constituted the actual military diploma which was typically made from two bronze tablets and presented to the retired soldier, possibly in a ceremony

![Slide 006][6]

The front of the first plate would declare the veteran a legal Roman citizen

![Slide 007][7]

The reverse side of the first plate would have an exact copy of the text as the outer engraving

![Slide 008][8]

The inside of the second plate included the names of 7 witnesses that were sealed with organic material and then covered and protected by metal strips

![Slide 009][9]

After which, the two plates were bound with wire

![Slide 010][10]

And then sealed together

![Slide 011][11]

* To prove his citizenship, the retired soldier presented his diploma to the governor who would break the seal and confirm that the outside and inside texts matched and that the witness seals had not been tampered with
* They would compare this text with the one found in the military archive to confirm that the information was correct and not a forgery

![Slide 012][12]

* So 12 slides in and you are probably asking yourself, what on earth is this guy on about?
* The Roman military diploma highlights a few key principles that may guide us in our discussion about data today:

1. First, people have been thinking about how to store and verify information for a very, very long time. The Roman military diploma is an ancestor to the principle of master data management which we will discuss here in a bit. Though this is not a new problem, the scale and scope of technology to handle data continues to drastically change.
2. Second, librarians, like the archivists at the military archive in Rome, have also been thinking about data management problems for a very long time. The progression, and increasing importance, of ideas such as “big data” and “data management” over the last decade has demanded that librarians learn how to manage researchers’ data.

* A third reason is because I thought that this was a fascinating, quirky aspect of ancient Roman history. I first learned about this a few years ago when our library purchased a replica of a Roman military diploma. In fact, I approached our Special Collections about bringing this replica to show you all but they told me they would need to hire security to escort me to this conference. I thought about pursuing it further just to see what they would do but decided a few pictures would do for our purposes today.
* In any case, I’d like to take a step back and spend some time thinking about how we can manage our own data, rather than researchers’ data, to enhance our ability to make data-driven collection development decisions. We use a ton of data to help us make decisions. Not just usage or <span class="caps">COUNTER</span> usage data, but also enrollment data, class registration data, budget data, inflation data, etc. How we manage, analyze, and synthesize that data is often simply an afterthought. But carefully planning for how we manage this data can make our lives so much easier and provides far more opportunities for us to meaningfully visualize, interpret, and mix and match our data as needed.
* Now, I’d like to spend several minutes defining what I mean when I say “small data” as compared to “big data” as well as data management.
* **[IMAGE: CC0 Creative Commons License](https://pixabay.com/en/question-mark-important-sign-1872665/)**

![Slide 013][13]

* Big Data Definition: data sets that are so large or complex that traditional data processing application software is inadequate to deal with them
* Small Data Definition: data that is small enough for human comprehension. You don’t need algorithms or machine learning to understand what the data is telling you.
* Regardless of what you call it, or how big or small it is, all data have the same problems when you attempt to tame them

![Slide 014][14]
* Here are just a few examples of vexing data-related problems
* So to give you some concrete examples of these problems, here are a few rhetorical questions to help you decide if you have ever encountered a data management problem:

![Slide 015][15]
1. Have you ever had to wait for a colleague to get back from vacation to get data or numbers from them to finish a report you were working on?
2. Or similarly, have you ever had to contact a colleague for a data set that would be very useful if it were made available to everyone working in the library?
* **[IMAGE: CC0 Creative Commons License](https://pixabay.com/en/cinque-terre-italy-riomaggiore-town-3191829/)**

![Slide 016][16]

* Have you ever carefully compiled a report for your administration and then, a year later, not be able to recreate the same numbers when they needed an updated data set?
* Have you ever found a great data set to help you evaluate your collections and then not remember where you found it, or from whom you requested it?
* **[IMAGE: CC0 Creative Commons License](https://pixabay.com/en/files-paper-office-paperwork-stack-1614223/)**

![Slide 017][17]

* Have you ever run a report and then gotten wildly different data the next time you run the exact same report?
* Have you or a colleague ever lost important data when a single hard drive failed?
* **[IMAGE: Creative Commons Attribution-Share Alike 3.0 Unported](https://upload.wikimedia.org/wikipedia/commons/7/71/Destroyed_Hard_Drive.jpg)**

![Slide 018][18]

If you answered yes to any of those questions then you have encountered a data management problem. These may have been rhetorical questions, but they certainly are not hypothetical. I have encountered each of these, among many others.

![Slide 019][19]

* Once we finally realized these were recurring problems, we investigated ways to solve the immediate and pressing problems we had with data management (highlighted here in orange).
* We quickly learned that there are a lot of commercial solutions aimed at large corporations or built for really complex data. Those tools were far too much for what we needed. In fact, our university has several tools that would meet some of our needs, but they are not readily accessible to us, and, more importantly, fail to address all of the problematic scenarios I just presented.
* Most tools we found tried to manage the full data management lifecycle which is not something we were interested in pursuing. At least, not yet. We thought if we could just get a handle on a few of our data management problems we would be doing OK. With that background and contextual information out of the way, I want to cover some basic data management terminology.

![Slide 020][20]

* Data management is a broad field with a lot of components associated with it
* This data management wheel outlines a few of them as defined by the Data Management Association’s “Data Management Body of Knowledge” Framework (2<sup>nd</sup> edition) ([definitions from DAMA-DMBOK: Data Management Body of Knowledge (2<sup>nd</sup> Edition)](http://proquest.safaribooksonline.com.erl.lib.byu.edu/book/databases/business-intelligence/9781634622479/chapter-1-data-management/idparadest_19_html))
    * **Data governance**: Central to all of data management. Provides direction and oversight for data management by establishing a system of decision rights over data that accounts for the needs of the library
    * **Data architecture management**: the structure of a library’s logical and physical data assets and data management resources
    * **Data modeling & design**: is the process of discovering, analyzing, representing, and communicating data requirements in a precise form called the data model
    * **Database operations management**: includes the design, implementation, and support of stored data to maximize its value
    * **Data security management**: ensures that data privacy and confidentiality are maintained, that data is not breached, and that data is accessed appropriately
    * **Data warehousing & business intelligence management**: includes the planning, implementation, and control processes to manage decision support data and to enable librarians and other employees to get value from data via analysis and reporting
    * **Document & content management**: includes planning, implementation, and control activities used to manage the lifecycle of data and information found in a range of unstructured media
    * **Metadata management**: includes planning, implementation, and control activities to enable access to high quality, integrated metadata, including definitions, models, data flows, and other information critical to understanding data and the systems through which it is created, maintained, and accessed
    * **Data quality management**: includes the planning and implementation of quality management techniques to measure, assess, and improve the fitness of data for use within a library
    * **Reference and master data management**: includes ongoing reconciliation and maintenance of core critical shared data to enable consistent use across systems of the most accurate, timely, and relevant version of truth about essential activities

![Slide 021][21]

* As you can see, Master Data Management, or <span class="caps">MDM</span>, is one small component of the larger data management landscape.
* <span class="caps">MDM</span>: comprises the processes, governance, policies, standards, and tools that consistently define and manage the critical data of an organization to provide a single point of reference
* After learning about <span class="caps">MDM</span>, we felt that if we could just manage that portion of data management, we would be in a far better position to effectively evaluate and analyze our collections
* While analyzing the available tools, we found two that we thought might be most useful for our needs

![Slide 022][22]

* The first is GitHub, which many of you have probably heard of. It is a web-based tool built on a system called git which is a file version control system
* In short, it lets you track changes to documents over time and revert back to previous versions if you made a mistake or just need to see what things looked like in the past.
* It allows you to work on files without worrying you are going to mess something up and not be able to recover from it.
* The second tool we found is from the “Comprehensive Knowledge Archive Network,” or <span class="caps">CKAN</span>, and is open-source, web-based software for managing, storing, and distributing data. If you are familiar with data.gov, it uses <span class="caps">CKAN</span> for all of its datasets.
* There are pros and cons of each depending on your use case, budget, and technical expertise.

![Slide 023][23]

Other features:

1. There are both public and private data repositories
2. Fine-grained controls for who can and cannot read and write to the data repository are available
3. You can add comments and documentation to data sets and even to specific data points
4. There is a built-in troubleshooting ticket system
5. You can create different, parallel, versions of the same data set depending on the audience and how the data was analyzed

![Slide 024][24]

Other features:

1. There are both public and private data repositories
2. You can tag, group, and place data into organizations
3. Faceted searching is available for the entire data repository
4. <span class="caps">CKAN</span> has an accessible and understandable user interface
5. Extensions are available to greatly expand the default capabilities of the system, and if you have the technical expertise, you can build your own to meet a specific need

![Slide 025][25]

Let’s take a look at how we have used each of these systems. First, let’s review Github and how we have experimented with it as an <span class="caps">MDM</span> tool

![Slide 026][26]

We created a repository that includes all of our data sets. In this case, there are only 2 datasets: ‘arl’ and ‘serial-prices’

![Slide 027][27]

There are 3 branches for the data sets:

1. **Normalized**: data that has been cleaned up and normalized to make sure it is ready to be analyzed
2. **Projects**: a parallel data set that presents the data in different ways depending on the audience. A trivial example is a line chart vs a bar graph. In truth, we often use the same data in different contexts all the time. By having branches for a single data set, you can create as many variations and ways of interpreting the data without having to question where you got the data for the analysis from.
3. **Raw**: the raw data as you got it from the source

Below the branches you see documentation on how the Github repository is set up and organized for use as a rudimentary master data management system

![Slide 028][28]

So let’s take a look at our <span class="caps">ARL</span> data set

![Slide 029][29]

* The ‘arl’ directory includes the actual data, a README, and a SOURCE file.
* This is true of every data set we have in Github. The README is automatically shown below the list of files and describes how the data is organized, what each field in the data means, and how it is formatted
* There is also a SOURCE file, so let’s see what that is.

![Slide 030][30]

* So the SOURCE file simply tells you where you got the data from. In this case, it is from a single source but some data sets can be culled from multiple sources.
* Let’s go back and look at some of the actual data

![Slide 031][31]

Let’s say we are interested in the ‘collection-expenditures’ data. We click on that…

![Slide 032][32]

* and Github will show you a preview of the <span class="caps">CSV</span> file
* If you want to download the file, you can click on “Raw” and download the file

![Slide 033][33]

* So that's what things look like in a single branch. The other branches include similar documentation.
* For example, the normalized branch tells you what steps you took to clean up the data so you can clean up future data sets in the same way so that it is consistent.
* The projects branch will have multiple folders for each normalized data set and then within the folder you will have multiple versions of the same data. Again, the trivial example would be showing the data as a line graph in Excel versus a bar graph.

![Slide 034][34]

So, that's Github. Let’s talk a little about how we have been experimenting with <span class="caps">CKAN</span>

![Slide 035][35]

<span class="caps">CKAN</span> includes a lot of features:

1. There’s keyword searching for all datasets
2. Tags you can create for each data set

* The main navigation is available at the top: Datasets, Organizations, and Groups
* Let’s take a look at datasests

![Slide 036][36]

* You can see that searching datasets is still an option and now you also have facets available for narrowing your search down.
* We’ll come back to datasets in a minute but let’s take a quick look at organizations

![Slide 037][37]

* With organizations, you can have multiple departments in the library with their own organization. In this case we only have the collection development organization
* But we could add a cataloging organization or administration organization, for example, if we wanted
* Next is groups

![Slide 038][38]

* Groups are just a way to group your data into broad categories and might be helpful when you have more than the 13 datasets we currently have in <span class="caps">CKAN</span>
* Now, let’s go back and take a closer look at datasets

![Slide 039][39]

And let’s say we are interested in the “<span class="caps">BYU</span> Class Schedule” dataset, so let’s click on that one

![Slide 040][40]

* There is a brief explanation of the dataset available and then a list of the files associated with the dataset
* If you scroll down the page…

![Slide 041][41]

* You can see some metadata fields. Some are automatically generated and some are customizable. With extensions, you can add even more metadata fields if you need to.
* This is the metadata for the entire dataset. You can also create metadata for individual files if you want to describe or explain some quirk of the dataset only present in that one file. It includes information about who loaded the data set as well as who is in charge of the data set. If someone finds a problem with the data, or has a question, this will let them know who they need to contact to get it fixed.
* Let’s scroll back up and take a look at some other features.

![Slide 042][42]

If you click on explore…

![Slide 043][43]

* You have the option to preview or download the file
* Let’s preview it

![Slide 044][44]

* Just like Github, it will show you a preview of the file.
* From here you can also create rudimentary visualizations of the data by clicking on “Graph” so let’s do that.

![Slide 045][45]

* You can then select the data you want to be on which axes and pick the kind of graph you’d like to use to represent your data.
* You can also embed the file on another website by clicking “Embed” and copying the code into another site.
* Or you can click on the <span class="caps">URL</span> to download the full file.

![Slide 046][46]

* So that's an overview of <span class="caps">CKAN</span>. After running experiments with both of these systems, our library <span class="caps">IT</span> team notified us that they will not be able to support <span class="caps">CKAN</span> for us
* However, the university recently licensed the use of Box.com for all employees with unlimited storage. Box.com, for those who are unfamiliar with it, is a cloud-based file synchronization system and is a competitor to tools like Dropbox.
    * Box offers similar benefits to those we identified with Github and <span class="caps">CKAN</span> but is most similar, probably, to Github. A few benefits include the following:
    * Includes a web-based interface and desktop tools
    * Fine-grain controls over who can edit and view the data (allows read-only data)
    * Includes version control for documents
    * Allows for searching within data sets
    * Allows for custom metadata for files and folders
* Some of these features are available by default and others are extensions being implemented by our university <span class="caps">IT</span> department
* While <span class="caps">CKAN</span> is undoubtedly the best overall tool for managing data sets, there are lots of options if you plan carefully and document how you will be using a system. <span class="caps">CKAN</span> is more difficult to get up and running and to maintain so there are trade-offs there.

![Slide 047][47]

* So what are some suggested steps for anyone interested in hacking together a simple master data management system based on our experience? Here are a few suggestions: {READ SLIDE}

![Slide 048][48]

* So that is a quick overview of some tools we have been experimenting with at BYU to help us manage and analyze our collection development data.
* Thank you!
* **[IMAGE: CC0 1.0 Universal Public Domain Dedication](https://pixabay.com/en/question-mark-why-icon-blue-usa-1332062/)**


[PowerPoint]: {{ site.url }}/assets/images/presentations/files/small-data-erl/presentation_pptx.pptx
[PDF]: {{ site.url }}/assets/images/presentations/files/small-data-erl/presentation_pdf.pdf
[Handout]:  {{ site.url }}/assets/images/presentations/files/small-data-erl/handout_pdf.pdf

[1]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_001.jpg
[2]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_002.jpg
[3]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_003.jpg
[4]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_004.jpg
[5]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_005.jpg
[6]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_006.jpg
[7]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_007.jpg
[8]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_008.jpg
[9]:  {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_009.jpg
[10]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_010.jpg
[11]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_011.jpg
[12]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_012.jpg
[13]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_013.jpg
[14]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_014.jpg
[15]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_015.jpg
[16]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_016.jpg
[17]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_017.jpg
[18]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_018.jpg
[19]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_019.jpg
[20]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_020.jpg
[21]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_021.jpg
[22]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_022.jpg
[23]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_023.jpg
[24]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_024.jpg
[25]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_025.jpg
[26]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_026.jpg
[27]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_027.jpg
[28]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_028.jpg
[29]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_029.jpg
[30]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_030.jpg
[31]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_031.jpg
[32]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_032.jpg
[33]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_033.jpg
[34]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_034.jpg
[35]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_035.jpg
[36]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_036.jpg
[37]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_037.jpg
[38]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_038.jpg
[39]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_039.jpg
[40]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_040.jpg
[41]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_041.jpg
[42]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_042.jpg
[43]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_043.jpg
[44]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_044.jpg
[45]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_045.jpg
[46]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_046.jpg
[47]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_047.jpg
[48]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_048.jpg
