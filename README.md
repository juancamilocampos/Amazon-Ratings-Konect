Amazon ratings network, part of the Koblenz Network Collection
===========================================================================

This folder contains the TSV and related files of the amazon-ratings network:

This bipartite network contains product ratings from the Amazon online shopping website. The rating scale ranges from 1 to 5, where 5 denotes the most positive rating. Nodes represent users and products, and edges represent individual ratings.


More information is provided there: http://konect.uni-koblenz.de/networks/amazon-ratings

Files: 
    meta.amazon-ratings -- Metadata about the network 
    out.amazon-ratings -- The adjacency matrix of the network in space separated values format, with one edge per line
      The meaning of the columns in out.amazon-ratings are: 
        First column: ID of from node 
        Second column: ID of to node
        Third column: edge weight
        Fourth column: timestamp of the edge

All files are licensed under a Creative Commons Attribution-ShareAlike 2.0 Germany License.
For more information concerning license visit http://konect.uni-koblenz.de/license.



Use the following References for citation:

@MISC{konect:2014:amazon-ratings,
    title = {Amazon ratings network dataset -- {KONECT}},
    month = feb,
    year = {2014},
    url = {http://konect.uni-koblenz.de/networks/amazon-ratings}
}

@inproceedings{konect:lim2010,
 author = {Lim, Ee-Peng and Nguyen, Viet-An and Jindal, Nitin and Liu, Bing and Lauw, Hady Wirawan},
 title = {Detecting Product Review Spammers Using Rating Behaviors},
 booktitle = {Proc. Int. Conf. on Information and Knowledge Management},
 year = {2010},
 pages = {939--948},
}

@inproceedings{konect:jindal2008,
 author = {Jindal, Nitin and Liu, Bing},
 title = {Opinion Spam and Analysis},
 booktitle = {Proc. Int. Conf. on Web Search and Web Data Mining},
 year = {2008},
 pages = {219--230},
}

@inproceedings{konect:mukherjee2012,
 author = {Mukherjee, Arjun and Liu, Bing and Glance, Natalie},
 title = {Spotting Fake Reviewer Groups in Consumer Reviews},
 booktitle = {Proc. Int. Conf. on World Wide Web},
 year = {2012},
 pages = {191--200},
}


