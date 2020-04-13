# Graph of my interests

An exercise for knowing myself better :)

With the help of [graphviz](https://www.graphviz.org/).

assign positions:
sfdp interests.gv > interests_ass.gv

render with [gvmap](https://www.mankier.com/1/gvmap):
gvmap -e interests_ass.gv | neato -Ecolor="#55555522" -n2 -Tpng > interests.png
