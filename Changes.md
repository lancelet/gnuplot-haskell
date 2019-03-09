# Change log for the `gnuplot` Haskell binding

## 0.5.5:

 * `Gnuplot.Utility.quote` bugfix:
   Do not escape printable non-ASCII characters
   because gnuplot has no universal escaping support for Unicode codepoints.
