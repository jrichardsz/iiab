============
Kiwix README
============

Kiwix develops ZIM file creation & rendering tools for offline action,
as summarized at: http://wiki.kiwix.org/wiki/Software

Internet-in-a-Box uses the kiwix-serve and kiwix-manage executables (in
/opt/iiab/kiwix/bin) to set up and render ZIM files such as Wikipedia, and
other educational materials: http://download.kiwix.org/zim/

Locations
---------

- Your ZIM files go in /library/zims/content
- Your ZIM index files go in directories under /library/zims/index (these index files are increasingly no longer necessary, as most ZIM files produced since 2017 contain an internal search index instead!)
- The URL is http://box/kiwix or http://box.lan/kiwix (both proxied for AWStats)
- Use URL http://box:3000/kiwix/ if you want to avoid the proxy

Your local ZIM catalog (at /library/zims/library.xml) can be regenerated by running:
/usr/bin/iiab-make-kiwix-lib

See "How do I add ZIM files, like Wikipedia?" at http://FAQ.IIAB.IO
