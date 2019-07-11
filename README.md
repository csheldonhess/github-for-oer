Using GitHub to support OERs
============================

This, right here, is technically an OER, developed and shared via GitHub. It's not fancy, but they don't all have to be, do they?

What is GitHub?
---------------

Originally created to help people share and build on each other's code, GitHub is what's known as a "version control" system. Version control solves this problem:
[![a bunch of file names for the same file](images/phd052810s.gif)](http://phdcomics.com/comics/archive.php?comicid=1323)

For people who want to read more about version control, [ProfHacker did a gentle introduction](https://www.chronicle.com/blogs/profhacker/a-gentle-introduction-to-version-control/23064) a while back.

Additionally, GitHub solves the problem of keeping your projects safe&mdash;backed up to the cloud&mdash;and making it easy\* to share and collaborate on with other people.

GitHub is only one of the many version control solutions available, but it's probably the most popular, not only with programmers, but with academics of all stripes (technical and non-technical). It has apps for Windows, Mac, and Linux.

\* OK, it takes a few hours to really get down how it works, maybe a full day to get to the point where you're comfortable enough with it to collaborate on a bigger project. There's a learning curve, but it's like anything: easy once you know how to do it.

The 4-6 R's
-----------
(Definitions for the first five are from [OpenContent.org](https://opencontent.org/definition/))

* **Retain** - the right to make, own, and control copies of the content (e.g., download, duplicate, store, and manage) 
* **Reuse** - the right to use the content in a wide range of ways (e.g., in a class, in a study group, on a website, in a video)
* **Revise** - the right to adapt, adjust, modify, or alter the content itself (e.g., translate the content into another language)
* **Remix** - the right to combine the original or revised content with other material to create something new (e.g., incorporate the content into a mashup)
* **Redistribute** - the right to share copies of the original content, your revisions, or your remixes with others (e.g., give a copy of the content to a friend)
* **[Request updates](https://boffosocko.com/2018/08/30/the-sixth-r-of-open-educational-resources-oer/)**

### GitHub's answers to the R's:
* Stores content locally to your machine(s) and also in the cloud
* Easy for others to download and duplicate from your GitHub page - can access and download a whole project or any subset of it from any internet-connected machine
* You (or others, with your approval) can make updates from any machine with Git installed
* A single project on GitHub can pull in other people's content from GitHub, add links to Google Docs, add images and videos, and generally mix and match content as needed
* While Git's version control is most powerful with text content (including text files, source code, data in CSV and other "flat" formats, and Markdown), you can add any kind of file to GitHub, including raw video or other formats you might want to allow others to download and remix into new projects.
* If you choose to make your content public, it's indexed by Google and discoverable by other people who are working on similar things
* Some attribution is done automatically, by tracking "forks" from one project to another
* People can file "bug reports" on your projects, and they can offer updates that the project owner(s) can accept or reject
* Changes are tracked over time, and you can look at the history of a project -- and even go back to a previous version, if you care to do so

Examples of OERs using GitHub
-----------------------------
We're going up in scale from "not fancy" to "really fancy," although when I'm talking about this I might show them to you in reverse order.

### Really just using GitHub as version control for the source code that runs their class website
* [Hacking Humanities](https://github.com/karlstolley/hh) - I want to be clear: this is entirely valid and great, and it makes these webpages easier to reuse/remix than if they were just sitting on the school's server. I absolutely count this as an OER, whether or not this is what people mean when they say "OERs on GitHub."


### Using basic GitHub repositories with Markdown files and/or Jupyter notebooks to hold most of the content
* this one, right here, that you are looking at 
* [my Python 1 course for CCAC](https://github.com/csheldonhess/dat-119-2019-spring), which is based heavily on [Elizabeth Wickes's Python 1 course for library students](https://github.com/elliewix/IS-452-Fall2018) - Jupyter notebooks are interactive when you download them to your machine, although GitHub renders a version of them on the cloud, as well. They're good teaching tools if you're doing Python, R, or SAS, and GitHub's a good place to store them.
* [Command Line Bootcamp](https://github.com/csheldonhess/c4l16-cli-workshop) - A colleague and I (so you can see that this is an example of a project with forks) built this together and co-ran this workshop a couple of years ago. Other people have forked it, changed it, and re-run it their own way. 

### Using GitHub to serve static webpages
* [Make OER](https://evanwill.github.io/make-oer) - A website created for a workshop at a library conference last year, with some good content about making OERs with GitHub. You can fork it and create your own version from [his GitHub site](https://github.com/evanwill/make-oer). As the theme name ("workshop-template-b") implies, the theme he used was probably designed for building teaching websites.
* [Software Carpentry - Git Novice](https://swcarpentry.github.io/git-novice/) - All of Software Carpentry's stuff is put together with GitHub pages; and as an organization, they think a lot about pedagogy and inclusiveness in a technology classroom. You could do worse, looking for a place to teach yourself Git. And, again, it's all hosted right on [GitHub](https://github.com/swcarpentry), so you can download, edit, and reuse any of it (with attribution).
* [Teaching and Learning with Jupyter](https://jupyter4edu.github.io/jupyter-edu-book/) - Again, it's built on GitHub pages and accessible via [GitHub](https://github.com/jupyter4edu/jupyter-edu-book), but here we have something that's designed to act much more like a book than a website. (And again, it's very good.)


### Honorable mentions: 

#### Syllabi shared on GitHub:
(This concept has been stuck in my head since I read [the ProfHacker article on it](https://www.chronicle.com/blogs/profhacker/forking-your-syllabus/39137). There's also a [howto](https://www.chronicle.com/blogs/profhacker/how-to-fork-a-syllabus-on-github/39447).)

* [MO4971 City in East and Southeast Asia 1850-1950](https://github.com/kmlawson/city-in-east-and-southeast-asia) - Most of the content is in Markdown files, but there's a LaTeX file, as well.
* [Public Opinion, Political Psychology and Citizenship](https://github.com/leeper/opinioncourse) - A few of the course materials seem to be included in this one, actually, not just the syllabus. It also has a "[why GitHub](https://github.com/leeper/opinioncourse/blob/gh-pages/fork.md)" section, which is cool.

#### Wired's meta-article about writing an article on GitHub:
https://www.wired.com/2012/02/github-revisited/

#### A cheatsheet on Markdown:
* [Markdown Here](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) - This gets stuck down in honorable mentions because I don't want to go into the difference between a GitHub repo and a GitHub wiki, but I still want you to have access to this very good reference for Markdown syntax.



[![This work is licensed under Creative Commons Attribution ShareAlike](images/CC-BY-SA_icon.png)](https://creativecommons.org/licenses/by-sa/4.0/legalcode)