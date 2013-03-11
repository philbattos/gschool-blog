---
title: HTML & CSS, Part 1
date: 2013-03-11 15:20 -06:00
tags:
---

<h4>What concept or technique was most confusing or difficult for you?</h4>

I think the most confusing technique in the first section of the book was the last one presented: forms. I understand the basics of how to set up a form using various text fields, buttons, and check boxes but the backend functionality of forms is still unclear to me. However, i think it would be rather difficult to describe - and show - some examples of html forms here without creating actual forms. So, instead, i will discuss some challenges i've had with tables.

<h4>Tables</h4>

I first learned html several years ago so that i could make some simple websites for a non-profit organization. I learned almost everything that was presented in the first seven chapters of HTML & CSS and i remember having the most difficulty with frames and tables - especially when they were nested inside each other. After reviewing and practicing the concepts in the book, tables seem quite easy but i remember having problems keeping the tags straight so that the columns and rows would be the right sizes. I also had trouble with the "cellpadding" and "cellspacing" attributes; I could never get them to organize text just the way i wanted it. And now i see from the book that they have been phased out and stored in CSS. I guess this will make it easier to design tables... I just have to learn CSS now.

Anyway, here are some examples of tables, using html tags.
<table>
  <thread>gSchool Table
    <tr>
      <th>Total</th>
      <th>Men</th>
      <th>Women</th>
      <th>Ratio</th>
    </tr>
  </thread>
  <tbody>
    <tr>
      <th>Students</th>
      <td>24</td>
      <td>18</td>
      <td>6</td>
      <td>75% men</td>
    </tr>
    <tr>
      <th>Teachers</th>
      <td>4</td>
      <td>3</td>
      <td>1</td>
      <td>75% men</td>
    </tr>
  </tbody>
</table>
