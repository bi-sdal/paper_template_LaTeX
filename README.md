# sdal_paper_template
LaTeX Template using Child Documents


The `master.tex` document is used to stitch together the various child documents.

The child documents are in the appropriate folders.
Currently figures need to placed in the folder that the child document needs.
I still need to figure out how to get this to work by putting all the figures into a separate `figure` folder

To get references, you need to compile the document twice (this is a normal LaTeX thing).
However, if you compile a child document that places a `ref` to a different child document `label`, it will show up as `??`.
You will only get the correct reference number when the `master.tex` is compiled
