# This is a test file demonstrating markdown.

## This is a Level 2 Header

### This is a Level 3 Header

#### This is a Level 4 Header

This is plain text.  There is nothing special about it.  You simply start typing your desired text.

## These are examples of lists:

### The Seven Continents of the World

- North America
- South America
- Antarctica
- Europe
- Africa
- Asia
- Australia

### The Continents Ranked by Size
1. Asia (approx. 44.6 million sq km)
1. Africa (approx. 30.4 million sq km)
1. North America (approx. 24.7 million sq km)
1. South America (approx. 17.8 million sq km)
1. Antarctica (approx. 14.2 million sq km)
1. Europe (approx. 10.2 million sq km)
1. Australia (approx. 7.7 million sq km)

## This is an example of an embedded link

Check out [leafmap](https://leafmap.org/) for more information.

## This is an example of an image

![leafmap logo](https://raw.githubusercontent.com/opengeos/leafmap/master/docs/assets/logo_rect.png)


## This is a sample python code block

```python
import requests

def get_hardiness_zone(zip_code):
    url = f"https://phzmapi.org/{zip_code}.json"
    response = requests.get(url)
    if response.status_code == 200:
        data = response.json()
        return data['zone']
    return None
```

