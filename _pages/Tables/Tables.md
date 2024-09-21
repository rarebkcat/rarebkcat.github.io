---
layout: single
type: docs
title: Tables
permalink: /DCRMR/tables/
sidebar:
  nav: "docs"
---

Pages for for tables conversation, summer 2023.

**Note**: Internal links are largely to my personal repository, which I am using as a sandbox for DCRMR discussion. Please do not distribute the [rarebkcat website](https://rarebkcat.github.io/DCRMR/preface/) -- it's for internal use only. 

## Tables 

There are several places we use tables to present information in DCRMR. The main kinds of information are:
+ letterforms and brevigraphs (in [Transcription](/DCRMR/general-rules/Transcription/))
+ conjectural dates (in [Chapter 5](/DCRMR/ppdm/))  
+ crosswalks between DCRM manuals and DCRMR (in [Appendix K](/DCRMR/tables/Appendix-k/))

A full list of tables in DCRMR can be found at [Tables in DCRMR reference](/DCRMR/tables/Appendix-t-table-reference/).

## Concerns

There are two concerns with tables:

First, that they be properly marked up, with the different parts of the table encoded appropriately. This is for accessibility, so that screenreaders can properly navigate them. I took a web accessibility course in Dec. 2022, and it emphasized to me the importance of properly marking up our data. (References: [WebAIM, Creating Accessible Tables, Data Tables](https://webaim.org/techniques/tables/data){:target="_blank"}, [How screenreaders navigate tables (YouTube)](https://www.youtube.com/watch?v=X1KR4u94cho){:target="_blank"}, and [Reading tables with JAWS (YouTube)](https://www.youtube.com/watch?v=xydbnhUdczs){:target="_blank"}.)

Second, that they are straightforward for keepers on the back-end, so that we can make edits as necessary, whether the edit be tiny (e.g., fixing a typo) or large (e.g., replacing an entire row). 

Currently, our tables are a mix of native markdown functionality (most of them) and exported html from google docs (the early letterforms table in Transcription, [0.4.16.1](https://dcrmr-development.github.io/DCRMR/general-rules/Transcription/#0.4.16.1){:target="_blank"}). To see what that looks like on the backend, you can look at the [brevigraphs markdown code](/DCRMR/tables/Letterforms-and-brevigraphs-current-release/#brevigraphs-code-excerpt-transcription-04161) and the [early letterforms html code](/DCRMR/tables/Letterforms-and-brevigraphs-current-release/#early-letterforms-code-transcription-04151). Neither coding structure uses mark-up to identify, e.g., header rows.

## Conversation

I'd like us to assess our use of tables and determine if we want to present the information in question as a table or through a different presentation.  Note that I am *only talking about **presentation** not content*. 

In instances where we (editorial group) do want to retain the table, we (keepers of the text) can go through and encode it. If there are places where we (editorial group) decide on a different presentation of the information, once the presentation is determined we (keepers) can edit the .md files accordingly

## Specced out content

In order to make everything more concrete, I used a personal copy of the DCRMR repository as a sandbox and spun out several pages. If you go to the [rarebkcat repository website](/DCRMR/preface/) and scroll down on the sidebar navigation, several sections related to tables follow the appedices.

Notes:  
1. All of the content on the sandbox pages are *excerpts* from the DCRMR text. I tried to include enough to be illustrative while being brief 
2. The specced out versions are for letterforms/brevigraphs and Appendix K. These are the most complicated and information dense of our tables
3. I included the iterations I could think of and could do. There might be other ways to present the information as well
4. In the Appendix K options, all of the DCRMR citations will be linked in the published iteration. For these purposes, I didn't add all of the coding  
5. For Appendix K, we need to think about how we want to incorporate the DCRM(G) cross-walks alongside the DCMR(B) cross-walks. Do we want them interfiled? Separated on the same page? On different pages? Etc. I specced a few different versions, although more iterations are possible; the table versions are based on kalan's work
6. There are almost certainly typos

This page serves as the equivalent to the chapter page for all of the broken out sections. The individual pages are:

Tables
* [Tables in DCRMR reference](/DCRMR/tables/Appendix-t-table-reference/); includes a linked list of DCRMR tables, some reference html for brevigraphs, and links to internet resources re: tables

Tables - letterforms and brevigraphs
* [Letterforms and brevigraphs, current release](/DCRMR/tables/Letterforms-and-brevigraphs-current-release/); includes excerpts from the main letterforms and brevigraphs tables as published, followed by an eye-readable version of their respective back-end coding, as published
* [Letterforms and brevigraphs, table options](/DCRMR/tables/Letterforms-and-brevigraphs-table-options/); includes html tables for both letterforms and brevigraphs, followed by an eye-readable version of their respective back-end coding
* [Letterforms and brevigraphs, detabled options](/DCRMR/tables/Letterforms-and-brevigraphs-detabled-options/); includes different possibilities for de-tabling the information in the transcription tables

Tables - Appendix K, table format
* [Option 1](/DCRMR/tables/Appendix-k-option-1/); this is the current layout of Appendix K, with a column added for DCMR(G). Citations are in numeric order
* [Option 2](/DCRMR/tables/Appendix-k-option-2/); this has one line per citation, with DCRM(B) and DCRM(G) citations interfiled 
* [Option 3](/DCRMR/tables/Appendix-k-option-3/); this has separate tables for each manual, with the table for DCRM(G) following DCRM(B) in each area. I copied the code from Option 2, so it's citation-content-citation, but the columns could be in any order
* [Option 4 (books)](/DCRMR/tables/Appendix-k-option-4-books/) and [Option 4 (graphics)](/DCRMR/tables/Appendix-k-option-4-graphics/); this is Option 3, but with separate pages for each manual

Tables - Appendix K, de-tabled format
* [Option 5](/DCRMR/tables/Appendix-k-option-5/); this is set up like an index, with one line per citation and DCRM(B) and DCRM(G) citations interfiled. There are two versions, one where the manual name comes first and one where the manual citation number comes first
* [Option 6](/DCRMR/tables/Appendix-k-option-6/); this has separate sections for each manual, with the section for DCRM(G) following DCRM(B) in each area. There are two versions, one that includes the manual name and one that omits the manual name
* [Option 7 - books](/DCRMR/tables/Appendix-k-option-7-books/) and [Option 7 - graphics](/DCRMR/tables/Appendix-k-option-7-graphics/); this is Option 6, Version 2, but with separate pages for each manual

## Conclusions

The goal at the June 21, 2023 meeting is to introduce everything to the editorial group, including some illustrative pages. 

There will be later follow-up after there's been time for thinking and conversing. 


---
