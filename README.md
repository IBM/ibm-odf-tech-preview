# IBM ODF Technology Preview
The technology preview uses Openshift Data Foundation APIs to implement Capacity Management use cases.

The [YAML file](src/odf-techpreview-capacity-planning.rules.yaml) contains the Prometheus recording rules to produce 3 metrics:
* **odf_system_raw_capacity_rate_consumption** - which calculates the rate of consumption of the given storage array (in bytes)
* **odf_system_raw_capacity_time_until_exhaustion** - which calculates the elapsed time from now until the given storage array run out of capacity (in seconds)
* **odf_system_raw_capacity_used_forecast** - which forecast in the future of total used raw capacity of the system


 


