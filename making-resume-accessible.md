---
navigation_weight: 5
title: Making my reaumé accessible
---

I recently revamped my resumé (also known as CV) to be more accessible. I’ve learned a lot about accessibility in the past couple of years, and some of my work as a content designer in technology has even included writing guidance on making content and documents more accessible. 

Realizing my resumé didn’t follow the principles I was applying to my other content work, I updated it to be simpler, easier to read and more compatible with assistive technology. 

## Why is it important to make CVs accessible?
Recruiters and hiring managers with accessibility needs exist. While I’m sure many of them, sadly, suffer in silence, there’s more we can and should all be doing to be inclusive not just of our users and customers, but of our future colleagues too (who, in this case, are “users” of our CV!)

Making things accessible also makes them better for everyone. So even if the people reviewing your application can use PDFs just fine, they can still benefit from your resumé being clearer and simpler. 

Making your resumé accessible is also a great way to demonstrate you know how to make content accessible. Whether you’re applying for a role in content, design, development, or literally any other job that involves written communication, content accessibility is a great skill to be able to not just say you have, but show you have. 

## How I make my CV accessible
Applying some of the basic principles I’ve picked up on the job, here are some of the things I now do to improve the accessibility of my CV. 

Note that I’m learning more about accessibility every day, so parts of this page and other parts of my website might still not be ideal. See my [Accessibility Statement](/accessibility-statement.md) for more information. 

### Avoid using tables to create the layout
Previously, I used a single-row table to arrange job details across the width of the page. The company and title were in the left column, the job dates in the right column, and the description was listed underneath the table, in the normal body text of the page.

This layout makes good use of the horizontal space on the page, but it can be distracting, confusing and even uncomfortable by leading the eye in multiple directions with no clear reading order. In addition, tables that aren’t properly marked up - with a header row and relationships between rows and columns - can be difficult for screen readers to make sense of.  

I removed these tables and now write information in a normal linear flow:

* Job title, Company
* Dates
* Description

This of course can mean the content runs over more pages, but I think this is a case where accessibility trumps brevity - or rather, the illusion of brevity, since it’s the same amount of information, just presented differently. Three pages of well laid out, easy to read information is better than two pages of squished together text in small font with very little whitespace. This also encourages me to be discerning about what information I really need to include in my resumé.

### Use proper header formatting (H1 through H4)
Instead of using bold formatting or manual font size changes to separate each section of my resumé, I use properly marked up header styles to make the structure of the information readable for assistive technology. 

I also find it a much quicker and more efficient way to apply consistent styling and content hierarchy. Since I use this method when designing content in my work, I’ve become used to using keyboard shortcuts to quickly apply these styles in Google Docs. 

### Make everything left-aligned
Previously I had my personal information - my name, job title, contact information and professional summary - centered at the top of my resumé. Some content like job dates were right-aligned, and the rest of the information was left-aligned. Similar to the problems caused by using a table to distribute text across the width of the page, using multiple text alignment can be distracting for the eye. 

I now have everything left-aligned, which in combination with the linear structure, makes everything flow much more easily for reading left to right, top to bottom. 

### Avoid abbreviations that can make content less readable
When trying to fit content in a certain amount of space, like two pages, we often take shortcuts to abbreviate information. For example, using “etc”, “eg” or using a slash (“/”) to straddle similar concepts. While using these notations can use fewer characters, this can often come at the cost of legibility or clarity. Screen reader software often reads out “eg” as “egg”, or “apps/websites” as “apps websites”, which might confuse non-visual readers. 

Writing things out fully in my CV (“for example”, “apps and websites”) sometimes means a sentence awkwardly carries over to a new line, or a bullet point becomes just a bit too long. This pushes me to find creative ways to rewrite things more succinctly while still maintaining clarity and readability. It also challenges me to be clear about what I’m really trying to communicate - does this mean “apps or websites” or “apps and websites?” 

### Make links descriptive
My CV generally only includes a couple of links - my email address and LinkedIn profile. Sometimes, though, I also provide a link to my portfolio or specific examples of my writing relevant to the role I’m applying for. In addition, I’ve now started including a link to this page at the end of my CV to let people know how and why I’ve made my CV more accessible.

Making links accessible generally means making hyperlinked text descriptive, so people know where the link goes and what it’s about. So a sentence saying “Click here to see my portfolio”, with only the word “here” hyperlinked, wouldn’t be particularly accessible for people who use assistive technology to navigate through a list of links. 

Instead, I make sure any hyperlinked text is descriptive: “For examples of my work, view my portfolio”, with “view my portfolio” as the link text. For my email address, I write it out in full and make sure it’s set as an email link (Google Docs does this automatically). This means people can use it as a link directly or copy and paste it as they need.

### Share in HTML or as an open format document
Although PDFs are the most common file format for sharing and uploading resumés, they’re not great for accessibility. Since they’re designed to be used for printed material, PDFs don’t work well on mobile devices or for people who use screen magnification, as the text doesn’t rearrange to fit the screen, meaning people have to scroll in multiple directions to read all the information. While it’s possible to mark up PDFs to work with screen readers and other assistive technology, this is quite technical work and some job application systems strip this information out.

In addition, some commercial word processing file formats like .doc or .pages can cause strange formatting issues if people use different software to open the file. 

Now, where possible, I share or upload my resumé in:

* HTML (web page), which can be viewed in any browser - similar to a PDF, this presents it as a finished product for viewing only, but is more compatible with different devices and settings
* DOCX, a standard word processing document file type that’s similar to a Word .doc file but is “open format” meaning you can create and read them even if you don’t have Microsoft software

## What have I learned?
By making my resumé more accessible, I’ve pushed myself to think differently. I’ve learned to be more concise and strategic with the content of my CV, and have had to challenge some of my own assumptions about technology and about the hiring process in general. 

It’s too early to tell if it’s made a difference to how people view and read my resumé, and in most cases I probably won’t know. 

If you have feedback, thoughts or questions about my accessible resumé, get in touch!
