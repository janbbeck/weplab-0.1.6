# weplab-0.1.6
WEP key cracking program. Can use statistical methods or brute force.

This is simply the good old weplab we all know. The original sourceforge site seems to be down and I needed to put in some fixes to get it to compile on Ubuntu 18.10. Also multithreading got broken along the way somewhere, so I fixed that up too.

I did this work because I wanted to know how long it would take in 2019 to brute force the effectively 40 bit key. I found that on even single threaded on a cheap laptop it's done in a month. A single compute-optimized Amazon instance can do the whole key space in a day.
