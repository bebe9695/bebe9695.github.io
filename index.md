---
layout: default
mathjax: true
---


## Welcome to the Bebe World

**Statistics $ + $ Linear Algebra $ + ... = $ Awesome $ + $ (Cool)$^n$**  
**\#NetBioMed**  


[Link to Images Page](./images.html).   
 
 ![Image](sleepy.jpeg)
 
 <dl>
  <iframe src="https://www.facebook.com/plugins/video.php?href=https%3A%2F%2Fwww.facebook.com%2Fseerlight%2Fvideos%2F2758646667698539%2F&show_text=0&width=380" width="380" height="476" style="border:none;overflow:hidden" scrolling="no" frameborder="0" allowTransparency="true" allowFullScreen="true"></iframe>  
 </dl>


```python
G = nx.erdos_renyi_graph(20, 0.1)
color_map = []
for node in G:
    if node < 10:
        color_map.append('blue')
    else: 
        color_map.append('green')      
nx.draw(G, node_color=color_map, with_labels=True)
plt.show()
```
### Selected Humor with a Hint of Truth at Times
* Modi's radio blabber should be called "Monkey Baat".
* Although I am a mathematician, with by bebe, I don't need to find my x.  
* What is Bruce Lee's favourite flower? Ans: Lily.  
