Yo! This easy and short documentation will help you to install and set Yokai theme properly. No hustle, let's dive in.

##Installation

1. Go to your Ghost site folder (via FTP or just on hard drive if you are hosted locally).
2. Find `content/themes` folder — go inside.
3. Upload Yokai folder there.
4. Restart Ghost.
5. Open site's dashboard (`http://yoursite.com/ghost`).
6. Navigate to "Settings".
7. At the very bottom find "Theme" line — select "Yokai" from dropdown menu.
8. Click "Save".
**Done**

##Configuration

###Inside Ghost

Ok, now it's time for some text work.

1. Hope you are still in dashboard.
2. Open "Settings" page.
3. Fill in info about your blog and upload it's logo and cover. Remember, that the cover must be at least 1200px width and 400px height. If you want your blog to look cool at large desktops — use at least 1080px height.
For logo minimum is 100x100px.
4. Smash "Save".
5. Open "User Section".
6. Fill in info about yourself. This will be displayed at the bottom of every post (avatar, name and bio, the rest is unnecessary).
7. "Save" again.

###Outside Ghost

You do not fear code, do you? Of course you don't. That's great, let's see what we have here...

First, navigate to Yokai theme folder and open "partials" — `content/themes/yokai/partials`.

#####Social Links

In order to make your blog really yours, we are gonna set some social icons. Yokai support Twitter, Facebook, Google Plus, LinkedIn and Dribbble. If you need more — drop me a [mail](mailto:jdavydko@gmail.com), we'll come up with something.

1. Open "socials.hbs"
2. Choose what icons you need and comment or simply delete the others.
3. Paste links to your social pages inside `href=""`.
4. Save the file.
**Done**

#####Comments

Ghost doesn't have native comment system yet, so we'll have to use third party solution. And this solution is Disqus.

1. Go to [disqus.com](http://disqus.com) and sign up. Or in, if you already have an account.
2. Register new site and get a code.
3. Open "comments.hbs".
4. Paste Disqus code there.
5. Save the file.
**Done**

#####Analyze it!

If you want to see statistics of your blog, you may use Google Analytics or something else.

1. Open "analytics.hbs"
2. Paste code you got from any analytics service there.
3. Save the file.
**Done**

###Not the end — the begining!

Well done! Your blog is ready and set to go. Hope you'll like it now that it have Yokai on board.

Some important tips before you go:

1. If you want an image appear in a post on index page — just insert it in the begining of post. Yokai will do the rest.
2. It's a little bit more tricky with videos. To make it  appear on index properly, you must implement it's code into video block, like this:
`<div class="video"><!--Your video iframe code goes here--></div>`

Enjoy!

##Credits

Something wrong? Can't make theme work? Problems with configurating? **Write me!** I'll help you with pleasure: [send me a letter](mailto:jdavydko@gmail.com).

Yokai uses wonderfull icons by [Entypo](http://entypo.com/).
Yokai's font is Open Sans (cyrillics are supported, by the way).
Yokai's based on Casper theme, the dafault free Ghost theme.

Design and development — [Ghosted.net](http://ghosted.net).