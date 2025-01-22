# OpenCAE Viewer

The OpenCAE Viewer is a library written in C and JavaScript, which
uses the WebGPU API to display graphics. It provides an interface to
help in pre-processing and post-processing of simulation models written
using the OpenCAE library.

OpenCAE Viewer can be found at https://opencae.net/viewer

Report bugs and issues at 
https://github.com/Johann-Albers/opencae-viewer/issues

License: GPLv2

You can get the sources to the latest development version from the
git repository:

```
git clone https://github.com/Johann-Albers/opencae-viewer.git
```

Detailed build instructions can be found in the [INSTALL.md](/INSTALL.md)
file.

## Contributing

If you want to contribute code, please open a pull request with signed-off
commits at https://github.com/Johann-Albers/opencae-viewer/pulls.
If you don't sign off your patches, they will not be accepted. 
This means adding a line that says "Signed-off-by: Name <email>" at the
end of each commit, indicating that you wrote the code and have the right
to pass it on as an open source patch under the GPLv2 license.

The code you commit should be in a reasonable format. If you need ideas,
consider reviewing the existing codebase or searching the web for coding
guidelines similar to those used in the Linux project. This includes
structuring, commenting, documenting, testing, etc. etc.

Also, please write good commit messages. A good commit message looks
like this:

```
Header line: explain the commit in one line (use the imperative)

Body of commit message is a few lines of text, explaining things
in more detail, possibly giving some background about the issue
being fixed, etc etc.

The body of the commit message can be several paragraphs, and
please do proper word-wrap and keep columns shorter than about
74 characters or so. That way "git log" will show things
nicely even when it's indented.

Make sure you explain your solution and why you're doing what you're
doing, as opposed to describing what you're doing. Reviewers and your
future self can read the patch, but might not understand why a
particular solution was implemented.

Reported-by: whoever-reported-it
Signed-off-by: Your Name <you@example.com>
```

where that header line really should be meaningful, and really should be
just one line.  That header line should summarize the change in one
readable line of text, independently of the longer explanation.
Please use verbs in the imperative in the commit message, as in
"Fix bug that...", "Add file/feature ...", or "Make OpenCAE-Viewer..."
