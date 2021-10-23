Given Ellipse equation x^2 + y^2 + Slant*xy = r^2 its parametric representation bridges Algebra, Geomety and Complex Number.
The constraint -2 < Slant < 2 applies.
          a = Major Axis/2
          b = Minor Axis/2
          c = Distance between two foci/2 = a^2 - b^2
          d = Distance from a point to two foci
          e = Eccentricity
          r = Radius of Conic Section
                Slant
          a/b

x = c1 * Cos(x) + s1 *  Sin(x)
y = s2 * sin(x)

Given Slant, a/b, Eccentricity we can generate c1, s1 and s2 is here. Ellipse symmetrical to x, y axes with Major axis in x-y line is generated.  Similarly Ellipse symmetrical to x, -y axes is generated when Salnt is positive.
1. Slant to Eclipse
2. a / b to Eclipse
3. Eccentricity to Eclipse

Generated constants:
1-Slant/2 = r = c1
a/b * Slant/2 = s1
a/b         = s2 

Some identities:
a^2 + b^2 = 2 *  (a / b)
	Abs(Slant)/2 = c / (a^2 + b^2)
Abs(Slant) = c / (a / b)^2
Distance from a point on ellipse to two foci = 2 * a

