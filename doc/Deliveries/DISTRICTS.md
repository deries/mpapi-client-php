## DISTRICTS


#### Get list of districts
```
<?php 
...
use MPAPI\Services\Deliveries;
... 

// create an instance of deliveries service  
$deliveries = new Deliveries($mpapiClient);  

// get list of districts
$districtCodes = $deliveries->districts()->get();
```

##### See more:
> **/root/vendor/mallgroup/mpapi-client/Example/PartnerPickupPointExample.php**