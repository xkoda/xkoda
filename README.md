"""
Sithija Sankalpa (xkoda/Koda) - AI & Python Developer Profile
"""
import random

class DeveloperProfile:
    def __init__(self):
        self.name = "Sithija Sankalpa"
        self.username = "xkoda"
        self.title = "Self-taught AI & Python Developer"
        self.skills = {
            'languages': ['Python', 'JavaScript', 'HTML/CSS'],
            'ai_tech': ['Machine Learning', 'Neural Networks', 'NLP'],
            'tools': ['TensorFlow', 'PyTorch', 'OpenCV', 'Pandas']
        }
        self.links = {
            'blog': 'https://soleaai.blogspot.com',
            'twitter': 'https://x.com/xsithij',
            'email': 'sankalpakoda@gmail.com'
        }
    
    def generate_banner(self):
        ai_art = """
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣀⣤⣴⣶⣾⣿⣿⣿⣿⣷⣶⣦⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⣠⣴⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣦⣄⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⢀⣴⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣦⡀⠀⠀⠀⠀
        �⠀⣠⣾⣿⣿⣿⣿⣿⣿⣿⣿⣿⡿⠿⠛⠛⠛⠛⠛⠿⠿⣿⣿⣿⣿⣿⣿⣿⣿⣷⣄⠀⠀⠀
        ⠀⣾⣿⣿⣿⣿⣿⣿⠿⠛⠉⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠛⠿⣿⣿⣿⣿⣿⣷⠀⠀
        ⢸⣿⣿⣿⣿⠟⠁⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠻⣿⣿⣿⣿⡇⠀
        ⣿⣿⣿⡿⠃⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠘⢿⣿⣿⣿⠀
        ⣿⣿⡟⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⢻⣿⣿⠀
        ⢹⣿⣧⡀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣸⣿⡏⠀
        ⠀⢻⣿⣿⣄⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⣠⣴⣿⣿⠏⠀⠀
        ⠀⠀⠻⣿⣿⣷⣤⣀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⢀⣀⣤⣾⣿⣿⠟⠁⠀⠀⠀
        ⠀⠀⠀⠈⠻⣿⣿⣿⣿⣶⣦⣤⣄⣀⣀⣀⣀⣀⣀⣀⣠⣤⣶⣿⣿⣿⣿⠿⠋⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠉⠛⠿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⣿⠿⠛⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        ⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠈⠉⠉⠉⠉⠉⠉⠉⠉⠉⠉⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀⠀
        """
        return ai_art
    
    def generate_readme(self):
        banner = self.generate_banner()
        
        readme = f"""
# {self.name} ({self.username})  
{banner}
### {self.title}

Passionate about creating intelligent systems and efficient code.  
Exploring the intersection of AI and software development.

## 🔧 Technologies & Skills

### Programming Languages  
{" ".join([f"`{lang}`" for lang in self.skills['languages']])}

### AI/ML Expertise  
{" ".join([f"`{tech}`" for tech in self.skills['ai_tech']])}

### Tools & Frameworks  
{" ".join([f"`{tool}`" for tool in self.skills['tools']])}

## 🌐 Connect With Me

📝 Blog: [{self.links['blog']}]({self.links['blog']})  
🐦 Twitter: [{self.links['twitter']}]({self.links['twitter']})  
📧 Email: {self.links['email']}

## 🚀 Current Projects

- Developing AI solutions at Solea AI  
- Building Python tools for machine learning workflows  
- Writing about AI concepts on my blog

```python
# Sample AI code
def neural_network(inputs):
    layers = [Dense(64, activation='relu'), 
              Dense(32, activation='relu'),
              Dense(10, activation='softmax')]
    for layer in layers:
        inputs = layer(inputs)
    return inputs