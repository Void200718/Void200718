from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "Void"
        self.age = "14"
        self.location = "Mars, With Elon Musk"
        self.work = "Developers"
        self.system = "Macbook Air"
        
    def skills(self):
        self.languages = {
            "main": ["Python"]
            "learning": ["Python"]
        }
        
        self.works = ["Antinuke bots", "Token gen", "Nuke Bots", "Multi token tools"]
        
    def social_media(self):
        self.discord = "Void.#5677"
        self.onlyfans = None
        
if __name__ = "__main__":
    readme = GithubReadme.create(Void)
