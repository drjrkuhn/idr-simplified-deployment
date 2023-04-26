# ome Ansible Roles and variables

## omero roles

See [ome/ansible-roles](https://github.com/ome/ansible-roles) for a list of OMERO ansible roles

REPOSITORY                          | ROLE                  | DESCRIPTION
---                                 |---                    |---
ansible-role-analysis-tools         | ome.analysis_tools    | Useful tools for running high-throughput analyses
ansible-role-anonymous-ftp          | ome.anonymous_ftp     | 
ansible-role-basedeps               | ome.basedeps
ansible-role-cadvisor               | ome.cadvisor          | cAdvisor container monitoring
ansible-role-celery-docker          |                       | Celery distributed processing with Docker (python task queues)
ansible-role-certbot                | 
ansible-role-cli-utils              | ome.cli_utils
ansible-role-debug-dumpallvars      | 
ansible-role-deploy-archive         | ome.deploy_archive
ansible-role-devspace               | 
ansible-role-docker                 | ome.docker
ansible-role-docker-slack-notifier  | 
ansible-role-docker-tools           | ome.docker_tools
ansible-role-fluentd                | ome.fluentd           | Install Fluentd log collector
ansible-role-haproxy                | ome.haproxy           | Installs HAProxy
ansible-role-hosts-populate         | ome.hosts_populate    | Populates /etc/hosts with static addresses for a list of hostgroups
ansible-role-ice                    | ome.ice
ansible-role-iptables-raw           | ome.iptables_raw      | Import the Iptables Raw library and make it available as a task (firewall)
ansible-role-java                   | ome.java
ansible-role-jekyll-build           | 
ansible-role-local-accounts         | ome.local_accounts    | Create or remove local user accounts
ansible-role-logrotate              | ome.logrotate
ansible-role-lvm-partition          | ome.lvm_partition
ansible-role-minio-s3-gateway       | ome.minio_s3_gateway
ansible-role-munin                  | 
ansible-role-munin-node             | 
ansible-role-mysql-backup           | 
ansible-role-network                | ome.network
ansible-role-network-cloud-interfaces| ome.network_cloud_interfaces
ansible-role-nfs-mount              | ome.nfs_mount         | Manage NFS mounts
ansible-role-nfs-share              | ome.nfs_share         | Manage NFS file shares
ansible-role-nginx                  | ome.nginx             | Install upstream Nginx
ansible-role-nginx-proxy            | ome.nginx_proxy       | Install Nginx for use as a front-end proxy
ansible-role-nginx-ssl-selfsigned   | 
ansible-role-omego                  | 
ansible-role-omero-common           | ome.omero_common
ansible-role-omero-logmonitor       | ome.omero_logmonitor
ansible-role-omero-prometheus-exporter| ome.omero_prometheus_exporter
ansible-role-omero-python-deps      |
ansible-role-omero-server           | ome.omero_server
ansible-role-omero-user             | ome.omero_user
ansible-role-omero-web              | ome.omero_web
ansible-role-omero-web-apps         |
ansible-role-omero-web-django-prometheus| ome.omero_web_django_prometheus
ansible-role-omero-web-runtime      | 
ansible-role-openstack-volume-storage| ome.openstack_volume_storage
ansible-role-postgresql             | ome.postgresql
ansible-role-postgresql-backup      | 
ansible-role-postgresql-client      | ome.postgresql_client
ansible-role-prometheus             | ome.prometheus        | Prometheus monitoring server, includes prometheus, alertmanager and blackbox-exporter
ansible-role-prometheus-jmx         | ome.prometheus_jmx
ansible-role-prometheus-node        | ome.prometheus_node
ansible-role-prometheus-postgres    | ome.prometheus_postgres
ansible-role-python-pydata          | ome.python_pydata
ansible-role-python-virtualenv-upstream|
ansible-role-python3-virtualenv     | ome.python3_virtualenv
ansible-role-reboot-server          | ome.reboot_server
ansible-role-redis                  | ome.redis             | Redis is an in-memory data store
ansible-role-rsync-server           | 
ansible-role-samba-client           | 
ansible-role-selinux-utils          | ome.selinux_utils
ansible-role-ssl-certificate        | ome.ssl_certificate
ansible-role-storage-volume-initialise| ome.storage_volume_initialise
ansible-role-sudoers                | ome.sudoers
ansible-role-system-monitor-agent   |
ansible-role-upgrade-distpackages   | ome.upgrade_distpackages  | Upgrades all packages installed with the distribution's package manager. 
ansible-role-versioncontrol-utils   | ome.versioncontrol_utils
infrastructure-extract-ansible-role | 
ome-ansible-molecule                | 
ansible-role-glusterfs-kube-config  | 

## IDR roles

See [IDR/repositories](https://github.com/orgs/IRD/repositories) for a list of IDR ansible roles

REPOSITORY                          | ROLE                  | DESCRIPTION
---                                 |---                    |---
ansible-role-openstack-idr-instance | idr.openstack_idr_instance
ansible-role-openstack-idr-instance-network| idr.openstack_idr_instance_network
ansible-role-openstack-idr-network  | idr.openstack_idr_network
ansible-role-openstack-idr-security-groups| idr.openstack_idr_security_groups
ansible-role-openstack-idr-keypairs | idr.openstack_idr_keypairs
ansible-role-redmine-tracker        | 
ansible-role-idr-jupyter            | 

