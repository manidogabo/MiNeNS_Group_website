---
# Title, summary, and page position.
linktitle: Writing
summary: Steps for setting up LaTeX writing in terminal via vim with PDF link support
weight: 3
icon: book
icon_pack: fas

# Page metadata.
title: Writing
date: '2024-01-24T00:00:00Z'
type: book # Do not modify.
---

{{% callout warning %}}
This page is still under construction!
{{% /callout %}}

We are in the business of creating knowledge and then sharing that knowledge, with an emphasis on sharing.
Writing is the means by which we document our creations and share it to the world. 
Thus, as I and many academics have found, writing is one of the most important aspect of my job.
While of utmost importance, writing has never come naturally nor have I ever desired to write for writing's sake.
Looking back, in my opinion, the most underdeveloped skill in my STEM education was writing and communication.
Thus, to uphold my responsibilities as a researcher, I have developed the following mindset and practices to aid my writing efforts.

## Writing is Thinking:

We are trained rigorously and become capable of doing challenging math and performing the scientific method in state-of-the art ways to solve problems.
Meanwhile, writing is often an afterthought we perform to document the thinking that we've already done.
However, that afterthough causes challenges to many of us as we try to navigate the correct way to document our thinking.
That's because writing is thinking.
To put one's thoughts on paper in a concise and coherent manner requires concies and coherent thought, active thought.
Further, as we write we can pick apart where are thoughts are not well-formed, require additional data to support, or are just flat-out wrong!
Thus, writing alongside the other activities helps to orient them and reduces the final load when we make deliverables to share to the world.

## Disciplines of Writing:

There is a reason the phrase, "_out of practice_", exists.
Top musicians and athletes are constantly honing their crafts.
When an interruption to activity causes top performers to rest and recover from pactice, they often have trouble coming back and performing at top levels.
Similarly, writing requires a practice and exercise to build and maintain our skills.
It is important to write frequently throughout the week in short intervals to work those writing muscles.
A dilligence to writing a certain number of times a week for a certain amount of time allows us to not only break up large writing tasks into smaller chunks but to also prepare ourselves for when we have to write for longer stretches at a time.
My baseline is 30 minutes per workday.
I set a meeting in my schedule and preserve that time for me to write unencumbered.

## Lowering the Activation Energy:

I try to make the writing environment convenient, fast, and distractionless. 
To accomplish these conditions I usually write in Mathematica notebooks or LaTeX.
I primarily use Mathematica notebooks for technical documentaition by usnig the native organization cells, performing calculations, and creating figures or plots.
I use LaTeX to write most other documents.

### Writing in Vim

Below, I document how I accomplish this in my terminal as my primary writing software on Mac.
I find this environment helps me to write faster and with less distraction than using other LaTeX IDEs. 

- Dependencies
    1. Iterm
    2. TeXLive
    2. Homebrew
- <span style="color:#F3B26D">**Steps**</span>
    1. Homebrew
        - install
        - add to path .zprofile
    2. NeoVim
        - install via Homebrew
    3. Install plugins from vim-plug
        - .local/nvim/init.vim
    4. Configure
        - .zshrc
        - .configure/neovim
- Other tools
    1. Ranger
        - Configure
    2. 
