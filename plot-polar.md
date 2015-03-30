# Using polar coordinates
- The following example is from `gnuplot` [user's manual](www.gnuplot.info/docs_4.6/gnuplot.pdf) (p. 146).

```
set polar
plot t*sin(t)
set trange [-2*pi:2*pi]
set rrange [0:3]
plot t*sin(t)
```

- To unset polar:
	```
	unset polar

	show polar
	```
