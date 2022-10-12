```python
class About_Me:
  def __init__(self):
    self.Name = "Seungju Lee"
    self.Born_in = 1999
    self.Nationality = "South Korea"
    self.Served_In_Military = Military("Republic Of Korea Marine Corps" , from = 2018 , to = 2020)
    self.Graduated = Graduation("Ecologycal Economic Liseum No65 in Bishkek" , year = 2017)
    
    self.Studying=Education()
    
    self.Studying.since = 2017
    self.Studying.University = "Lomonosov Moscow State University"
    self.Studying.Division = "Computational Mathematics and Cybernetics"
    self.Studying.Department = "Algorithmic Languages"
    self.Studying.Department.Concentration = "Computational Linguistics"

    self.I_studied = set("Pascal" , "C" , "C++" , "Python" , "masm4.0")
    self.I_can_speak = set("Russain" , "Korean" , "English")
    self.Hobby = set('Powerlifting' , 'Photographing' , 'Poem writing')
    
    self.GirlFriend = False

  def Contact(self):
    print(" email : nugejus@naver.com ")
    print(" instagram : www.instagram.com/lift.yourlife ")
```
