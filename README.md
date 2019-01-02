# SVRET: save returned results to your dataset

- Current version: `1.0.1 3apr2010`
- Jump to: [`updates`](#recent-updates) [`install`](#install) [`description`](#description) [`author`](#author)

-----------

## Updates:

* **April 3, 2010**
  - Added backwards compatibility for Stata 8.2

## Install:

Type `which svret` at the Stata prompt to determine which version you have installed. To install the most recent version of `svret`, copy/paste the following line of code:

```
net install svret, from("https://raw.githubusercontent.com/reifjulian/svret/master") replace
```

To install the version that was uploaded to SSC, copy/paste the following line of code:
```
ssc install svret, replace
```

These two versions are typically synced, but occasionally the SSC version may be slightly out of date.

## Description: 

`svret` is a [Stata](http://www.stata.com) command that replaces the dataset in memory with the scalars and macros stored in ```e()```, ```r()```, and ```s()```.

For more details, see the Stata help file included in this package.

## Author:

[Julian Reif](http://www.julianreif.com)
<br>University of Illinois
<br>jreif@illinois.edu
