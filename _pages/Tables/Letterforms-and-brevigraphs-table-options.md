---
layout: single
type: docs
title: T — Letterforms and brevigraphs, table options
permalink: /DCRMR/tables/Letterforms-and-brevigraphs-table-options/
sidebar:
  nav: "docs"
---

## Contents:
{: .no_toc .text-delta }

- TOC
{:toc}

## Note

Hand-coded html, so that it includes column headers, doesn't include extraneous css, and is easy to read and edit in the backend. 

ALT note: we don't really have row headers -- there's no handy label for what's in the row, except insofar as the source image is one -- which we might need to remedy. Could we flip the first two columms, so the 'modern form' serves as the row header? (Follow-up ALT note: I think it's okay as-is. Per WebAIM, "A critical step toward creating an accessible data table is to designate row and/or column headers." We have the column part of the "and/or".)

ALT note: the WebAIM page has some information about spanned headers, although it also notes "despite being standard markup for tables for many years, some screenreaders still do not fully support complex tables with spanned or multiple levels of row and/or column headers. When possible, try to 'flatten' the table and avoid spanned cells and multiple levels of header cells.

## Brevigraphs, html table

### Brevigraphs, html table -- the table

<table>
<caption><strong>Brevigraphs</strong></caption>

<thead>
<tr>
<th scope="col">Source</th>
<th scope="col">Transcription</th>
<th scope="col">Example</th>
<th scope="col">Transcription of example</th>
<th scope="col">Notes</th>
</tr> </thead>

<tbody> 

<tr>
<td><img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/Brevigraph-1.png" alt="Brevigraph"/></td>
<td>[missing letter(s)]</td>
<td>
<img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/Co%5Bn%5Dsummatu%5Bm%5D.png" alt="co[n]summatu[m]"/> 
<img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/D%5Bomi%5Dn%5Bu%5Ds.png" alt="D[omi]n[u]s"/></td>
<td>co[n]summatu[m] D[omi]n[u]s</td>
<td>Over a vowel, usually <strong>n</strong> or <strong>m</strong>; over a consonant, often replaces several letters </td>
</tr>

<tr>
<td><img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/%5Bae%5D.png" alt="[ae]"/></td>
<td>[ae]</td>
<td><img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/h%5Bae%5Dc.png" alt="h[ae]c"/></td>
<td>h[ae]c</td>
<td></td>
</tr>

<tr>
<td><img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/%5BChristus%5D.png" alt="Christus"/></td>
<td>[Christus]</td>
<td></td>
<td></td>
<td>A contraction using both Greek and Latin letters</td>
</tr>

</tbody>
</table>

### Brevigraphs, html table -- the code

ALT note: I need to see if there's a best practice for empty cells

&lt;table&gt;  
&lt;caption&gt;&lt;strong&gt;Brevigraphs&lt;/strong&gt;&lt;/caption&gt;  

&lt;thead&gt;  
&lt;tr&gt;  
&lt;th scope="col"&gt;Source&lt;/th&gt;  
&lt;th scope="col"&gt;Transcription&lt;/th&gt;  
&lt;th scope="col"&gt;Example&lt;/th&gt;  
&lt;th scope="col"&gt;Transcription of example&lt;/th&gt;  
&lt;th scope="col"&gt;Notes&lt;/th&gt;  
&lt;/tr&gt; &lt;/thead&gt;  

&lt;tbody&gt;  

&lt;tr&gt;  
&lt;td&gt;&lt;img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/Brevigraph-1.png" alt="Brevigraph"/&gt;&lt;/td&gt;  
&lt;td&gt;[missing letter(s)]&lt;/td&gt;  
&lt;td&gt;  
&lt;img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/Co%5Bn%5Dsummatu%5Bm%5D.png" alt="co[n]summatu[m]"/&gt; 
&lt;img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/D%5Bomi%5Dn%5Bu%5Ds.png" alt="D[omi]n[u]s"/&gt;&lt;/td&gt;  
&lt;td&gt;co[n]summatu[m] D[omi]n[u]s&lt;/td&gt;  
&lt;td&gt;Over a vowel, usually &lt;strong&gt;n&lt;/strong&gt; or &lt;strong&gt;m&lt;/strong&gt;; over a consonant, often replaces several letters &lt;/td&gt;  
&lt;/tr&gt;  

&lt;tr&gt;  
&lt;td&gt;&lt;img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/%5Bae%5D.png" alt="[ae]"/&gt;&lt;/td&gt;  
&lt;td&gt;[ae]&lt;/td&gt;  
&lt;td&gt;&lt;img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/h%5Bae%5Dc.png" alt="h[ae]c"/&gt;&lt;/td&gt;  
&lt;td&gt;h[ae]c&lt;/td&gt;  
&lt;td&gt;&lt;/td&gt;  
&lt;/tr&gt;  
&lt;tr&gt;  
&lt;td&gt;&lt;img src="https://rbms-bsc.github.io/DCRMR/assets/pictures/transcription/%5BChristus%5D.png" alt="Christus"/&gt;&lt;/td&gt;  
&lt;td&gt;[Christus]&lt;/td&gt;  
&lt;td&gt;&lt;/td&gt;   
&lt;td&gt;&lt;/td&gt;  
&lt;td&gt;A contraction using both Greek and Latin letters&lt;/td&gt;  
&lt;/tr&gt;  

&lt;/tbody&gt;  
&lt;/table&gt;  

## Early letterforms, html table

### Early letterforms, html table -- the table

ALT note: I added a "foo" in the Notes column just so we could see where the note text would go.

<table>
<caption><strong>Early letterforms and their transcriptions</strong></caption>

<thead>
<tr>
<th scope="col">Source</th>
<th scope="col">Modern form</th>
<th scope="col">Example</th>
<th scope="col">Transcribed example</th>
<th scope="col">Notes</th>
</tr> </thead>

<tbody> 
<tr>
<td><img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image11.png" alt="d"/> </td>
<td>d</td>
<td><img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image7.png" alt="day"/> </td>
<td>day</td>
<td>foo</td>
</tr>

<tr>
<td><img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image45.png" alt="d"/> </td>
<td>d</td>
<td><img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image24.png" alt="day"/> </td>
<td>sed</td>
<td></td>
</tr>

</tbody>

</table>

### Early letterforms, html table code

&lt;table&gt;  
&lt;caption&gt;Early letterforms and their transcriptions&lt;/caption&gt;  

&lt;thead&gt;  

&lt;tr&gt;  
&lt;th scope="col"&gt;Source&lt;/th&gt;  
&lt;th scope="col"&gt;Modern form&lt;/th&gt;  
&lt;th scope="col"&gt;Example&lt;/th&gt;  
&lt;th scope="col"&gt;Transcribed example&lt;/th&gt;  
&lt;th scope="col"&gt;Notes&lt;/th&gt;  
&lt;/tr&gt; &lt;/thead&gt;  

&lt;tbody&gt;  

&lt;tr&gt;  

&lt;td&gt;&lt;img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image11.png" alt="d"/&gt; &lt;/td&gt;

&lt;td&gt;d&lt;/td&gt;  

&lt;td&gt;&lt;img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image7.png" alt="day"/&gt; &lt;/td&gt;

&lt;td&gt;day&lt;/td&gt;  

&lt;td&gt;foo&lt;/td&gt;  

&lt;/tr&gt;  

&lt;tr&gt;  

&lt;td&gt;&lt;img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image45.png" alt="d"/&gt; &lt;/td&gt;

&lt;td&gt;d&lt;/td&gt;  

&lt;td&gt;&lt;img src="https://bsc.rbms.info/assets/pictures/transcription/early-letterforms-and-symbols/image24.png" alt="day"/&gt; &lt;/td&gt;
&lt;td&gt;sed&lt;/td&gt;
  
&lt;td&gt;&lt;/td&gt;  

&lt;/tr&gt;  

&lt;/tbody&gt;  

&lt;/table&gt;  



---
