Created with the command 'softcover new softcover_example' do demostrate an issue with the LaTex `input` command.

According to the [documentation](http://manual.softcover.io/book/softcover_markdown#sec-input), one should be able to use the `input` command to include Markdown from another file.

- `input` doesn't work without the suffix. E.g `preface` contains `\input{chapters/a_chapter}`, but the content does not render.
- including the md suffix, the contents is rendered, but not all is processed. Hyperlinks remain unrendered.
- pasting the contents into the file, correctly processes the markdown.  `a_chapter` renders correctly.