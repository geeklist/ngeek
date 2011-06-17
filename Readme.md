ngeek (Coming soon)
=====

ngeek is a node.js CLI tool for accessing and posting info to and from Geekli.st

Installation
------------

With [npm](http://github.com/isaacs/npm):

    npm install ngeek

CLI
---

    Usage: ngeek [options] [data]
    
    [Options]
    -i, --init        Initialize (here you need to add your developer key)
    -h, --help        Display this help page
    -s, --stats       Display stats
                        ex: ngeek -s
                        ex: ngeek --stats
                        ex: ngeek 

Example
---

    $>ngeek
    
    ///// STATS //////
    
    23    - messages (+2 new ones)
    234   - high fives (+ 5 new ones)
    4045  - endorsements (+1 new ones)
    23    - followers (9+ new ones)
    
Todo
---
    
    [Options] [data]
    -e, --endor       Display latest endorsements
    -a, --hfive       Display latest high fives
    -f, --foll        Display latest followers
    -f, --msgs        Display latest messages
    -t, --tweet       Post to twitter
                        ex: ngeek -s -t (posts your stats to twitter)
                        ex: ngeek -f -t (posts your followers to twitter)





