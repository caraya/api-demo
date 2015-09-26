third-party-API-demo

The idea is to build an app that wraps the Udacity API to do something similar to this:

```python
import json
import urllib
response = urllib.urlopen('https://udacity.com/public-api/v0/courses')
json_response = json.loads(response.read())
for course in json_response['courses']:
  print course['title']
  print course['homepage']
```

I'll be using a different layout than the one provided by PSK. 
