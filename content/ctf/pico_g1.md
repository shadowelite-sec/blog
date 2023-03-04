---
title: "PICO CTF | OBEDIENT CAT"
date: 2023-02-28
tags: ["pico","picoctf","general skills","ctf"]
author: "ALAN S"
# author: ["Me", "You"] # multiple authors
showToc: true
TocOpen: false
draft: false
hidemeta: false
comments: true
description: "Desc Text."
disableHLJS: false # to disable highlightjs
disableShare: false
disableHLJS: false
hideSummary: false
searchHidden: false
ShowReadingTime: true
ShowBreadCrumbs: true
ShowPostNavLinks: true
ShowWordCount: true
ShowRssButtonInSectionTermList: true
UseHugoToc: true
---

its is a very very easy challange <!--more-->  

## STEP 1

Download The flag file to a directory

For now we have no idea what this file is, 
but we can easily identify the file type using the linux command `file`
![file](https://raw.githubusercontent.com/shadowelite-sec/blog/main/assets/pico/g1/file.png)

now we know the file is an ASCII text 

## STEP 2

The 'cat' command in Linux is a versatile tool that can be used to concatenate and display the contents of files on the standard output. there is the detailed manual [man cat](https://man7.org/linux/man-pages/man1/cat.1.html)


previousliy we found the the file is an ASCII text so we can use cat command to display what inside that file

![cat](https://raw.githubusercontent.com/shadowelite-sec/blog/main/assets/pico/g1/cat.png)

this is the flag
{{< css.inline >}}

<style>
.canon { background: white; width: 100%; height: auto; }
</style>

{{< /css.inline >}}
