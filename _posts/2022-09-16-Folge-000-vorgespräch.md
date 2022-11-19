---
title: Folge 0 - Vorgespräch
author: letztereiheparkett
date: 2022-09-15 23:49:00 +0100
categories: [Podcast]
tags: [podcast]
html: https://archive.org/download/lrparkett-podcast-folge-0-vorgesprach/LRParkett%20Podcast%20Folge%200%20-%20Vorgespr%C3%A4ch.mp3
---

## Vorgespräch

In ihrem ersten mikrofonalen Aufeinandertreffen wollen Dominik und Yves wichtige und grundsätzliche Dinge für ihren anstehenden Podcast besprechen.\\
Nach holprigem Start, geraten die beiden dann doch ins "Schwätzen" und merken dabei, dass sie mit ihrem Vorhaben noch weit am Anfang stehen.
<br>
<br>
{% include plyr.html audio=page.html %}

 <audio controls>
  <source src="https://archive.org/download/lrparkett-podcast-folge-0-vorgesprach/LRParkett%20Podcast%20Folge%200%20-%20Vorgespr%C3%A4ch.mp3" type="audio/mpeg">
</audio> 

<link rel="stylesheet" href="https://cdn.plyr.io/3.7.3/plyr.css" />

<script src="https://cdn.plyr.io/3.7.3/plyr.polyfilled.js"></script>

<script>
const player = new Plyr('audio', {
	controls: [   
                'restart', // Restart playback    
                'rewind', // Rewind by the seek time (default 10 seconds)    
                'play', // Play/pause playback   
                'fast-forward', // Fast forward by the seek time (default 10 seconds)    
                'progress', // The progress bar and scrubber for playback and buffering    
                'current-time', // The current time of playback    
                'duration', // The full duration of the media    
                'mute', // Toggle mute    
                'volume', // Volume control    
                'settings', // Settings menu    
                'download', // Show a download button with a link to either the current source or a custom URL you specify in your options    
            ]
});

// Expose player so it can be used from the console
window.player = player;

</script>