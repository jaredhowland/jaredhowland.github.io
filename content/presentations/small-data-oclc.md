---
title: Small Data Management
kind: presentation
permalink: /presentations/small-data-oclc/
---
# Small Data Management #

## <span class="caps">OCLC</span> Americas Regional Council Meeting 2017 ##
Jared L. Howland

Given October 2017 in Baltimore <span class="caps">MD</span>

**Download:** [PowerPoint][] | [PDF][]

![Slide 001][1]

Good morning! Thank you all for being here. I’m Jared Howland—the collection development coordinator at BYU.

I want to start today by talking about a little ancient Roman history. Because what good presentation about data doesn’t start off with a good history lesson?

So, in ancient Rome, you were not automatically granted legal citizenship when Rome took over your country

Before 212 AD, the primary way for imperial subjects to gain citizenship was to enlist in the Roman Army and serve for a minimum of 25 years

![Slide 002][2]

Afterwards, to prove their citizenship, they were granted a Roman military diploma which consisted of three parts:

The first part was a decree issued by the emperor of Rome and housed in the military archive at Rome

![Slide 003][3]

The second and third parts constituted the military diploma which was made from two bronze tablets bound together and presented to the retired soldier, possibly in a ceremony

![Slide 004][4]

They would bind the two plates together with wire

![Slide 005][5]

And then seal them together

![Slide 006][6]

The recto of the first plate would declare the veteran a legal Roman citizen

The verso of this plate would have an exact copy of the text on the outside

![Slide 007][7]

The recto of the second plate included the names of 7 witnesses that were then sealed

After which, the plates were bound together with wire and sealed together

![Slide 008][8]

To prove his citizenship, the retired soldier presented his diploma to the governor who would break the seals and confirm that the texts matched and that the seals had not been tampered with

They would compare this text with the one found in the military archive to confirm that the information was correct and not a forgery

![Slide 009][9]

At this point you are probably asking yourself, what on earth is this guy going on about?

I think this story illustrates a couple of key principles that may guide us in our discussion about data today:

1. First, people have been thinking about how to store and verify information for a very, very long time. The Roman military diploma is an ancestor to the principle of master data management which I will discuss here in a bit. Though this is not a new problem, the scale and technology for data has continues to drastically change.
2. Second, librarians have also been thinking about data problems for a very long time. The progression, and increasing importance, of ideas such as “big data” and “data management” over the last decade has demanded that librarians learn how to manage researchers’ data.

Today, I’d like to take a step back and spend some time thinking about how we can manage our own data to enhance our abilities to make data-driven collection development decisions.

You probably noticed that the title of my presentation is “Small Data Management” so before jumping into that, I’d like to very quickly define what I mean when I say “small data” as compared to “big data”.

IMAGE: CC0 Creative Commons License—https://pixabay.com/en/question-mark-important-sign-1872665/

![Slide 010][10]

Big Data Definition: data sets that are so large or complex that traditional data processing application software is inadequate to deal with them

![Slide 011][11]

Small Data Definition: data that is small enough for human comprehension. You don’t need algorithms or machine learning to understand what the data is telling you.

But regardless of what you call it, big or small, all data have the same problems when you attempt to tame them

![Slide 012][12]

Here are just a few examples of vexing data-related problems

So to give you some concrete examples of these problems, here are a few rhetorical questions to help you decide if you have ever encountered a data management problem:

1. Have you ever had to wait for a colleague to get back from vacation to get data or numbers from them to finish a report you were working on?
2. Or similarly, have you ever had to contact a colleague for a data set that would be very useful if it were made available to everyone working in the library?
3. Have you ever carefully compiled a report for your administration and then, a year later, not be able to recreate the same numbers when they needed an updated data set?
4. Have you ever found a great data set to help you evaluate your collections and then not remember where you found it, or from whom you requested it?
5. Have you ever run a report and then gotten wildly different data the next time you run the exact same report?
6. Have you or a colleague ever lost important data when a single hard drive failed?

If you answered yes to any of those questions then you have encountered a data management problem. These may have been rhetorical questions, but they certainly are not hypothetical. I have encountered each of these, among many others.

![Slide 013][13]

Once we finally realized these were recurring problems, we investigated ways to solve the immediate and pressing problems we had with data management (highlighted here in orange).

We quickly learned that there are a lot of commercial solutions aimed at large corporations or built for really complex data. Those tools were far too much for what we needed. In fact, our university has several tools that would meet some of our needs, but they are not readily accessible to us, and, more importantly, fail to address all of the problematic scenarios I just presented.

Most tools we found tried to manage the full data management cycle which is not something we were interested in pursuing. At least, not yet. We thought if we could just get a handle on a few of our data management problems we would be doing ok. With that background and contextual information out of the way, it will be important for us to know some data management terminology before getting much further into this.

![Slide 014][14]

Data management is a broad field with a lot of components associated with it
This table outlines just a few of them as defined by the Data Management Association’s “Data Management Body of Knowledge” Framework

![Slide 015][15]

Master Data Management, or MDM, is one small component of the larger data management landscape.

MDM: comprises the processes, governance, policies, standards, and tools that consistently define and manage the critical data of an organization to provide a single point of reference

After learning about MDM, we felt that if we could just manage that portion of data management, we would be in a far better position to effectively evaluate and analyze our collections

While analyzing the available tools, we found two that we thought might be most useful for our needs

![Slide 016][16]

The first is GitHub, which many of you have probably heard of. It is a web-based tool built on a system called git which is a file version control system

In short, it lets you track changes to documents over time and revert back to previous versions if you made a mistake or just need to see what things looked like in the past.

It allows you to work on files without worrying you are going to mess something up and not be able to recover from it.

![Slide 017][17]

The second tool we found is from the “Comprehensive Knowledge Archive Network,” or CKAN, and is open-source, web-based software for managing, storing, and distributing data. If you are familiar with data.gov, it uses CKAN for all of its datasets.

There are pros and cons of each depending on your use case, budget, and technical expertise.

![Slide 018][18]

Other features:

1. There are both public and private data repositories
2. Fine-grained controls for who can and cannot read and write to the data repository are available
3. You can add comments and documentation to data sets and even to specific data points
4. There is a built-in troubleshooting ticket system
5. You can create different, parallel, versions of the same data set depending on the audience and how the data was analyzed

![Slide 019][19]

Other features:

1. There are both public and private data repositories
2. You can tag, group, and place data into organizations
3. Faceted searching is available for the entire data repository
4. CKAN has an accessible and understandable user interface
5. Extensions are available to greatly expand the default capabilities of the system, and if you have the technical expertise, you can build your own to meet a specific need

![Slide 020][20]

Let’s take a look at how we have used each of these systems. First, let’s review Github and how we have experimented with it as an MDM tool

![Slide 021][21]

We created a repository that includes all of our data sets. In this case, there are only 2 datasets: ‘arl’ and ‘serial-prices’

![Slide 022][22]

There are 3 branches for the data sets:

1. Normalized: data that has been cleaned up and normalized to make sure it is ready to be analyzed
2. Projects: a parallel data set that presents the data is different ways depending on the audience. Line chart vs Bar graph
3. Raw: the raw data as you got it from the source

Below the branches you see documentation on how the Github repository is set up and organized for use as a rudimentary master data management system

![Slide 023][23]

So let’s take a look at our ARL data set

![Slide 024][24]

The ‘arl’ directory includes the actual data, a README, and a SOURCE file.

This is true of every data set we have in Github. The README is automatically shown below the list of files and describes how the data is organized, what each field in the data means, and how it is formatted

![Slide 025][25]

There is also a SOURCE file, so let’s see what that is.

![Slide 026][26]

So the SOURCE file simply tells you where you got the data from. In this case, it is from a single source but some data sets can be culled from multiple sources.

Let’s go back and look at some of the actual data

![Slide 027][27]

Let’s say we are interested in the ‘collection-expenditures’ data. We click on that…

![Slide 028][28]

and Github will show you a preview of the CSV file

![Slide 029][29]

If you want to download the file, you can click on ”Raw” and download the file

![Slide 030][30]

The other branches include similar documentation.

For example, the normalized branch tells you what steps you took to clean up the data so you can clean up future data sets in the same way so that it is consistent.

The projects branch will have multiple a folder for each normalized data set and then within the folder you will have multiple versions of the same data. A trivial example would be showing the data as a line graph in Excel versus a bar graph.

![Slide 031][31]

Let’s talk a little about how we have been experimenting with CKAN

![Slide 032][32]

CKAN includes a lot of features:

There’s keyword searching for all datasets

Tags you can create for each data set

![Slide 033][33]

The main navigation is available at the top: Datasets, Organizations, and Groups

![Slide 034][34]

Let’s take a look at datasests

![Slide 035][35]

You can see that searching datasets is still an option and now you also have facets available for narrowing your search down.

![Slide 036][36]

We’ll come back to datasets in a minute but let’s take a quick look at organizations

![Slide 037][37]

With organizations, you can have multiple departments in the library with their own organization. In this case we only have the collection development organization

But we could add a cataloging organization or administration organization, for example, if we wanted

![Slide 038][38]

Next is groups

![Slide 039][39]

Groups are just a way to group your data into broad categories and might be helpful when you have more than the 13 datasets we currently have in CKAN

![Slide 040][40]

Now, let’s go back and take a closer look at datasets

![Slide 041][41]

And let’s say we are interested in the “BYU Class Schedule” dataset…

![Slide 042][42]

so let’s click on that one

![Slide 043][43]

There is a brief explanation of the dataset available and then a list of the files associated with the dataset

If you scroll down the page…

![Slide 044][44]

You can see some metadata fields. Some are automatically generated and some are customizable. With extensions, you can add even more metadata fields if you need to.

This is the metadata for the entire dataset. You can also create metadata for individual files if you want to describe or explain some quirk of the dataset only present in that one file.

Let’s scroll back up and take a look at some other features.

![Slide 045][45]

If you click on explore…

![Slide 046][46]

You have the option to preview or download the file

Let’s preview it

![Slide 047][47]

Just like Github, it will show you an abbreviated view of the file.

From here you can also create rudimentary visualizations of the data by clicking on “Graph”…

![Slide 048][48]

so let’s do that.

![Slide 049][49]

You can then select the data you want to be on which axes and pick the kind of graph you’d like to use to represent your data.

![Slide 050][50]

You can also embed the file on another website by clicking “Embed” and copying the code into another site.

![Slide 051][51]

Or you can click on the URL to download the full file.

![Slide 052][52]

So that is a quick overview of some tools we have been experimenting with at BYU to help us manage and analyze our collection development data.

Thank you!

IMAGE: CC0 Creative Commons License—https://pixabay.com/en/lamps-thank-you-door-workshop-1030901/

[PowerPoint]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_pptx.pptx
[PDF]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_pdf.pdf

[1]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_001.jpg
[2]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_002.jpg
[3]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_003.jpg
[4]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_004.jpg
[5]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_005.jpg
[6]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_006.jpg
[7]: {{ site.url }}/assets/images/presentations/files/small-data-oclc/presentation_007.jpg
