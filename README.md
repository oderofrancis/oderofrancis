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
 
### Languages and Tools:

[<img align="left" alt="Visual Studio Code" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/visual-studio-code/visual-studio-code.png" />][ytplaylist]
[<img align="left" alt="Javascript" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png" />]
[<img align="left" alt="Python" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png" />]
[<img align="left" alt="Git Control" width="26px" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png" />]
[<img align="left" alt="Github" width="26px" src="https://user-images.githubusercontent.com/3369400/139448065-39a229ba-4b06-434b-bc67-616e2ed80c8f.png" />]
[<img align="left" alt="Mysql" width="26px" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/mysql/mysql-original.svg" />]

### check out my Github stats

![Github stats](https://github-readme-stats.vercel.app/api?username=oderofrancis&theme=highcontrast&show_icons=true&count_private=true) ![Top Languages Card](https://github-readme-stats.vercel.app/api/top-langs/?username=oderofrancis&layout=compact)

### Reach out to me on wakatime

[![wakatime](https://wakatime.com/badge/user/d5c6a673-b491-48c9-af56-061dd6c053b9.svg)](https://wakatime.com/@Odero)


- 💬 Ask me about Python, JavaScript, startups, Geo web development and bootstrapping
- 📫 How to reach me: on Twitter [@_francisodero_](https://twitter.com/_francisodero_) or [@WakaTime](https://wakatime.com/@Odero) on Wakatime

