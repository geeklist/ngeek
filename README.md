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
    
    33     - achievements / decs 
    2444   - views

    ---------------------------------------

    23     - messages (+2 new ones)
    234    - high fives (+ 5 new ones)
    4045   - endorsements (+1 new ones)
    23     - followers (9+ new ones)
    33     - collaborators (0 new ones)
    
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


Code Contribution Agreement
=====

By contributing code to the Geeklist, Inc code base you certify that you have read 
and understand the statement below on Ownership of Intellectual Property and agree to 
all terms therein;

(A) Upon the first commit to the Geeklist code base you grant Geeklist, 
it’s successors and owners perpetual and unlimited rights to use the contribution 
for any purpose deemed relevant to Geeklist, Inc. For any contribution you make 
to the Geeklist repository, you have made all reasonable efforts to determine the 
legal owners of the contribution, and obtained the permission of the owners of the 
contribution to make the contribution available under an open source license certified 
by the Open Source Initiative;

(B) if you are employed, you have discussed contributing to Geeklist with your employer, 
and have obtained their permission to contribute or have determined that they do not 
assert ownership rights to my contributions;

(C) Geeklist is under no obligation to compensate you, your company or any entity for 
any code contributed now or in the future; unless under expressly written agreement 
for compensation signed by Geeklist Officers of the company. You may not lay any claim 
against the company or it’s partners or subsidiaries for contributions made voluntarily.

(D) You will not knowingly submit any contribution of which you are not the owner or
for which you do not have the owner's permission;

and

(D) You will release and hold harmless Geeklist from any liabilities which may arise 
from the use of your contribution. You may be held liable in the event of a breach of 
any of these terms.

If you disagree or can not abide by these regulations, do not contribute to the 
Geeklist code base. You may contact info@geekli.st if you need any clarity. 
We are built by developers for developers so please share your questions or request 
to contribute. Thank you!



