This is a self-contained example that demonstrates that hovering on edges does not reset the edge style color to its default values. Hover does work correctly on nodes, although the update times are slow. 

To replicate, download the files, start a server, I use: 

```
http-server
```

and type `localhost:8080` in a browser. This will load up `index.html`. Howver, over the nodes and edges. Nodes turn red and return to their default color. Edges change color on hover, but do not return to their default state. 

