# Class-for-Conversion-
The program has a class named Converter which converts values entered in metre to different other units
class Converter:
  def __init__(self,metre):
    self.metre=metre
  def centimetre(self):
    c=self.metre/100
    return c
  def millimetre(self):
    m=self.metre/1000
    return m
  def decimetre (self):
    d=self.metre/10
    return d
  def feet(self):
    f=3.28*self.metre
    return f
  def inches(self):
    i=39.36*self.metre
    return i
C = Converter(10)
print(C.centimetre())
print(C.millimetre())
print(C.decimetre())
print(C.feet())
print(C.inches())
