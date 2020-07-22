## Welcome to the Bebe World

This is a joint webpage of bebe and bebe-shebe.  
 ![Image](logo.png)

```markdown
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
