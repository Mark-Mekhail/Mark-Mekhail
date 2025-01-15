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
        'GPA'   : '91.6% (3.9/4.0)'
      }
      mark.experience = [
        'Software Engineer Intern           @ Remitly',
        'Simulation Software Engineer Co-op @ Intel Corporation',
        'Software Engineer Intern           @ Schweitzer Engineering Laboratories (SEL)',
        'Teaching Assistant                 @ University of British Columbia',
        'Backend Software Developer Co-op   @ Safe Software',
        'Full-Stack Sotware Developer Co-op @ Government of Canada'
      ]
      mark.skills = {
        'programming languages' : ['Java', 'Python', 'C/C++', 'Go', 'JavaScript', 'TypeScript', 'HTML', 'CSS', 'SQL', 'SystemVerilog'],
        'frameworks/technologies': ['Node.js', 'React', 'Express', 'Jest', 'Spring Boot']
        'tools'     : ['Git', 'Docker', 'AWS', 'Jenkins', 'GitHub Actions', 'Cypress', 'Linux', 'Jira']
      }
      mark.interests = {
        'software'     : ['Machine Learning', 'Cybersecurity', 'Application Development', 'Automation'],
        'non-technical': ['Snowboarding', 'Skiing', 'Hiking', 'Standup Comedy', 'Skin Care', 'Arabic']
      }
```

## GitHub Stats 🤓
Being a good software engineer isn't easy. To succeed, you need to commit! Apparently I've done that hundreds of times 🚀.

[![Mark's GitHub stats](https://github-readme-stats.vercel.app/api?username=Mark-Mekhail&hide=contribs,stars&show_icons=true&hide_rank=true&include_all_commits=true)](https://github.com/anuraghazra/github-readme-stats)

## Find me online 🌐
- Check out my [website](https://mark-mekhail.github.io/About/) 🔗
- Connect with me on [LinkedIn](https://www.linkedin.com/in/markmekhail/) 🤝
- I would direct you to my GitHub page but you're already here! 🤷‍♂️
