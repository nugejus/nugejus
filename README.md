```python
class About_Me:
  def __init__(self):
    self.Name = "Seungju Lee"
    self.Born_in = 1999
    self.Nationality = "South Korea"
    self.Served_In_Military = Military("Republic Of Korea Marine Corps" , from = 2018 , to = 2020)
    self.Graduated = Graduation("Lomonosov Moscow State University" , year = 2025)
    
    self.Studying = Education()
    
    self.Studying.since = 2017
    self.Studying.Division = "Computational Mathematics and Cybernetics"
    self.Studying.Department = "Algorithmic Languages"
    self.Studying.Department.Concentration = "Computational Linguistics"

    self.I_code = set("C++" , "Python")
    self.I_can_speak = set("Russain" , "Korean" , "English")
    self.I_love = set("NLP" , "AI", "Computer Vision", "ML")
    self.Hobby = set('Powerlifting')
    
    self.GirlFriend = True

  def Contact(self):
    print(" email : nugejus@naver.com ")
    print(" instagram : www.instagram.com/lift.yourlife ")
```
