# cluster-agents-radius
###### Usage 
Copy script to this location : /usr/lib/ocf/resource.d/heartbeat/ 
###### Testing 
bash -x /usr/lib/ocf/resource.d/heartbeat/Radius monitor
bash -x /usr/lib/ocf/resource.d/heartbeat/Radius
bash -x /usr/lib/ocf/resource.d/heartbeat/Radius validate-all
###### Configure
crm configure primitive radius ocf:heartbeat:Radius op monitor interval="30 


