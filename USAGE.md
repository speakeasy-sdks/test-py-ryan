<!-- Start SDK Example Usage -->


```python
import swagger_petstore


s = swagger_petstore.SwaggerPetstore()


res = s.pets.create_pets()

if res.status_code == 200:
    # handle response
    pass
```
<!-- End SDK Example Usage -->