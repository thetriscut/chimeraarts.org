# ChimeraArts.org

The website source code for <http://www.chimeraarts.org>.

If you've found a problem with the site (missing content, typos, etc...), please either fork this repository and send a pull request or [create an issue](/chimera/chimeraarts.org/issues).

## Development

The website is built with [Hugo](http://hugo.spf13.com), a static site generator written in Golang.

To develop using the site, just download the Hugo binary in your platform (Mac, Win, Linux) and run `hugo server --watch --source=./` in this directory.

Any changes to the `static`, `content`, and `layouts` directories will automatically be compiled into the `public` dir. 

Site content is found in the `content` directory and is written in Markdown.

Once you've completed your changes, commit the changes and submit a pull request.

## License

Content released under the [Creative Commons Share-Alike 2.5 License](http://creativecommons.org/licenses/by-sa/2.5/).

## Credits

Created by [Dana Woodman](http://danawoodman.com).

Thanks to [Hugo](http://hugo.spf13.com) for making this easy for us.