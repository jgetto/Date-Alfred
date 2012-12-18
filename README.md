#Just give me the download already
http://tinyurl.com/date-alfred

#What's this about?

I got sick of firing up `node` or a browser JavaScript console for converting ms-since-epoch values to something I could actually understand.

This is a shortcut for:

    λ node -pe 'new Date($YOUR_MILLISECONDS_HERE)'

Supports [Extension Updater](http://jdfwarrior.tumblr.com/post/13826478125/extension-updater) (possibly excessive).

#Requirements

Requires [node](http://nodejs.org/) to be somewhere in a `$PATH` specified by `~/.profile`, `~/.bashrc`, or `~/.zshrc`. Sorry, Alfred shell script extensions don't load much by default.
