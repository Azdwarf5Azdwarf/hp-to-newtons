# 1 hp is not 745.7 newtons

A common statement floats around:

> 1 horsepower (hp) is approximately equal to **745.7 newtons**

It is not.

## What is actually true

1 mechanical horsepower = **745.7 watts**

And by definition:

1 watt = 1 newton-metre per second  (N·m/s)

So:

**1 hp = 745.7 N·m/s**

That is a rate of doing work (power), not a force.

## Specific examples of the slip and the correct form

### The seed claim (this discourse)
The statement that opened this repository:

> 1 horsepower (hp) is approximately equal to **745.7 newtons** when considering the conversion in terms of force and distance over time (work rate).

This is the exact pattern: the correct numerical value is kept, the units are reduced from power to force, and a parenthetical attempt is made to justify it with “work rate.”

### Intermediate form that enables the error
A common teaching explanation is:

> 1 hp is the power of applying a force of roughly 746 newtons over a distance of 1 metre in 1 second.

This is dimensionally correct *only while the velocity (1 m/s) remains attached*. Once someone omits “over 1 metre in 1 second,” the number is left floating as a force. See, for example, the conversion walk-through in this video explanation (transcript):

- https://www.youtube.com/watch?v=S23AOeGP_Os (around the 746 N × 1 m / 1 s step)

### Authoritative correct statements

- Wikipedia (Horsepower):
  > one imperial horsepower … is about 745.7 watts
  https://en.wikipedia.org/wiki/Horsepower

- Unit converters that keep the units honest:
  - 1 hp = 745.6998715823 newton meter/second  
    https://www.unitconverters.net/power/horsepower-to-newton-meter-second.htm
  - 1 hp = 745.699921 N.m/s  
    https://www.endmemo.com/power/horsepowernewtonmeter_second.html

### Why the number is so sticky
745.7 appears everywhere because it is the precise SI equivalent of the mechanical definition (550 ft·lbf/s). The number itself is not the problem; the unit that gets silently deleted is.

## Why the confusion arises

People sometimes drop the “metres per second” and treat the number as if it were force.  
The number is familiar, the units get quietly stripped, and the sentence still *sounds* precise.

Dimensional analysis catches it immediately:
- Force has dimensions M L T⁻²
- Power has dimensions M L² T⁻³

They are not the same thing.

## Starting the discourse

This repository exists to keep the distinction clear and to explore the surrounding questions in public.

Possible threads:
- How often does this exact unit slip appear in engineering documents, textbooks, homework solutions, or AI outputs?
- What other common power/force confusions exist?
- How do different definitions of horsepower (mechanical, metric, electrical) affect the conversion?
- Practical examples where treating power as force would produce nonsense results.

Feel free to open issues, post corrections, or add more examples.

The goal is simple: keep the units honest.
