Conversion process for Faulty Metrics (from pdf)

python Txt2LaTeX.py "FaultyMetrics.txt" ""

In Sublime Text, do an re search for "^\d.*\n" to locate footnote text to place in endnotes area.

Generate html w/pandoc:
pandoc FaultyMetrics.tex -o FaultyMetrics.html


Generate md w/pandoc:
pandoc FaultyMetrics.tex -o FaultyMetrics.md


