---
layout: post
title: OpenGLBook.com Relaunch
authors:
  - email: eddyluten@gmail.com
    name: Eddy Luten
---

<img
	src="{{site.url}}/images/Octocat.png"
	alt="Octocat"
	title="Octocat"
	class="right"
/>

You may have noticed that for a few days the site was unavailable. This was caused by my old host, GoDaddy, who without informing me pulled the plug on my VPS account that hosted this site for the last three years. I still don't know why this happened and can't manually reactivate the account. Oh well, their loss.

However, this fiasco gave me incentive to finish converting the site to Markdown in preparation for release to GitHub Pages. I was planning this anyway, so tonight I put the final touches on the conversion, and as of right now, the entire site is hosted on GitHub pages.

## What This Means ##

1.) Even though the site's code samples were previously released under the MIT license, the site's contents were not open source. This has now been remedied by licensing the contents of the site under the [Creative Commons Attribution-ShareAlike 4.0 International](http://creativecommons.org/licenses/by-sa/4.0/) license (CC BY-SA 4.0). The source code for the entire site is [now available on GitHub](https://github.com/openglbook/openglbook.com) for anyone to mess around with.

2.) I don't have to pay for hosting anymore, so no more ads (yay!).

3.) Inline code samples are now hosted as gists, which makes maintaining the site content less of a nightmare.

4.) Chapters are stored as Markdown, so they're editable in any text editor, not restricted to a clumsy web-based WYSIWYG editor.

## Known Issues ##

* Legacy chapter URLs no longer work (not fixing).
* Code samples haven't been put on GitHub *yet*.
* Many old bugs haven't been fixed since this was almost a verbatim copy.
* There are still many files to clean up.

I'm expecting more issues with the site in the next couple of days, so if you come across something that doesn't look quite right, please report the issue.