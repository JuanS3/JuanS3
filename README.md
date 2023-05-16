# Hello
<div align="center">
  <img src="about.png" alt="" width="200"/>
</div>


```
╔══════════════════════════════════════════════════════════════════════════╗
║                                                                          ║
║ Hello to my mini README; first of all, my golden rule is                 ║
║ "Be the change that you want to see in the world".                       ║
║                                                                          ║
║ I am passionate about the sea of data science and artificial             ║
║ intelligence; in fact, I am taking a Master's degree in                  ║
║ Artificial Intelligence at Universidad Internacional de la Rioja (UNIR). ║
║                                                                          ║
║ In addition, I've worked as Business Intelligence Consultant,            ║
║ Python Developer, Data Engineering and Data Developer.                   ║
║                                                                          ║
╚══════════════════════════════════════════════════════════════════════════╝
```
<br/>
<br/>

*Visit my [live-cv](https://juans3.github.io) for more information*

<br/>
<br/>


```python
class SebastianMartinez:

  def __init__(self):
    self.name = "Juan Sebastian Martinez"
    self.education = "Master's degree in Artificial Intelligence"
    self.university = "Universidad Internacional de la Rioja (UNIR)"
    self.location = "Bogotá D.C, Colombia"

    self.interests = ["DS", "AI", "ML", "DL", "CV", "NLP", "BI", "DE"]
    self.hobbies = ["Reading", "Writing", "Music", "Movies", "Series", "Video Games", "Sports"]
    self.languages = ["Spanish", "English"]

    self.technologies = {
      "programming languages":[
        "Python", "R", "JavaScript", "Java", "SQL - NoSQL", "C", "C++", "Go", "Bash - Batch"
      ],
      "tools": [
        "PowerBI", "QlikSense", "Docker", "KNIME", "IBN Cognos - Data Stage", "GNU/Linux"
      ],
      "libraries - frameworks": [
        "Pandas", "Numpy", "Matplotlib", "Seaborn", "Scipy", "Scikit-Learn/Image", "TensorFlow", "Keras", "PySpark", "Django", "TKinter"
      ]
    }

    self.contact = {
      "telegram": "https://t.me/JuanS3",
      "linkedin": "https://www.linkedin.com/in/jsebastian-martinez",
      "github": "https://juans3.github.io"
    }

  def main_programming_language(self):
    return self.technologies["programming languages"][0]

  def __str__(self):
    return f"Hello, my name is {self.name} and I am a {self.education} at {self.university}.\nI am passionate about the sea of data science and artificial intelligence.\nIn addition, I've worked as Business Intelligence Consultant, Python Developer and Data Engineering.\n\nVisit my {self.contact['github']} for more information.\n\n{self.technologies}"

if __name__ == "__main__":
  print(SebastianMartinez())

```

<br/>
<br/>

<!-- GitHub stats In two columns -->
<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=JuanS3&layout=compact" alt="" width="400"/>
  <img src="https://github-readme-stats.vercel.app/api?username=JuanS3&show_icons=true" alt="" width="400"/>
</div>
