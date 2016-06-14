# pacvis

Visualize pacman database using [Vis.js](http://visjs.org/),
inspired by [pacgraph](http://kmkeen.com/pacgraph/).

![full](full.png)
![zoomin](zoomin.png)

## How to use

Install tornado, then:

```python
python pacvis
```

Then go to `http://localhost:8888/?maxlevel=40`.

You may need to zoom in initially to see the rendered picture.
Currenly we have scalability issue when there are too may packages, so we need
`maxlevel` to limit the level of dependency depth.

To be continued ...
