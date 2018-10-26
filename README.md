# Finch

*updated Oct 26, 2018*

My test site: <http://finch.soupmode.com>.

At the moment, Finch does little. 

A text file contains the URLs of the feeds.

A Lua script executes in cron. 

The script reads the feeds file, accesses the feeds, creates an HTML file for each feed, and creates a homepage HTML file with the links to each feed HTML file.

Maybe I'll add a web interface to manage the feeds, to manage new and unread posts, etc.

I doubt that I go as far as supporting the interesting Microsub spec, produced by the IndieWeb community, for the client and the server.

<https://indieweb.org/microsub>

Currently, Finch supports processing the following feed formats: RSS, Atom, and the humorously useful [RSS3](http://sawv.org/2018/08/21/rss-30-jokey-but-useful-spec.html). 

I'd like to add support for the Reece-Simmons [JSON Feed format](https://jsonfeed.org) and the IndieWeb's [h-feed](https://indieweb.org/h-feed).
