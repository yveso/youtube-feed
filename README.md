# youtube-feed

Some feed readers have problems recognizing Youtube feeds, if the channel url (like https://www.youtube.com/channel/_???_/videos) doesn't contain a real name but a gibberish id.
Sometimes feeds based on such a url don't contain all the videos.

But everything works fine using a gdata url (like http://gdata.youtube.com/feeds/api/users/_???_/uploads).

As I am lazy, this project gives a simple (very simple) function to create those urls based on a user id.