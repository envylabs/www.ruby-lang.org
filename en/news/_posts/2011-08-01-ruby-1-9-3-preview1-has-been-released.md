---
layout: news_post
title: Ruby 1.9.3 preview1 has been released
---

Ruby 1.9.3 preview1 has been released. This is a first preview of next
version and there're still minor known issues. But it will be fixed in
next release, Ruby 1.9.3-p0. See [ChangeLogs][1] and [NEWS][2] for the
descriptions. 

## Downloads

* [http://ftp.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-preview1.tar.bz2][3]<br />
  SIZE: 9507455 bytes<br />
  MD5: 7d93dc773c5824f05c6e6630d8c4bf9b<br />
  SHA256: a15d7924d74a45ffe48d5421c5fc4ff83b7009676054fa5952b890711afef6fc
* [http://ftp.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-preview1.tar.gz][4]<br />
  SIZE: 12186410 bytes<br />
  MD5: 0f0220be4cc7c51a82c1bd8f6a0969f3<br />
  SHA256: 75c2dd57cabd67d8078a61db4ae86b22dc6f262b84460e5b95a0d8a327b36642
* [http://ftp.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-preview1.zip][5]<br />
  SIZE: 13696708 bytes<br />
  MD5: 960e08b2dc866c9987f17d0480de63a1<br />
  SHA256: 249483f88156b4ae65cd45742c6f6316660f793b78739657596c63b86f76aaeb

### Differences from previous version

Previous Ruby versions was licensed under "GPLv2" and "Ruby" license
but "2-clause BSDL"(AKA Simplfied BSD License) and "Ruby" lisence
been replacement of them.

### Encoding

SJIS changed to alias for Windows-31J, instead of Shift_JIS.

### Standard Libraries

* io/console: Add capabilities to IO instances.
* openssl
* test/unit: supports parallel test

### Other changes

* pathname and date are re-implemented on current preview.
* A purpose of VM locking is changed.

[1]: http://svn.ruby-lang.org/repos/ruby/tags/v1\_9\_3\_preview1/ChangeLog
[2]: http://svn.ruby-lang.org/repos/ruby/tags/v1_9_3_preview1/NEWS 
[3]: http://ftp.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-preview1.tar.bz2 
[4]: http://ftp.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-preview1.tar.gz 
[5]: http://ftp.ruby-lang.org/pub/ruby/1.9/ruby-1.9.3-preview1.zip 