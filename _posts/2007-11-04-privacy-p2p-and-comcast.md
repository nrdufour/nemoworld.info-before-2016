---
layout: post
title: Privacy, P2P and Comcast
---

For a while, you can read <a href="http://web.archive.org/web/20080206160955/http://www.boingboing.net/2007/10/20/how-the-ap-busted-co.html">articles</a> talking about Comcast blocking BitTorrent traffic on their network.

I have tried several times to use it and yes I had few problems here and there: the torrent was more a tiny stream than something else or even a drought !

Now, perhaps it’s time to think of we use Internet. Specially the server centric way... P2P is known to solve a lot of problems by dispatching a task to multiple points and use that network as a force rather than a weakness.

<hr />

The first point is clearly the privacy. It’s difficult to preserve it, specially if you have to give name, address and other stuff to a company just to subscribe to a newsletter !You can use:
<ul>
 	<li><a href="http://www.torproject.org/">tor</a>: Tor provide a fairly good solution to maintain your identity hidden by using other tor network nodes to relay randomly your encrypted communications.</li>
 	<li><a href="http://www.i2p.net/">i2p</a>: i2p doesn’t focus on hiding your true identity for others, but simply make both the sender and the receiver anonymous. This is done by a constant exchange of encrypted messages between i2p nodes using p2p. The network itself avoid anybody to know who you are.</li>
</ul>

I have found also 2 nice projects interesting to follow :
<ul>
 	<li><a href="http://yacy.net/">YaCy</a>: YaCy is a search engine using p2p connections between its network to exchange indexes. It’s again using the network instead of big farms of servers/crawlers such as Google’s ones ;)</li>
 	<li><a href="http://dijjer.org/">Dijjer</a>: provides a good way to easily publish a file using a p2p network. Let’s say that you have a fairly big file to share (example: sources of your open source project …) but want to avoid to have your server to be blocked because you’ve reached too much traffic. Then p2p is clearly the ideal solution already used by numbers of companies such as Blizzard or Novell.</li>
</ul>

I will update this blog about those tools with my experiments ;) see you soon

<blockquote><strong>Update</strong> (1.15am): I have also found this <a href="http://web.archive.org/web/20080206160955/http://whalesalad.com/2006/08/27/tunneling-bittorrent-over-ssh/">article</a> talking of tunneling bittorrent through ssh when it doesn’t work.</blockquote>