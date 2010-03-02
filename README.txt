The Ruby 1.9.1p376 RDoc documentation.

Compiled by Jeff Reinecke <jeff@paploo.net> and posted at http://github.com/paploo/ruby-rdoc/.

After an hour minutes and over 3.3 GB of RAM (to the process) to compile this
on my MacBook Pro with a 64-bit compiled ruby, I aborted.  Around 3.2 gigs, things went to swap, the speed of processing went to 1/10th of what it was.  So then I went to my old version of p129 (which was compiled 32-bit) and it took about 30 minutes and only used 2.3 GB of RAM.

After having installed Ruby 1.9.1p376 and verified it worked, I changed
directories to the root ruby-1.9.1p376 director and ran:
  $ rdoc --all --line-numbers --promiscuous --op rdocs .
