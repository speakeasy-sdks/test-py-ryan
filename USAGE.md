<!-- Start SDK Example Usage [usage] -->
```python
import swagger_petstore
from swagger_petstore.models import shared

s = swagger_petstore.SwaggerPetstore()

req = shared.Pet(
    id=596804,
    name='<value>',
)

res = s.pets.create_pets(req)

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage [usage] -->