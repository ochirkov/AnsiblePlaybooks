I've dicide to share some my playbooks. It could be useful if somebody will try to find some examples during studying.

1. OpenLDAP cluster. This playbook setups cluster with masters and slaves servers with fresh&persist replication type. It also tunes client machines to authenticate linux users via this OpenLDAP. Be careful because of during replication password transfering like plain text. It should be secure with SASL or SSL. Up to you.
2. ElasticSearch cluster.
3. Logstash standalone server.
