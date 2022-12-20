### Hi there 👋

Get to know more about me.
```python

from django.db import models
from django.db.models import Manager as GeoManager
from django.contrib.gis.db import models as geomodels
from phonenumber_field.modelfields import PhoneNumberField

# Create your models here.

class Portfolio(models.Model):
  name = models.CharField('Francis Odero')
  location = geomodels.PointField('Nairobi, Kenya')
  phone_number = models.PhoneNumberField(+254791061506)
  profile  = models.CharField('GIS web developer, GIS Data analyst','Google Earth Engine','Python')
  experience = models.PositiveIntegerField('3 + years')
  hobbies = models.CharField('coffee','cooking','travelling','poetry')
  
  def __str__(self):
    return self.name
    
    
 class Skills(models.Model):
  languages = models.CharField('python','javascript')
  operating_systems = models.CharField('linux - Ubuntu')
  web_frameworks = models.CharField('django')
  data_modelling_libraries =  models.CharField('pandas','geopandas','scikit-learn',
                                              'NumPy','SciPy','keras','TensorFlow'
                                              'rasterio'
                                              )
  data_visualization_libraries = models.CharField('matplotlib','plotly','seaborn')
  version_control = models.CharField('git')
  approaches = models.CharField('object oriented')
  database  = models.CharField('PostgreSQL','SQLite')
  database_extension = models.CharField('PostGIS')
  data_skills = models.CharFiels('Data analysis','data scrapping','data visualisation',
                                  'data prediction','data cleaning','spatial data'
                                  )
  
  def __str__(self):
    return self.languages
    
class softwares(models.Model):
   gis_analysis = models.CharField('ArcGIS','Quantum GIS','ENVI')
   spatial_analysis_cloud = models.CharField('Google Earth Engine')
   data_science = models.CharField('Microsoft Azure')
   text_editor = models.CharField('VS code','sublime Text','jupyter notebook)
   cloud_notebooks =  models.CharField('Datalore','Google Colab','Kaggle')
    
   def __str__(self):
     return self.gis_analysis
    
    
    
class Social(models.Model):
  github = models.CharField('https://www.github.com/oderofrancis')
  wemappers = models.CharField('https://wemappers.com/')
  twitter = models.CharField('https://twitter.com/_francisodero_')
  linkedin = models.CharField('www.linkedin.com/in/francis-odero-b69b6219')
  wakatime =models.CharField('https://wakatime.com/@Odero')
  email = models.CharField('francisodero10@gmail.com')
  
  def __str__(self):
    return self.github	
    
 ```
 
 ### Languages and Tools
 
 <img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/><img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" /><img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" /><img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg"/><img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/><img height=50 src=" https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png
"/><img height=50 src="[https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg](https://www.google.com/url?sa=i&url=https%3A%2F%2Fblog.jetbrains.com%2Fdatalore%2F2020%2F08%2F28%2Fnew-logo-and-domain-change-command-palette-rename-refactoring-and-other-small-fixes%2F&psig=AOvVaw05IkI1Yb7beud8Q6Lm-Ybp&ust=1671634241666000&source=images&cd=vfe&ved=0CA8QjRxqFwoTCJjA7vq4iPwCFQAAAAAdAAAAABAE)" />
 

### check out my Github stats

![Github stats](https://github-readme-stats.vercel.app/api?username=oderofrancis&theme=highcontrast&show_icons=true&count_private=true) ![Top Languages Card](https://github-readme-stats.vercel.app/api/top-langs/?username=oderofrancis&layout=compact)

<img src="https://github-readme-streak-stats.herokuapp.com/?user=zluvsand"/>

### Reach out to me on wakatime

[![wakatime](https://wakatime.com/badge/user/d5c6a673-b491-48c9-af56-061dd6c053b9.svg)](https://wakatime.com/@Odero)


- 💬 Ask me about Python, JavaScript, startups, Geo web development and bootstrapping
- 📫 How to reach me: on Twitter [@_francisodero_](https://twitter.com/_francisodero_) or [@WakaTime](https://wakatime.com/@Odero) on Wakatime

