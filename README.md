# cluster-agents-radius
###### Usage 
<pre>

Copy script to this location : /usr/lib/ocf/resource.d/heartbeat/ 
cp Radius /usr/lib/ocf/resource.d/heartbeat/
</pre>

###### Testing 
<pre>

bash -x /usr/lib/ocf/resource.d/heartbeat/Radius monitor
bash -x /usr/lib/ocf/resource.d/heartbeat/Radius
bash -x /usr/lib/ocf/resource.d/heartbeat/Radius validate-all
</pre>

###### Configure
<pre>

crm configure primitive radius ocf:heartbeat:Radius op monitor interval="30 
</pre>


