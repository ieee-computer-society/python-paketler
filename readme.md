# Popüler Python Paketleri
 Bu derste python için tavsiye edeceğim paketlerden bahsedeceğiz.

## Ipython

Kurulum:
```
pip install ipython
```

Örnek:
```bash
ipython
```

## PPrint (Pretty printer)
Json terminalde daha iyi görmek için kullanılan bir default kütüphane
Örnek
```
from pprint import pprint
pprint(~data~)
```
More : [PPrint](https://docs.python.org/3/library/pprint.html)

## Requests

Kurulum:
```
pip install requests
```
Örnek:
```python3
import requests
from pprint import pprint
r = requests.get('https://www.instagram.com/tlghnzn/?__a=1')
pprint(r.json())
```
More : [Requests](http://www.python-requests.org/)

## Scrapy

Kurulum:
```
pip install scrapy
```

Örnek : [Code Example](http://mherman.org/blog/2012/11/05/scraping-web-pages-with-scrapy/#.Wew7ZhOCy9Y)

More : [Scrapy](https://scrapy.org/)

## WxPython

Kurulum:
```
pip install wxPython
```

Örnek : [Code](https://wxpython.org/pages/overview/#hello-world)

More: [WxPython](https://wxpython.org)

## Pillow

Kurulum:
```
pip install Pillow
```

Örnek:
```
from PIL import Image
im = Image.open("resim.jpg")
im.show()
box = (100, 100, 400, 400)
region = im.crop(box)
region.show()
```

## BeautifulSoup

More: [BeautifulSoup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)

## Twisted

More: [Twisted](http://twistedmatrix.com/trac/)

## Numpy - Scipy

```
pip install numpy
```

Örnek:
```
import numpy as np
a = np.arange(15).reshape(3, 5)
a
a.shape
a.dtype.name
a.size
b = np.array([2,3,4])
c = np.zeros( (3,4) )
```

More: [Numpy](http://www.numpy.org/)
More: [Scipy](https://www.scipy.org/)

## Matplotlib

Kurulum:
```
pip install matplotlib
```

Örnek:
```
import numpy as np
import matplotlib
import matplotlib.pyplot as plt

# Fixing random state for reproducibility
np.random.seed(19680801)


matplotlib.rcParams['axes.unicode_minus'] = False
fig, ax = plt.subplots()
ax.plot(10*np.random.randn(100), 10*np.random.randn(100), 'o')
ax.set_title('Using hyphen instead of Unicode minus')
plt.show()
```

## PyGame

More = [Pygame](http://www.pygame.org/wiki/GettingStarted)

## Python HTTP SERVER

```bash
python -m http.server 8080
```