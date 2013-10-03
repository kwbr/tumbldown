USAGE

    tumbldown SITE [DIRECTORY]

EXAMPLES

    Update a bunch of directories named after a tumblr site:

    for file in *; do
        if [ -d $file ]; then
            tumbldown $file
        fi
    done

RELATED PROJECTS

    https://github.com/nixterrimus/tumbld
    https://github.com/jamiew/tumblr-photo-downloader
    https://github.com/davidshaw/Tumblr-Scrape
    https://github.com/eljudni/fetchTumblrPics

COPYING

    This is MIT licensed Free Software

    Copyright (C) 2013 by
    Kai Weber
