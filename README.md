<div align="center"> 
    <h2>Hi, I'm <span style="color:#4888B7">Bayu Taufiqurrahman</span>&nbsp;<img src="https://c.tenor.com/CiObPlNJeDwAAAAi/langrisser.gif" style="width:40px"/> </h2>
</div>

---

<div style="text-align:center;"> 
    <img src="https://img.shields.io/badge/github-masibay-%235D275D?style=for-the-badge&logo=github&logoColor=white&labelColor=%23181717" alt="GitHub">&nbsp;
    <img src="https://img.shields.io/badge/linkedin-Bayu%20Taufiq-%234888B7?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=%23181717" alt="LinkedIn">
</div>

```python
import json

def about():
    BayuTaufiq = {
        'codename': 'masibay',
        'ask_me_about': ['Data Ops', 'Machine Learning', 'FE', 'Tech'],
        'technologies': {
            'de': {
               'code': 'Python',
               'database': ['PostgreSQL', 'SQL Server', 'Big Query'],
               'tools': ['spark', 'airflow', 'kafka', 'talend'],
            },
            'ml': {
                'code': ['Python', 'C++'],
                'database': ['csv', 'json'],
                'tools': ['pandas', 'spark', 'sklearn', 'tensorflow', 'huggingface'],
            },
            'fe': {
                'code': ['HTML', 'CSS', 'Javascript'],
                'framework': ['solid', 'react'],
            }
        },
        'current focus': 'Data Engineer',
        'current_learning': 'Java',
        'hobbies': ['UI Design', 'Gacha Game', 'Anime Watch'],
    }
    return BayuTaufiq

about_me = about()


print(json.dumps(about_me, indent=4))
```