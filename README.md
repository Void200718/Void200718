
-----
```python
from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "Void!"
        self.age = "15"
        self.location = "Mars, With Elon Musk"
        self.work = "Developer"
        self.system = "Macbook air"

    def skills(self):
        self.languages = {
            "main": ["Python", "JavaScript"],
            "learning": ["discord.py", "discord.js"]
        }

        self.works = ['Spotify follwer Generator', 'Moderation bots', 'Token Manager', 'etc...']
    
    def social_media(self):
        self.discord = "Storm '#5677"
        self.onlyfans = None


if __name__ == "__main__":
    readme = GithubReadme.create(Void)
```
-----
