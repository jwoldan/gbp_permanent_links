gbp\_permanent\_links\_jrw
=======================

_gbp\_permanent\_links_ is an excellent plugin for [Textpattern][tp] created by Graeme Porteous.  For more information about the plugin, see the [post][] in the Textpattern forum.

[tp]: http://textpattern.com/
[post]: http://forum.textpattern.com/viewtopic.php?id=18918

This version of the plugin adds support for custom permalinks for articles that share the same url-title where the article permalinks differ only by date components.  For example, given two articles in a single section with the url-title of 'article' posted on different days, the plugin is able to correctly map the following /section/year/month/day/article permalinks:

	/section/2011/02/11/article
	/section/2011/02/10/article

As long as the date elements of the url (combined with the title) are enough to uniquely identify it, the same title can be reused, even within a single section.

If more than one article with the same url-title exists in a section when using a permalink scheme such as /section/title, the most recent article will be display at that url.  Older articles with that same title would be inaccessible by this URL scheme.

I've just barely figured out enough of the plugin to implement this, and it works on my site.  There is no guarantee it will work on yours, but if it doesn't, feel free to let me know.