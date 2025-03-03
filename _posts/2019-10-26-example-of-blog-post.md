---
layout: post
title:  "Running VoiceSauce raw/remotely"
date:   2025-03-03 11:48:00
blurb: "VoiceSauce."
og_image: /assets/img/content/post-example/Banner.jpg
---

<img src="{{ "/assets/img/content/post-example/Banner.jpg" | absolute_url }}" alt="bay" class="post-pic"/>
<br />
<br />

[VoiceSauce](https://www.phonetics.ucla.edu/voicesauce/) is an open-source software tool for automated voice analysis (Shue et al., 2011). It offers a wide range of acoustic measurements, making it a valuable tool for studying human speech.  

In my work, I needed to process a large number of audio files, which made running VoiceSauce through the MATLAB GUI on my MacBook inefficient. So I developed a wrapper function that allows VoiceSauce to run both on my Mac environment and a remote Linux server. 

If you're dealing with similar challenges, you can find my wrapper code here:  
➡ **[Chloe's GitHub repo for VoiceSauce](https://github.com/chloedkkwon/voicesauce_matlab?tab=readme-ov-file)**  

Follow the instructions in the repository, and you should be able to adapt it for your own setup. Let me know if you have any questions or need help customizing it!  

<br />



##### FOOTNOTES

[^1]: This is a note!
