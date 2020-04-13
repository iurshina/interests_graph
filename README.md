# Graph of my interests

An exercise for knowing myself better :)

With the help of [graphviz](https://www.graphviz.org/).

assign positions:
sfdp interests.gv > interests_ass.gv

render:
gvmap -e interests_ass.gv | neato -Ecolor="#55555522" -n2 -Tpng > interests.png

Example used as a reference: https://graphviz.gitlab.io/_pages/Gallery/undirected/gd_1994_2007.html
