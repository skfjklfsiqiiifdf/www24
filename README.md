```bash
pip install pixivpy3 --upgrade
```

```python
from pixivpy3 import *

api = AppPixivAPI()

artwork_id = 4242
user_id = 2424

# get artwork
json_result = api.illust_detail(artwork_id)

# get user
json_result = api.user_detail(user_id)
```