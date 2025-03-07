### Hi there 👋

Get to know more about me.
```python

#pip install EDMT

import edmt
edmt.init()


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
  experience = models.PositiveIntegerField('6 + Years')
  hobbies = models.CharField('coffee','cooking','travelling','poetry')
  
  def __str__(self):
    return self.name

class Conservation(models.Model):
  app = models.CharField('EarthRanger')
  analysis = geomodels.PointField('Ecoscope')
  data_management = edmt.__version__
  automation = models.PhoneNumberField('Python Scripts')
  script_management  = models.CharField('Google colaboratory','Google Drive')
  config = models.PositiveIntegerField('Json')
  config_managemnt = models.CharField('Dropbox')
  
  def __str__(self):
    return self.app
    
    
 class Skills(models.Model):
  languages = models.CharField('python','javascript')
  operating_systems = models.CharField('linux - Ubuntu, Linux Lite')
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
  linkedin = models.CharField('linkedin.com/in/francis-odero-b69b62191')
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
src="https://autogis-site.readthedocs.io/en/2019/_images/OSM_logo.png" /><img height=50 
src="https://upload.wikimedia.org/wikipedia/commons/9/91/QGIS_logo_new.svg" /> <img height=50 
src="https://geopandas.org/en/stable/_images/geopandas_logo.png" /> <img height=50 
src="https://earthengine.google.com/static/images/earth-engine-logo.png" /> <img height=50 
src="https://geoplaza.vu.nl/cms/wp-content/uploads/2021/09/Logo_ArcMap_transparent-768x372.png" />


<!--  ## Github stats 

[![Your Name's GitHub stats](https://github-readme-stats.vercel.app/api?username=oderofrancis&show_icons=true&theme=dark)](https://github.com/anuraghazra/github-readme-stats) -->


<!-- ## Graph

[![My Github activity graph](https://github-readme-activity-graph.cyclic.app/graph?username=oderofrancis&theme=github-compact&hide_border=true)](https://github.com/oderofrancis) -->



## Data moves in mysterious ways... but spatial data? Now that’s a whole coordinate system of fun!

