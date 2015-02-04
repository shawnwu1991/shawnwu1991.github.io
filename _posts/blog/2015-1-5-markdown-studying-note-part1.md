---
layout: post
title: markdown studying note (part 1)
description: Markdown is a popular light-level markup language in the programming world and I will use some blogs to record my experiences using this publishing format.
category: blog
tags: Jekyll Markdown
published: true
---


{{page.description}}

## 1. what is markdown ##
		Markdown's official definition is here [wiki](http://en.wikipedia.org/wiki/Markdown). In a word, markdown is a kind of light-rank markup language, which doing well in improving level of readability and being easier for people to catch the code's meaning.
		

## 2. Advantages ##
As the above words have been written, markdown uses the conception of tag to formating contents, helping creaters to understand the details. Compared with HTML, it is comfortable to write and read markdown language other than using HTML, which consisting of a plenty of <tag>. Nevertheless, markdown has no offense to take place of HTML but has a platform to be transfered to HTML - [Pandoc](http://johnmacfarlane.net/pandoc/try/)

## A brief introduction of syntax ##
1. making a new paragraph: <code><tag>code> ;
2. making head line (h1 ~ h6): 
	h1 <code> # text # </code>
	h2 <code> ## text ## </code>
	...
	h6 <code> ###### text ###### </code>
3. using '+' to create a out-of-order list, and using 'number.'(eg. 1. ) to create an ordering one;
4. creating a text link: <code>[link name](http://...)</code> and creating a image tag: <code>![img name](http://)</code>;
5. adding '_' or '*' to both sides of the text to strong words or sentences.

## Some awesome features ##
  
1. references links:
eg: 
<code>
filters -- including [Setext] [1], [atx] [2], [Textile] [3], [reStructuredText] [4],
[Grutatext] [5], and [EtText] [6] -- the single biggest source of
inspiration for Markdown's syntax is the format of plain text email.

  [1]: http://docutils.sourceforge.net/mirror/setext.html
  [2]: http://www.aaronsw.com/2002/atx/
  [3]: http://textism.com/tools/textile/
  [4]: http://docutils.sourceforge.net/rst.html
  [5]: http://www.triptico.com/software/grutatxt.html
  [6]: http://ettext.taint.org/doc/
</code>

2. h1 and h2 can alse be written as 
h1: <code>============</code>
h2: <code>-------------------</code>

If you want to know more details, you can broawse [the official desription of markdown][1]

Finally, thanks to markdown's designer - [John Gruber][2].

[1]:http://daringfireball.net/projects/markdown/
[2]:http://en.wikipedia.org/wiki/John_Gruber