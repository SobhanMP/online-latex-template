# An alternative workflow to overleaf

I use overleaf a lot in my work but i have a series of problem with it. The history is hard to use, it's not clear who wrote what when, and the render time is high. Furtheremore, copy pasting the text into software and back removes all comments so using grammarly or the like, or building the file locally is not an option.

To remedie these, this repo is set up such that any commit will trigger a pdf build. Comments and online edits can be done via the github online editor.

To use this, reimport (or fork) this repo. It will automatically rebuild the `document.tex` file. Note that forks cannot be private in github.

This is powered by github actions. This repo uses softprops/action-gh-release@v1 and xu-cheng/latex-action@v2. Also thanks to whomever came up with the release tag hack for release@v1.
