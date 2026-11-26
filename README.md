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
      mark.experience = [
        'Software Engineer                  @ Databricks',
        'Software Engineer Intern           @ Shopify',
        'Software Engineer Intern           @ Amazon',
        'Software Engineer Intern           @ Remitly',
        'Simulation Software Engineer Co-op @ Intel Corporation',
        'Software Engineer Intern           @ Schweitzer Engineering Laboratories (SEL)',
        'Teaching Assistant                 @ University of British Columbia',
        'Backend Software Developer Co-op   @ Safe Software',
        'Full-Stack Sotware Developer Co-op @ Government of Canada'
      ]
      mark.education = {
        'school': 'University of British Columbia',
        'major' : 'Computer Engineering',
        'GPA'   : '91.6% (3.9/4.0)',
        'awards': 'EGBC Achievement Award (top student in graduating class)'
      }
      mark.skills = {
        'languages'   : ['Java', 'Python', 'C/C++', 'Go', 'JavaScript/TypeScript', 'Ruby', 'HTML', 'CSS', 'SQL'],
        'technologies': ['AI Coding', 'Multi-Agent Workflows', 'AWS', 'Azure', 'GCP', 'Docker', 'Kubernetes']
      }
      mark.interests = {
        'software'     : ['Machine Learning', 'Application Development', 'Automation'],
        'non-technical': ['Snowboarding', 'Skiing', 'Hiking', 'Standup Comedy', 'Arabic']
      }
```

## Find me online 🌐
- Check out my [website](https://mark-mekhail.github.io/About/) 🔗
- Connect with me on [LinkedIn](https://www.linkedin.com/in/markmekhail/) 🤝
- I would direct you to my GitHub page but you're already here! 🤷‍♂️
