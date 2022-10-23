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
  phone_number = models.PhoneNumberField(+254791061506)
  profile  = models.CharField('GIS web developer, GIS Data analyst','Google Earth Engine','Python')
  experience = models.PositiveIntegerField('3 + years')
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
  wemappers = models.CharField('https://wemappers.com/')
  twitter = models.CharField('https://twitter.com/_francisodero_')
  linkedin = models.CharField('www.linkedin.com/in/francis-odero-b69b6219')
  wakatime =models.CharField('https://wakatime.com/@Odero')
  email = models.CharField('francisodero10@gmail.com')
  
  def __str__(self):
    return self.github	
    
 ```

![Github stats](https://github-readme-stats.vercel.app/api?username=oderofrancis&theme=highcontrast&show_icons=true&count_private=true) ![Top Languages Card](https://github-readme-stats.vercel.app/api/top-langs/?username=oderofrancis&layout=compact)


[![wakatime](https://wakatime.com/badge/user/d5c6a673-b491-48c9-af56-061dd6c053b9.svg)](https://wakatime.com/@Odero)
[![twitter](https://img.shields.io/twitter/follow/wakatime?label=followers&logo=twitter&color=%23007ec6&style=plastic)](https://twitter.com/WakaTime)
[![github](https://img.shields.io/github/followers/alanhamlett?logo=github&style=plastic)](https://github.com/alanhamlett?tab=followers)

- 🔭 I’m currently working on [[https://wakatime.com](https://wakatime.com/@Odero)](https://wakatime.com)
- 💬 Ask me about Go, Python, TypeScript, startups, and bootstrapping
- 📫 How to reach me: [@alanhamlett](https://twitter.com/alanhamlett) or [@WakaTime](https://twitter.com/wakatime) on Twitter

Add the [@WakaTime](https://github.com/wakatime) badge ([![wakatime](https://wakatime.com/badge/user/66b6796d-eb84-4bb9-b9d2-8dc882f4c6ac.svg)](https://wakatime.com/@66b6796d-eb84-4bb9-b9d2-8dc882f4c6ac)) to your GitHub profile by creating a GitHub repo named `username/username` then copy the snippet from your [public WakaTime profile](https://wakatime.com/me).

