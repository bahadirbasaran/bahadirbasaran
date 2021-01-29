<h2> Hi there, I'm Bahadır 👋 </h2>

```python
class AboutMe:
	def __init__(self):
		self.name = 	 "Bahadir"
		self.surname = 	 "Basaran"
		self.education = {
			"M.Sc.": "Politecnico di Torino - Computer Engineering",
			"B.Sc.": ["Ege University - Electrical & Electronics Engineering",
			          "Universitat Politecnica de Catalunya - Electronics & Telecommunication Engineering"]
		}
		self.lastEmployment = "Havelsan Inc. - Software Engineer"
		self.skills = {
			"Coding":       ["Python", 'C', "C++", "SQL", "JavaScript", "PHP"],
			"Framework": 	["PyTorch", "TensorFlow", "Keras", "Qt", "jQuery", "Selenium"],
			"Domain-based": ["ML Libraries", "O.S Fundamentals and Multi-threaded System Programming",
			                 "Embedded Programming on NXP FRDM-K64F", "Version Control", "Containerization",
			                 "Test-driven Development", "Linux Development Environments"]
		}
		
	def getSummary(self):
		print(" I am {}  {}!\n Studied at: {}\n Worked at: {}"
			.format(self.name, self.surname, self.education, self.lastEmployment))
		return
		
	def getSkills(self):
		return self.skills
		
```
