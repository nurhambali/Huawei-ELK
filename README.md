# Huawei-ELK 
<!-- TITLE: Configuration File -->

Send log Network Device Huawei to **ELK**
Support device Network Hauwei :

|Device  | Product |
|----------|:----:|
|**Firewall**| **USG6300**|
|**Router**| **AR2200**|
|**Core Switch**| **S12700**|
|**Cloud Engine**| **CE12800**|

## Configure on All Device Huawei :

[huawei] info-center source default channel 2 

[huawei]info-center timestamp log none 

[huawei] info-center timestamp trap none

[huawei] info-center timestamp debugging none

[huawei]  info-center loghost 192.168.137.1 *(IP server elk)*

## Configure Server ELK 

| Required | Version|
|----------|:----:|
|**Elasticsearch**|**6.5.4**|
|**Logstash**|**6.5.4**|
|**Kibana**|**6.5.4**|

link install [ELK] ()
