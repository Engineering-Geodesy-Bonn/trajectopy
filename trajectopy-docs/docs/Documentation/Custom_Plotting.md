# Custom Matplotlib Plotting

You can customize the style of the plots by placing a `custom.mplstyle` file in the current working directory. The default style that Trajectopy uses is:

```python
figure.figsize: 8, 6
figure.facecolor: white

font.size: 12
font.family: serif
font.serif: Times New Roman, DejaVu Serif

axes.facecolor: white
axes.edgecolor: black
axes.linewidth: 0.8
axes.labelsize: 14
axes.titlesize: 14
axes.grid: True
axes.axisbelow: True
axes.prop_cycle: cycler("color", ["#1E88E5", "#FFC107", "#004D40", "#D81B60", "#2bd2bb", "#a3bbf1", "#3c41fd", "#cc5510", "#3b0732", "#88122b", "#bccb70", "#dc9c54"])

grid.color: gray
grid.alpha: 0.3
grid.linewidth: 0.5
axes.grid.which: major

xtick.labelsize: 12
ytick.labelsize: 12
xtick.direction: in
ytick.direction: in
xtick.major.size: 5
ytick.major.size: 5

lines.linewidth: 1.5
lines.linestyle: -
lines.marker: .
lines.markersize: 6

legend.frameon: True
legend.facecolor: white
legend.edgecolor: black
legend.loc: best
legend.framealpha: 1

savefig.dpi: 600
savefig.format: pdf
savefig.bbox: tight
```

