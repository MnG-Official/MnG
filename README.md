```python
# MnG
class MnG():
    
  def __init__(self):
    self.name = "MnG"
    self.username = "MnG-Official"
    self.location = "?"
    self.lang = "tr"
    self.web = "in development"
    self.work = "Programmer, Developer, Professional Graphic Designer and 3D Designer"
    self.programs = ["Python","C/C++","Java","MySql","C#","HTML5","R","SQL","Algorithm"]
  
  def __str__(self):
    return self.name

if __name__ == '__main__':
    me = MnG()
