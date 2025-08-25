<div align="center">

[![LinkedIn](https://img.shields.io/badge/Yousef%20Hany-LinkedIn-0077b5)](https://www.linkedin.com/in/yousef-hany-dev/)
[![GitHub](https://img.shields.io/badge/youseifMahmoud-GitHub-2b3137)](https://github.com/youseifMahmoud/)
[![Download CV](https://img.shields.io/badge/Download-CV-6b3237)](https://github.com/youseifMahmoud/youseifMahmoud/blob/main/Yousef%20Hani%20Muhamed.pdf)
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

    # نص منسق على سطرين
    introduction = (
        f"Hello, my name is {name}. I am a {occupation}.\n"
        f"My skills include: {', '.join(skills)}."
    )

    return Response({'introduction': introduction})

```

<div align="center"> <br><p align="centre"><b>Visitors Count</b></p> <p align="center"><img align="center" src="https://profile-counter.glitch.me/{faresemad}/count.svg" /></p> <br> </div> <hr> <h3 align="left">Languages and Tools:</h3> <p align="left"> <a href="https://www.djangoproject.com/" target="_blank" rel="noreferrer"> <img src="https://cdn.worldvectorlogo.com/logos/django.svg" alt="django" width="40" height="40"/> </a> <a href="https://www.postgresql.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/postgresql/postgresql-original-wordmark.svg" alt="postgresql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> <a href="https://www.linux.org/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/linux/linux-original.svg" alt="linux" width="40" height="40"/> </a> <a href="https://www.w3.org/html/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="html5" width="40" height="40"/> </a> <a href="https://www.javascript.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg" alt="javascript" width="40" height="40"/> </a> </p> <hr> 

### 🤖Most Used Languages:
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=faresemad&theme=slateorange)](https://github.com/anuraghazra/github-readme-stats)

<hr>

## ⚡ Fun fact
- “Any fool can write code that a computer can understand. Good programmers write code that humans can understand.” — Martin Fowler
