# Euclidean Distance

Euclidean distance is the straight line distance between two points in the Euclidean space.

This distance can be calculated using Pythagorean theorem by connecting the two points as the [hypotenuse](https://en.wikipedia.org/wiki/Hypotenuse#/media/File:Hypotenuse.svg) of a right angle triangle – getting the length of the two other sides ([catheti](https://en.wikipedia.org/wiki/Cathetus)) – then adding the two sides squared.

In a right angle triangle, the sides opposite of the hypotenuse is known as the <u>catheti</u>.

###### Code - Work In Progress

```python
def ecludian_distance(c1, c2):
	hypothenuse = c12 + c22
	distance = math.sqrt(hypothenuse)
	print distance
```

*— TODO c1 and c2 are the lengths of the catheti - learn the formula to get the lengths given the xy coordinates of two points.*

- http://codepad.org/ttkNdqWI
- https://www.khanacademy.org/math/basic-geo/basic-geometry-pythagorean-theorem/pythagorean-theorem-distance/v/example-finding-distance-with-pythagorean-theorem

------

###### Reason:

A couple weekends ago I came across [this](https://youtu.be/imD_XsEV-90) video that made mention of euclidean distance — it sounded vaguely famillair, as I did not pay much attention to maths in secondary school.

Last year my interest in machine learning peaked and I realised in order to understand the topic more I needed to understand maths.