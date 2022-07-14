from Github import GithubReadme

class Void:
    def __init__(self):
        self.name = "Void!"
        self.age = "14"
        self.location = "Mars, With Elon Musk"
        self.work = "Developer"
        self.system = "MacOS"

    def skills(self):
        self.languages = {
            "main": ["Python", "Node.js"],
            "learning": ["Node.js"]
        }

        self.works = ['Token Generator', 'hCaptcha Bypass', 'Chat Botter', 'Shill Tool', 'Token Manager', 'etc...']
    
    def social_media(self):
        self.discord = "- Storm?!♡PlayZ#0014"
        self.onlyfans = None


if __name__ == "__main__":
    readme = GithubReadme.create(Void)
