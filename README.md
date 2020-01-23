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

[huawei] `info-center source default channel 2 `

[huawei] `info-center timestamp log none` 

[huawei] `info-center timestamp trap none`

[huawei] `info-center timestamp debugging none`

[huawei]  `info-center loghost 192.168.137.1` *(IP server elk)*

## Specification ELK Server 

| Required | Version|
|----------|:----:|
|**Elasticsearch**|**7.5.0**|
|**Logstash**|**7.5.0**|
|**Kibana**|**7.5.0**|

## Plugins Logstash 

bin/logstash-plugin install **Name Plugins**

|Plugin Name | Version
|------------|:---|
|**logstash-input-file**|latest| 
|**logstash-input-udp**|latest|
|**logstash-input-syslog**|latest|
|**logstash-filter-drop**|latest|
|**logstash-filter-translate**|latest|
|**logstash-filter-grok**|latest|
|**logstash-output-elasticsearch**|latest|
|***logstash-output-file***|latest|

