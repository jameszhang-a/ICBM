# ICBM
### Ice Cream Ball Maker

It makes overlapping icecream balls that fill up a mesh.

To use it, first install Pybullet and other utilities if going the `convex_then_clump` path:

```bash
pip3 install pybullet --upgrade --user
pip3 install Pillow
pip3 install trimesh
```

Then call the script, something like this (a bear.obj demo is included):

```bash
python3 convex_then_clump.py -i bear.obj -o result.csv -c parts.obj -v 1000000 -r 0.6
python3 convex_then_clump.py -i football_refined.obj -o result.csv -c parts.obj -v 1000000 -r 0.1
```

**This path is not recommended:**

``` bash
python3 sample_then_clump.py -i football.obj -o result.csv -n 10000 -b 3
```

