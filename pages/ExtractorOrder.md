## ExtractorOrder

An extractor writes [instances](instance.md) to disk.

<br>
<br>
<br>

### Example

```python
import pyblish.api as pyblish

class MyExtractor(pyblish.InstancePlugin):
    """Extract to disk"""
    
    order = pyblish.ExtractorOrder

    def process(self, instance):
        ...
```

<div class="modified-date">{{ file.mtime }}</div>