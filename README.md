# Prose Grinder

Writing fiction is hard. So is the publishing process. This collection of tools aims to make both eaiser.

## Who is Prose Grinder

For now, it's just [David Day](https://www.davidlday.com).

I write code and fiction. I'm not a famous author, and I don't strive to be. I love telling stories, I love learning, and I want to become the best storyteller I can. And maybe sell a few things along the way, of course.

## Creating Stories is Not Typesetting

Word Processors are a distraction. They force you to continually think about typesetting and format instead of freeing you up to focus on crafting a story. I switched to using a text editor for writing toward the end of 2017. I use both [Atom](https://atom.io) and [Visual Studio Code](https://code.visualstudio.com/), and have found Atom a little more suitable to writing prose.

### Text Editor

[Atom](https://atom.io) is a free text editor, and calls itself "A Hackable Text Editor for the 21st Century." I use it for writing fiction. I just like it better for writing Markdown.

### Markdown?

> [Markdown](https://daringfireball.net/projects/markdown/) s a text-to-HTML conversion tool for web writers. Markdown allows you to write using an easy-to-read, easy-to-write plain text format, then convert it to structurally valid XHTML (or HTML).

Originally used for authoring websites, Markdown has caught on quickly as a de facto language for rapidly authoring documents and delaying typesetting / formatting / presentation concerns until later. [GitHub Flavored Markdown](https://help.github.com/articles/basic-writing-and-formatting-syntax/) is in popular use by programmers today to maintain documenation without being overburdened by the typical impositions of a word processor.

Both Atom and Visual Studio Code have built-in support for Markdown, plus additional packages for previewing and authoring.

### What About Spelling and Grammar?

One thing that keeps us chained to our word processors is the need for spelling and grammar checking. However, there is an Open Source, stand-alone alternative called [LanguageTool](https://languagetool.org/). You could go and download it directly, install it as a service locally or run it from the command line, but you don't have to. If you switch to [Atom](https://atom.io) or [Visual Studio Code](https://code.visualstudio.com), both have packages availabe that add LanguageTool's capabilities to them.

* [Linter-LanguageTool for Atom](https://atom.io/packages/linter-languagetool)
* [LanguageTool for Visual Studio Code](https://marketplace.visualstudio.com/items?itemName=adamvoss.vscode-languagetool)

## But isn't Typesetting Still Necessary

Yes, it is. Every publisher has submission guildelines that include formatting. Sometimes these guidelines are nuanced, in part to see if the writer can follow directions, but most will be okay with a manuscript formatted using [William Shunn's Proper Manuscript Formatting](https://www.shunn.net/format/) guidelines. Remember Markdown above? It's no longer used just for creating HTML. It can also be turned into .docx format (as well as many others) using a little bit of technological magic known as [Pandoc](https://pandoc.org).

Unfortunately, pandoc has somewhat limited support for creating .docx templates, but I'm working on creating the set of data files needed to specifically generate [Short Story](https://www.shunn.net/format/story.html) and [Novel](https://www.shunn.net/format/novel.html) formats from Markdown. I have it working for me, but not in a reusable way. I'll be moving that work to GitHub in the near future.

## What about X, Y, and Z?

Yeah, I'm gonna cover those later. For now, I just wanted to get some thoughts down on the fundamental pieces needed for bigger work ahead. There are many things I've learned in working in IT that I think can and should be applied to the entire publishing value chain, things I think folks like Amazon have either missed or chosen to ignore because they're difficult or impossible to monetize without violating the concept that...

## All Money Flows to the Writer

If someone's charging for a good or service that can't directly be linked to you selling a story, then skip it. Automating the publishing value chain doesn't mean creating a space where anyone can barf up words and throw it up for sale. That's bypassing the value chain by eliminating the quality checks of various gatekeepers. Editors have tremendous value. Publishers have tremendous value. Distributors as well. Retailers, too. Value Chain Acceleration happens by making the tasks done along the way happen faster, not by eliminating them.

## Where are the Tools?

A few are linked inline above, but I have many others in the planning stages, including:

* A free submission management service
* A free marketplace analytics service
* A free reader analytics service
* A modern approach to selling publications backed by the above

Free. Because money flows to the writer.





