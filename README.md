### Hi there, I am Leo 👋

Applied AI Postgraduate Student at George Brown College<br>
Graduated from Hong Kong University of Science and Technology


```python
from dataclasses import dataclass
import coding_language as cl

@dataclass
class Person:
  name: str
  pronouns: tuple[str]
  roles: list[str]
  spoken_langs: list[str]
  coding_langs: list[str]

  def say_hi(self):
    print(f"HI! My name is {self.name} and I am now a {self.roles[-1]}")

me = Person(
         name="Leo Wong",
         pronouns=("He", "him", "his"),
         roles=["Software Developer", "IT Consultant", "Computer Engineering Student",
                "Fullstack Software Engineer", "Applied AI Postgraduate Student"],
         spoken_langs=["yue_HK", "zh_TW", "en_US", "ja_JP"],
         coding_langs=[cl.Python, cl.R, cl.C, cl.CPP, cl.Java, cl.Javascript, cl.Typescript]
     )

me.say_hi()

```

## Working on
- LLM Deep Learning with [Keras](https://github.com/keras-team/keras) & [PyTorch](https://github.com/pytorch/pytorch)
- Statistical analysis with [PowerBI](https://learn.microsoft.com/en-us/power-bi/) & [Tableau](https://community.tableau.com/s/)
  
## Learning
- Deep Learning on Tabular, Textual, and Graphical data
- ML model hosting on Cloud Platforms

## Technologies & Tools 🔧

![](https://img.shields.io/badge/Ubuntu-E95420?style=flat&logo=ubuntu&logoColor=white)
![](https://img.shields.io/badge/Windows-0078D6?style=flat&logo=windows&logoColor=white)
![](https://img.shields.io/badge/VS_Code-2C2B30?style=flat&logo=visual-studio-code&logoColor=3CA5EA)
![](https://img.shields.io/badge/Vim-C6C6C6?style=flat&logo=vim&logoColor=019331)
![](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![](https://img.shields.io/badge/JavaScript-323330?style=flat&logo=javascript&logoColor=F7DF1E)
![](https://img.shields.io/badge/TypeScript-ffffff?flat&logo=typescript&logoColor=3178C6)
![](https://img.shields.io/badge/C-00599C?style=flat&logo=c&logoColor=white)
![](https://img.shields.io/badge/C%2B%2B-00599C?style=flat&logo=c%2B%2B&logoColor=white)
![](https://img.shields.io/badge/Shell_Script-121011?style=flat&logo=gnu-bash&logoColor=white)
![](https://img.shields.io/badge/Vue.js-35495E?flat&logo=vue.js&logoColor=4FC08D)
![](https://img.shields.io/badge/React.js-222222?flat&logo=react&logoColor=21DAFB)
![](https://img.shields.io/badge/SQL-4479A1?flat&logo=mysql&logoColor=ffffff)
![](https://img.shields.io/badge/Firebase-0393D9?flat&logo=firebase)
![](https://img.shields.io/badge/GraphQL-ffffff?flat&logo=firebase&logoColor=d932a2)
![](https://img.shields.io/badge/Socket.io-ffffff?flat&logo=socketdotio&logoColor=000000)
![](https://img.shields.io/badge/scikit_learn-ffffff?flat&logo=scikitlearn)
![](https://img.shields.io/badge/Keras-ffffff?flat&logo=keras&logoColor=D00000)

<!--
![](https://img.shields.io/badge/Pytorch-ffffff?flat&logo=pytorch&logoColor=EE4C2C)
-->


## Contacts 📱

[![](https://img.shields.io/badge/Gmail-D14836?style=flat&logo=gmail&logoColor=white)](mailto:leo62227@gmail.com)
[![](https://img.shields.io/badge/GitHub-100000?style=flat&logo=github&logoColor=white)](https://github.com/LeoLYW12138)

<!--
**LeoLYW12138/LeoLYW12138** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
