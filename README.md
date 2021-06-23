# IBM ODF Technology Preview
The technology preview uses Openshift Data Foundation APIs to implement Capacity Management use cases.

The [YAML file](src/odf-techpreview-capacity-planning.rules.yaml) contains the Prometheus recording rules to produce 3 metrics:
* **odf_rate_consumption**
* **odf_time_until_exhaustion**
* **odf_used_capacity_forecast**
 


