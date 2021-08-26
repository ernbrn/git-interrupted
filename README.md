# git interrupted / git uninterrupted

## Why
It's happened to you. There you were, working away on a big feature. And, ok, maybe you haven't been super great at committing while you're ahead so your working tree is more like a forest. Then, oh no suddenly something on production is breaking and your boss is Slacking you and asking if you can take a look at it _right now_. 🔥🔥🔥

When you get interrupted, use `git interrupted`. 

## What
`git interrupted` is a highly suspect, extremely WIP, not yet robust CLI that will take your whole working tree, put it into a temporary commit and pop you onto `main`.

When you've put out the fire and your working tree is clean again, `git uninterrupted` will put you back onto the branch where you left off and put your changes back into the messy state it was before all this started. 

## How

To use this, download this project (or clone or fork or whatever), and just make sure the files are in your path. So in your bash or zsh rc, do this:

```
export PATH=$PATH:/<path-to-file-you-just-downloaded>/git-interrupted
```

Restart your shell and give it a try!

## Did you test it?
A few times!

## Will you personally use it?
Absolutely! 

## Can I trust it for my fun pet project that isn't super important?
Probably!

## Can I trust it for my super important, once in a lifetime, un-reproducible work?
😬

## Hey isn't this just `git stash`?
Just getting that question out of the way since several men have asked me this.