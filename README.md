# Relatively-Prime-Python

# Q4: Relatively Prime
Weight: 15%

Last update: 20 Sep, 7am

Let two positive integers be relatively prime (rp) if the only positive integer that divides both of them (without remainder) is 1. For example, 14 and 15 are rp, being commonly divisible by only 1, but 14 and 21 are not rp, because they are both divisible by 7.

A set of positive integers is mutually relatively prime (mrp) if the only positive integer that divides all of them is 1. For example the set {6, 12, 22, 27} is mrp.

A set of positive integers is pairwise relatively prime (prp) if every pair of integers in the set is rp. For example, the set {121, 122, 123} is prp. Note that every set that is prp is also mrp.

Given a set of at least two positive integers,

output prp if its is prp,

output mrp if it is mrp and not prp,

otherwise output ~.


Here a few sample runs.

```

Numbers: 6 12 22 27
mrp
Numbers: 121 122 123
prp
Numbers: 14 15
prp
Numbers: 21 14
~
Numbers: 12 27 6
~

```
