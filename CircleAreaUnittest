# My-J18P1
Advanced Practice Project

#!/usr/bin/env python
import unittest
import circle
from circle import circle_area
from math import pi

class TestCircleArea(unittest.TestCase):
    def test_area(self):
        #test areas when radius is >=0
        self.assertAlmostEqual(circle_area(1), pi)
        self.assertAlmostEqual(circle_area(0), 0)
        self.assertAlmostEqual(circle_area(2.1), pi*2.1**2)

    def test_values(self):
        #Make sure value erros are raised when necessary
        self.assertRaises(ValueError, circle_area, -2)

    def test_types(self):
        #make sure type errors are raised when necessary
        self.assertRaises(TypeError, circle_area, 3+5j)
        self.assertRaises(TypeError, circle_area, True)
        self.assertRaises(TypeError, circle_area, "radius")
