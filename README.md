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
  location = geomodels.PointField('Nyeri, Kenya')
  profile  = models.CharField('Python GIS web developer, GIS Data analyst')
  experience = models.PositiveIntegerField('2 + years')
  hobbies = models.CharField('coffee','cooking','travelling','poetry')
  
  def __str__(self):
    return self.name
    
    
 class Skills(models.Model):
  languages = models.CharField('python','javascript')
  operating_systems = models.CharField('linux')
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
  
  def __str__(self):
    return self.languages
    
    
class Social(models.Model):
  github = models.CharField('https://www.github.com/oderofrancis')
  twitter = models.CharField('https://twitter.com/_francisodero_')
  linkedin = models.CharField('www.linkedin.com/in/francis-odero-b69b6219')
  email = models.CharField('francisodero10@gmail.com')
  
  def __str__(self):
    return self.github	
,,,
