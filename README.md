<div align="center">

[![LinkedIn](https://img.shields.io/badge/Yousef%20Hany-LinkedIn-0077b5)](https://www.linkedin.com/in/yousef-hany-dev/)
[![GitHub](https://img.shields.io/badge/youseifMahmoud-GitHub-2b3137)](https://github.com/youseifMahmoud/)
[![Download Resume](https://img.shields.io/badge/Download-CV-6b3237)](https://github.com/youseifMahmoud/youseifMahmoud/blob/main/Yousef%20Hani%20Muhamed.pdf)
[![Download CV](https://img.shields.io/badge/Download-CV%202-2b6cb0)](https://github.com/youseifMahmoud/youseifMahmoud/blob/main/Yousef_Hany_Muhamad_cv.pdf)
[![Email](https://img.shields.io/badge/Email-youusefhani634@gmail.com-red)](mailto:youusefhani634@gmail.com)

</div>

<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=800&size=25&duration=3000&pause=503&center=true&vCenter=true&width=1000&lines=Hello+Everyone;My+name+is+Yousef+Hany.;I+am+a+Software+Developer.;and+my+interests+include+%5BDjango%2C+PostgreSQL%2C+Python%5D" alt="Typing SVG" /></a>

```python
from rest_framework.decorators import api_view
from rest_framework.response import Response

@api_view(['POST'])
def introduce_yourself(request):
    name = request.data.get('name', 'Yousef Hany')
    occupation = request.data.get('occupation', 'Fullstack Web Developer')
    skills = request.data.get('skills', [
        'HTML', 'CSS', 'JavaScript',
        'Python', 'Django', 'PostgreSQL', 'SQL'
    ])

    # رسالة جديدة منسقة بوضوح
    introduction = (
        f"### 👋 Hi there!\n\n"
        f"My name is **{name}**.\n\n"
        f"💼 I work as a *{occupation}*.\n\n"
        f"### 🔧 Skills I use:\n"
        + "".join([f"- {skill}\n" for skill in skills])
    )

    return Response({'introduction': introduction})

```

<div align="center">
  <br>
  <p align="center"><b>Visitors Count</b></p>
  <p align="center">
    <img align="center" src="https://komarev.com/ghpvc/?username=faresemad" alt="GitHub Profile Views Counter">
  </p>
  <br>
</div>


### 🤖Most Used Languages:
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=faresemad&theme=slateorange)](https://github.com/anuraghazra/github-readme-stats)

<hr>

## ⚡ Fun fact
- “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.” — Martin Fowler
