---
layout: post_archive
title: The Content Layout System
created: 1095864179
tags:
- ''
lang: nl
---
or: Why embedded editors are no good solutions for a CMS.  We see it very often these days: CMS-es with a full blown, javascript powered interface to edit and layout content in a site. Today I came across a plug-in for HTML-area called ImageManager. I call such a system a Content Layout System. Both are javascript powered tools that replace the standard text-area in a CMS. Both allow users to edit content using a full featured WYSIWYG editor. No more HTML tags, no more BBtags, simply select a text and press the [b] icon, and it becomes bold. Better even: you actually see it becoming bold. Like we are used to in for example Word. And in case of the ImageManager, press some buttons to rotate and scale and crop images. and probably to do a lot more.   But the crux lies in the purpose of a CMS. Content Management System. Manage content. It says nowhere: content layout system, nor does it say image modification system. Managing the content is the bottomline. Whether content is an image, an MP3, a piece of text, or anything else, does not really matter it is all content, and it is up to the CMS to manage it, organize it, or display it.  And since we are talking internet that last part still is the main task of a CMS. (Although the popularity of RSS is starting to change this)  Alright: So the management part is clear. The system part should not be too difficult too. But the most important part is yet to come: The content part. We are talking content, raw content. Or a better name: Knowledge, with all sorts of metadata attached to it. A title gets a tag "title", an article has some metadata about the fact its an article, but also what title belongs to it, who wrote it, and what more you can think of.  And because of that metadata a CMS will know what to output on particular areas, in a particluar layout. A frontpage, for example, will contain a list with titles, while an article view will show the article with all its metadata, probably the name of the author, a publication date, maybe an image, or a bordered quote,  possibly a quote and maybe teaser in bold type.   With a Content Layout System, you will open up a screen to add such an article. You will select the teaser text, make it bold. Upload, modify  and insert an image. You will select the quote, give it a black border, make the quite bold and italic, and give it a big font size. You will add your name and the date, and then press send.  The article will then look like a professional news article like they have on BBC.  In a CMS, however, you will open a form, with separate areas for all the separate data: The image can be uploaded, with an upload field.   A quote should be inserted in a separate field. The teaser is typed in a smaller text-area and user and date are automatically added. The CMS will give all these fields a layout when presenting it to the user.  I think it is clear that the last example has a lot of benefits: The CMS has all content split out, thus real knowledge is stored in a way it can be reused and searched for.  The first example saves all content, together with layout as one blob, somewhere. It will never be able to output only a list of quotes, to name an example. Thus knowledge cannot be structured and re-used. The CMS, however allows very little creativity, but willbe much easier to maintain, because of its unified look, and unified storage of content. There is one more issue, though: I hear you asking it already: "what if my image is too big, or needs to be rotated 90°?" And last, but not least, the CMS gives you hard times with placing items inline. What If my artcle contains, for example, inline postal addresses? I will then need to add these addresses somewhere else, if i want to stick close to the CMS ideal (an address could be used in an address book too).  A lot of CMS-es solve this by adding tokens. A token for an adress could be [address:addressID] where addressID is a unique number for an adress book entry.   And this is where some form of graphical interface should be used. A button could open a selection window where I can search for an address. After selecting that and pressing a OK button, the token will be inserted in my text.  Now the creativity and freedom part: If you investigate an article (or a portfolio entry, to give another example) you will see that the content can be devided into areas, all with a specific use. In fact you will have to search very hard for articles, in magazines, or so, that do not follow these. If you find cases where each page looks different, with differnet areas (different metadata) you will find that the idea behind this is mostly creativity: a designer wants each page to have its own feeling. Ther is nothing wrong with that. But if you enter that area of website design there are much, much better toolkits for creating a site than an inline HTML-area. I am thinking of Dreamweaver, Flash, Freehand, Photoshop and so on.  And that brings me to my last issue: "what if my image is too big, or needs to be rotated 90°?" As said: there are far better toolkits for doing that. Why should the server, in combination with a javascript interface handle that, if Photoshop can do so much more?  Why do I need online spelling checkers and HTML generators, when there are complete integrated office suits around that do the same, in a much better suited way, with much better tools with it (autosave, to name one).  If you look at all the possibilities, that for example "the gimp" offers, for free. Not only can you modify it for your website, but fixing a dark sky, or retouching some shadows is all possible. A webbased application will never be able to do this with only Javascript and some serverside software.  But even if ever this is possible, it is not ideal: Imagine the computer that is needed for editing thousands of images per hour, it's huge. If people would edit everything at home, the sever could be much smaller. But can you expect everyone to install an image editor like Photoshop, or the gimp? No, you cannot, but more important you cannot expect people to get to know these applications, only for uploading their photo' s to their family webalbum. But you cannot expect them to learn a new system for each webalbum they have either.  Ideally you would find some hybrid system: A CMS that creates its own layout, with some small, embedded tools for inserting data, and have the users do the preparation of the content on their desktops, with the tools they feel most comfortable with.  Ideally the web interface would plug into these applications, so that you can say directly from your webinterface: edit this text in Word, or in word say: "publish the sected text as body". But for that we have to wait for XUL alike systems to grow up. until that day I just use my textareas, without any WYSIWYG tools.