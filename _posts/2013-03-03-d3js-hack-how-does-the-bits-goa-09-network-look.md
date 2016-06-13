---
layout: post
title: "d3.js Hack: How Does the BITS Goa '09 Network Look?"
---
<em ><strong >It looks like shit</strong></em>:?<a href="http://tvamev.in/index.htm" >http://tvamev.in/index.htm</a>?(Super slow+ CPU intensive, click with caution)

This is a hacky, very crude representation, and not just because this is only my second attempt??with d3.js.<a href="http://kanudeshpande.wordpress.com/mapping-friendships/" >?I'm using Melange data</a>, and a testimonial is a connection- no messing around with directionality, strength of the connection or anything like that.

I think it looks like shit because this is graph <em >not helpful!</em>?Surely this isn't how our network looks, it should be more grainy- we <em >know?</em>that there are a few well-connected people, but the rest mostly belong to one or two, somewhat closely knit cliques. I had hoped that we would write testimonials sparsely, but that was a fool's hope. This is how it is, this is really how '09 looks.

This is how almost all networks look- unhelpful splotches. <a href="http://www.wolframalpha.com/input/?i=facebook+report" >WolframAlpha's Facebook Report</a> and <a href="http://inmaps.linkedinlabs.com/" >LinkedIn's InMaps</a>?insights stop at the obvious- I have three splotches: work, school and college.
<img alt="" src="http://blog.mdmadman.com/wp-content/uploads/2012/04/youdontsay.png" ></img>

Yeah. Thanks, but I already know that. It's a pretty visualization...wait, it's not really a visualization. All three of us tried and failed to squash multi-dimensional data onto a map.

The graph still has some points of interest- I can't reveal them now because then you won't trust me with your data.

How do we curdle the splotch? I have no idea how you would go about visualizing (truly visualizing!) ?networks like these. So I'm working on it.

1- Second attempt with real data. For the first I made a map of the InMobi employee network. It was easy because it was a hierarchical network, at least in theory. It's very pretty-<a href="http://mbostock.github.com/d3/talk/20111018/cluster.html" > like this.</a>
