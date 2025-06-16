# Gnuplot

$y=sin(x)，tan^{-1}(x)$ のグラフを描く

```gnuplot {cmd=true output="html"}
set terminal svg

plot sin(x),atan(x)
set xlabel "x"
set ylabel "y"
set grid
set zeroaxis
set xrange [-10:10]
set yrange [-2:2]
plot sin(x) title "y = sin(x)", atan(x) title "y = atan(x)"
