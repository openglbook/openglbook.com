---
layout: post
title: Post-Relaunch Update
authors:
  - email: eddyluten+openglbook@gmail.com
    name: Eddy Luten
---

A quick breakdown of the changes that have happened since the relaunch and a bit of information about what's to come.

<!--more-->

<img
	src="{{ site.url }}/images/ladybug.png"
	alt="The good kind of bug"
	title="The good kind of bug"
	class="left"
/>

## Bugs and Issues ##

With this migration, I finally got around to handling some of those *really* old bugs that were filed all the way back in 2011. All of the reported typos have been handled so far, and there are only [a few more bugs to go through](https://github.com/openglbook/openglbook.com/issues?labels=bug).

If you find any issue with the text or code, please don't hesitate to report them by selecting the appropriate option from the "Report Issues" menu atop ever single page. This will take you to the GitHub issue tracker for the project where you can file an issue. Also, if you're able to fix the issue yourself, don't hesistate to do so and shoot over a pull request.

## Code Samples ##

The code samples now have their [own GitHub repository](https://github.com/openglbook/openglbook-samples). For now, it contains a directory structure similar to that of the previous repository, but in the future this will change with the shift to non-OpenGL 4.0 specific samples and text. If you don't want to clone the repository using git, you can also download an archive containing all of the files [on the releases page.](https://github.com/openglbook/openglbook-samples/releases)

## Remember That Poll? ##

Well, the results are in with 32.63% of the voters wanting C++ but no GLM support, 42.06% wanting C++ plus GLM support, and 25.31% wanting everything to remain the same.

<img
	src="{{ site.url }}/images/poll-results.png"
	alt="C++ poll results"
	title="C++ poll results"
	class="center"
/>

The focus of the poll was to determine if the samples should be written in C++ instead of C. I've had a lot of time to think about it, and regardless of the poll's results, I'm not converting the samples to C++. This decision comes from taking into account the many style differences, increasing complexity, and of course the massive effort it would take to convert everything. Not to mention that C is an easier language to learn and this site's main goal is to provide a resource that's easy to read.

There are a few other resources out there that *do* use C++ and even provide full frameworks that handle resource creation and storage that I personally believe should not be avoided if your aim is to learn these things yourself.

## So, What *Is* Next? ##

Besides bugs, I've also entered feature requests and enhancements to the [issue tracker on GitHub](https://github.com/openglbook/openglbook.com/issues?labels=feature-request%2Cenhancement&page=1&state=open). Not all of these may make it to the site, but it's a good indicator of what's coming next. Also, it's a good place to request a feature or chapter that you'd like to see.