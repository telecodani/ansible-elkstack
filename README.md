# Install ELK Stack on Centos 7.5
Install Elasticsearch, Logstash, and Kibana (Elastic Stack) on CentOS 7, following this steps:
* 1.install_and_configure_elasticsearch.yml
* 2.install_and_configure_kibana.yml
* 3.install_and_configure_logstash.yml
* 4.install_and_configure_filebeat.yml

Once all playbook are completed you can access at server_ip:81. And with the user kibanaadmin with the same password. You can add new users on /etc/nginx/htpasswd.users with:

echo "new_user_name_here:`openssl passwd -apr1`" | sudo tee -a /etc/nginx/htpasswd.users
