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
   text_editor = models.CharField('VS code','sublime Text','jupyter notebook')
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
 
 ## Languages and Tools
 
 <img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg"/> <img height=50 src="https://github.com/devicons/devicon/blob/master/icons/javascript/javascript-plain.svg" /> <img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg"/> <img height=50 src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg"/> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/vscode/vscode-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/django/django-plain.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/bootstrap/bootstrap-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/jetbrains/jetbrains-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/numpy/numpy-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/pandas/pandas-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/postgresql/postgresql-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/twitter/twitter-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/jupyter/jupyter-original.svg" /> <img height=50 
src="https://github.com/devicons/devicon/blob/master/icons/linux/linux-original.svg" /> <img height=50 
src="https://assets.website-files.com/61b3a482c8531b1b59d1d777/61f33c7e8911db2b4b7c0222_Dash.png" /> <img height=50 
src="https://corevaluetech.com/wp-content/uploads/2023/03/leaflet.png" /> <img height=50 
src="https://autogis-site.readthedocs.io/en/2019/_images/OSM_logo.png" /><img height=50 
src="https://upload.wikimedia.org/wikipedia/commons/9/91/QGIS_logo_new.svg" /> <img height=50 
src="https://geopandas.org/en/stable/_images/geopandas_logo.png" /> <img height=50 
src="https://earthengine.google.com/static/images/earth-engine-logo.png" /> <img height=50 
src="https://geoplaza.vu.nl/cms/wp-content/uploads/2021/09/Logo_ArcMap_transparent-768x372.png" />


# stats

<a href="https://github.com/oderofrancis/github-readme-stats">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=oderofrancis&repo=github-readme-stats" />
</a>
<a href="https://github.com/oderofrancis/convoychat">
  <img align="center" src="https://github-readme-stats.vercel.app/api/pin/?username=oderofrancis&repo=convoychat" />
</a>

## Github stats
[![Anurag's GitHub stats-Dark](https://github-readme-stats.vercel.app/api?username=oderofrancis&show_icons=true&theme=dark#gh-dark-mode-only)](https://github.com/anuraghazra/github-readme-stats#gh-dark-mode-only)  [![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=anuraghazra&layout=donut&theme=dark#gh-dark-mode-only)](https://github.com/oderofrancis/github-readme-stats)

## Total Working Hours on wakatime

[![wakatime](https://wakatime.com/badge/user/d5c6a673-b491-48c9-af56-061dd6c053b9.svg)](https://wakatime.com/@Odero)

[![Harlok's wakatime stats](https://github-readme-stats.vercel.app/api/wakatime?username=@Odero)](https://github.com/anuraghazra/github-readme-stats)

## Graph

[![My Github activity graph](https://github-readme-activity-graph.cyclic.app/graph?username=oderofrancis&theme=github-compact&hide_border=true)](https://github.com/oderofrancis)



## Reach Me At:

- 💬 Ask me about Python, JavaScript, Geo web development and bootstrapping
- 📫 How to reach me: on Twitter [@_francisodero_](https://twitter.com/_francisodero_) or [@WakaTime](https://wakatime.com/@Odero) on Wakatime

