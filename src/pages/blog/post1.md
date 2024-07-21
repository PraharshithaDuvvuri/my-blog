---
layout: "../../layouts/blog-layout.astro"
title: Tables and Forms in HTML simplified.
description: A blog about HTML table and form elements.
published: 01-10-2023
---

<img src="/images/post1/cover.webp" alt="cover"/>

<p class="-mt-6 font-bold text-sm" align="center">HTML sample tags</p>

HTML is a markup language that is being used for developing websites. It has three types of tags: structural, semantic, and formatting. These tags can be learned from [mdn docs](https://developer.mozilla.org/en-US/docs/Web/HTML) and [W3 schools](https://www.w3schools.com/html/) etc. But here is a tip for simplifying this journey. After going through basic HTML tags, practice the usage in [visual studio code](https://code.visualstudio.com/download). The most important extensions to be installed in vs code are prettier and live server. Then go through the [emmet shortcuts](https://docs.emmet.io/abbreviations/).

### Tables in HTML

The most common tags used for creating tables in HTML are `<table>`,`<thead>`,`<th>`,`<tbody>`,`<tr>`,`<td>`, and `<tfoot>`.`<table>` tag is used to indicate the compiler that we want to create a table.`<thead>` tag is used to indicate that we want to give headings to our table.`<th>` tag is used inside `<thead>` tag for creating different elements i.e. n no. of `<th>` tags for n no. of columns.`<tbody>` tag indicates that the content or the actual data will be placed here.`<tr>` tag is used to indicate that we want to create a row in our table.`<td>` tag is used to indicate a specific data cell((row,col) or(1,2)). `<tfoot>` tag is used to indicate that we want to create a footer element for our table. The border=”1" attribute can be added to create borders for the table.Sometimes in caseof complex tables, there can be multiple rows inside `<thead>` tag. Take sample tables from the internet and start practicing on your own.

### Forms in HTML

Forms in HTML are used for collecting data from users and are sent to the backend for processing this information. While learning about forms, firstly go through the form elements. The form elements are input, label, select, options, button, and textArea. Practice these tags by taking references from [mdn docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/form).

<img src="/images/post1/form1.webp" alt="form1" />

<p class="-mt-6 font-bold text-sm" align="center">Usage of form elements part 1.</p>

<img src="/images/post1/form2.webp" alt="form2" />

<p class="-mt-6 font-bold text-sm" align="center">Usage of form elements part 2.</p>

The concept of radio buttons and checkboxes is pretty much important. These are the most frequently used in developing real-time forms.

### Radio Buttons

Radio buttons can be called mcq’s where only one option can be chosen by the user. In order to achieve this, we use the ‘name’ attribute. The ‘name’ attribute value should be the same so that similar options can be grouped as one.

<img src="/images/post1/radio.webp" alt="radio" />

<p class="-mt-6 font-bold text-sm" align="center">Example for radio buttons.</p>

### Checkboxes

Checkboxes can be called mcq’s where multiple options can be chosen by the user. Here, the ‘name’ attribute should not be the same for different checkboxes because any no. of checkboxes can be selected at a time by the user.

<img src="/images/post1/checkbox.webp" alt="checkbox" />

<p class="-mt-6 font-bold text-sm" align="center">Example for checkbox.</p>
