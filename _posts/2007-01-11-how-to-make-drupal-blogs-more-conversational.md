---
layout: post_archive
title: How to make (Drupal) blogs more conversational
created: 1168547559
tags:
- knowledge management
- php
- collaborative writing
- weblogging
- drupal
- drupal
- drupal blog
lang: en
---
Blogs. Conversation. Not exactly two words that people would fit in one sentence. Blogs don't talk to eachother; maybe with some trackback system, or via technorati, but even then they don't really conversate.  [Wilfred Rubens](http://wilfredrubens.typepad.com/wilfred_rubens_weblog/2007/01/conversaties_bi.html) pointed me to a [very good post on this matter](http://blogs.salon.com/0002007/2007/01/10.html#a1748). Dave Pollard investigated the very nature of a conversation, looked at how this applies to online communities and explains very clearly how blogs can improve the actual conversation, both within the weblogs and within their blogosphere. Let me take his points one by one and see what Drupal has to offer, or what Drupal should do better. One important note: It is a known fact that modules often integrate badly (or not at all). That the contributions promise far more then they deliver etceteras. Don't take my advice for granted, I tried less then one third of the modules mentioned below, and even that made me sad at moments. The modules listed below should be handled with care: don't ever think 'cool Bèr has a list with all the stuff Drupal can do, Its exactly what I need, I'll go for Drupal. [Choose with care](http://webschuur.com/publications/blogs/2006-12-21-drupal_and_the_carpenter_drupal_can_do_you_harm). My comments are in _italic_.1. There should be a process to allow people to 'subscribe' to the comments to any blog post, and get notified of new comments posted.    _[Subscribe](http://drupal.org/project/subscribe), [Organic Groups](http://drupal.org/project/og), [Notify](http://drupal.org/project/notify), [Views](http://drupal.org/project/views) and [Comment RSS](http://drupal.org/project/commentrss). Enough to choose from, I'd say, yet no ready-to-go-out-of-the-box solution._1. Each comment should have space for, and begin with, a one-sentence summary of the commenter's point (not the subject or thread title, the point they're making) to make browsing long comments threads easier.  _Nothing in Drupal nor in the contribs for this._1. The comment mechanism should require each commenter to indicate who they're replying to: the author of the main article or the author of one of the previous comments. The blog tool should then automatically 'thread' the comments accordingly.  _This is a great benefit of Drupal, it comes with core Drupal!. I am not aware of any blogging tool that offers this threading._1. The comment mechanism should allow each commenter to indicate what kind of response they would like, by checking off one of (a) response is requested from the person their comment is replying to, (b) response is requested from anyone who wants to chime in, or (c) no response is expected (closing that thread). The person(s) who have been requested to respond should get an e-mail notifying them of this fact (in case (b) the e-mail would go to anyone who 'subscribed' to the conversations for the blog post). _None of the listed subscription options mentioned under #1 offer anything like this._1. here should be a simple, short, polite way for the person getting a request to respond and who has nothing substantial to say, or wishing to acknowledge a compliment in a thread, to just say 'thank you' and close that thread.   _This too, is not possible with Drupal, nor with any of the contributions. If comments were nodes, however, such things would be simple to develop_1. The ability of most discussion forums to copy & paste excerpts from whatever the commenter is replying to (Jo said: "   ", in a box to start the comment) should also be available in blog comments.    _One module for this, [Quote](http://drupal.org/project/quote), not to be confused with quote__s__. The module seems particulary well coded, using Drupal in a good way, for example, it runs trough the filter system._ 1. Trackbacks should be integrated into comments as separate threads that readers can pursue at the other site -- they're part of the conversation, too, albeit moved to another site.  _Last time I used it, Drupal's contributed [trackback](http://drupal.org/project/trackback) module does not integrate comments and trackbacks. It's discription tells me this did not change._1. The comments threads should be appended to the actual blog post, rather than being kept elsewhere apart. Some blog tools do this. Others (like the one I use) don't.   _This is, in fact the only way Drupal can handle comments._1. Comments threads should make it easy to include links and other html (Radio Userland of late has been sending 403 messages to commenters using html).    _Drupals excellent filter system allows many more then this. which is its downside too: for Co Commentor  [this wayy to geeky and huge page, babbling about filter formats](http://webschuur.com/filter/tips) and HTML is too much._ 1. Bloggers and commenters should be able to note their Skype address and/or IM address and invite others to sign up for scheduled real-time chats on the entire article or some aspect or comment thread stemming from it. The recorded archives of such real-time sidebar conversations should be embedded in, or at least linked to, the applicable thread.    _Drupal has the comment fields hardcoded as far as its very core. This is not only impossible, even with contributions, it is technically not possible with the current architecture._So, the conclusion is, that Drupal has some work to do, but that the components, or at least the possibilities are there!Do you know any other modules that I missed? Are there issues (with patches) that cover some of these features waiting to be reviewed and tested? Could Drupal be the first 'Blogging tool', even if it is not a blogging tool, that has the ingredients for real conversations?