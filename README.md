## Hey, I'm Mark 👋👨‍💻

```python
  class Mark:
    _mark = None

    # Until cloning is possible, there can only be a single Mark 😉
    def __new__(cls):
      if cls._mark is None:
        cls._mark = super().__new__(cls)
        print("Mark is born! It doesn't look like we're in the 2000's, though 🤔")
      return cls._mark

    def __init__(mark):
      mark.education = {
        'school': 'University of British Columbia',
        'major' : 'Computer Engineering',
        'GPA'   : '91.6%'
      }
      mark.experience = [
        'Simulation Softwar Engineer Co-op  @ Intel Corporation',
        'Software Engineer Intern           @ Schweitzer Engineering Laboratories (SEL)',
        'Teaching Assistant                 @ University of British Columbia',
        'Backend Software Develoepr Co-op   @ Safe Software',
        'Full-Stack Sotware Developer Co-op @ Government of Canada'
      ]
      mark.skills = {
        'languages' : ['Java', 'Python', 'C/C++', 'JavaScript', 'HTML/CSS', 'SQL', 'SystemVerilog'],
        'frameworks': ['React', 'Express', 'Spring Boot']
        'tools'     : ['Git', 'Jenkins', 'Linux', 'Jira', 'Docker', 'AWS']
      }
      mark.interests = {
        'software'     : ['Machine Learning', 'Cybersecurity', 'Application Development', 'Automation'],
        'non-technical': ['Snowboarding', 'Skiing', 'Hiking', 'Standup Comedy', 'Skin Care', 'Arabic']
      }
```

## Some GitHub Stats
Although I like to think I'm a 🌟 star developer 🌟 it seems like I haven't earned very many yet. If you like any of my work, do show some love with a star ⭐!

[![Mark's GitHub stats](https://github-readme-stats.vercel.app/api?username=Mark-Mekhail&hide=contribs&show_icons=true)](https://github.com/anuraghazra/github-readme-stats)

## Find me online 🌐
- Check out my [website](https://mark-mekhail.github.io/About-Mark/) 🔗
- Connect with me on [LinkedIn](https://www.linkedin.com/in/markmekhail/) 🤝
- I would usually also list my GitHub page, but you're already here! 🤷‍♂️
