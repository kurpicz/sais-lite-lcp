# sais-lite-lcp
This is an ad-hoc-implementation of the code described in ["Inducing the LCP-Array"](http://arxiv.org/abs/1101.3448) by [Johannes Fischer](http://ls11-www.cs.tu-dortmund.de/staff/fischer). It is based on Yuta Mori's [sais-lite 2.4.1](http://sites.google.com/site/yuta256), which is an implementation of the  following paper:

Nong, G., Zhang, S., & Chan, W. H. (2011). Two efficient algorithms for linear time suffix array construction. Computers, *IEEE Transactions on, 60(10)*, 1471-1484.

The original version of the code can be found [here](http://algo2.iti.kit.edu/english/1828.php).
## Building and Running
To build use the makefile and to test the code use the suftest as described below.

    make
    ./suftest <textfile>
    
Please notice that the *textfile* is required to be ended by a special sentinel value. Thus the last character of the text is automatically considered to be an unique character which is also the lexicographically smallest character.
#Contributors
+ [Johannes Fischer](http://ls11-www.cs.tu-dortmund.de/staff/fischer) (Author)
+ [Florian Kurpicz](http://ls11-www.cs.tu-dortmund.de/staff/kurpicz)

# Changelog
### Version 0.0.1
+ Initial Release
