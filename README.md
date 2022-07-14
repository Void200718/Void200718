from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "Void!"
        self.age = "14"
        self.location = "Mars, With Elon Musk"
        self.work = "Developer"
        self.system = "MacOs"

    def skills(self):
        self.languages = {
            "main": ["Python", "Node.js"],
            "learning": ["Python", "Node.js"]
        }

        self.works = ['Token Generator', 'Hosting', 'Music Bot', 'Token Tool', 'Antinuke bot src', 'etc...']
    
    def social_media(self):
        self.discord = "- Storm?!♡PlayZ#0014"
        self.onlyfans = None


if __name__ == "__main__":
    readme = GithubReadme.create(Void)
