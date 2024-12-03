# SOAP-mini

```
from soapmini import SOAP_mini
optimizerSOAPmini = SOAP_mini(model.parameters(), 
    lr=3e-3,
    betas=(0.95, 0.95),
    weight_decay=.01, 
    precondition_frequency=10
    )
```
