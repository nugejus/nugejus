```python
class About_Me:
  def __init__(self):
    self.name = "Seungju Lee"
    self.born_in = 1999
    self.nationality = "South Korea"
    self.military = Military(
        "Republic Of Korea Marine Corps", 
        date = (2018, 2020)
    )

    self.education = Education()
    self.education.add_course(
        Graduation(
            level = 'Bachelor',
            university = "Lomonosov Moscow State University",
            division = "Computational Mathematics and Cybernetics",
            department = "Algorithmic Languages",
            concentration = "Computational Linguistics",
            year = 2025)
    )

    self.education.add_course(
        Graduation(
            level = 'Master',
            university = 'National Research University Higher School of Economics',
            division = 'Moscow Institute of Electronics and Mathematics',
            department = 'Applied Artificial Intelligence Models',
            year = 2027
        )
    )

    self.married = True
```
