# Sarah Marie Larson's Pretty Website!

To build, run

``` sh
hugo server -p 1313
```
    
in the terminal, and then open the local page [here](https://127.0.0.1:1313). Any changes you make
(and save!) will automatically reload.


## Adding new content

To add a new image, create `new-file.md` in either `content/artwork`, `content/photograph` or `content/graphic-design`, and then copy the template below into that file:

``` markdown
+++
showonlyimage = false
draft = false
image = "img/photography/jam.jpg"
date = "2016-04-15"
title = "Jam"
weight = 0
+++

Jam with California strawberries.

<!--more-->

![figure1][1]

More about the work (after clicking on it).


[1]: /img/artwork/figure1.jpg

```
and replace the things.

## Pushing Changes

When you're done making changes, click on the git sidebar:

![git sidebar](/images/git_sidebar.png)

And then:
1. **Add the changes** by clicking mousing over "Changes" and clicking on the `+` symbol.

    ![add changes](/images/add_changes.png)

2. Write a commit message and hit `CTRL-ENTER`.

    ![commit](/images/commit_message.png)
    
3. Push changes!

    ![push](/images/push_changes.png)

## Closing Down

When you're finished, either close VS Code or click in the terminal and press `CTRL-C`.