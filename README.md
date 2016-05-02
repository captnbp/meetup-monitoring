# meetup-monitoring
Ansible playbook used for Paris Monitoring #4 Meetup 

## Usage
```bash
ansible-playbook -e "port=80" -e "datadog_api_key=YOURKEY" -e "mail=YOURMAIL" -e "host=localhost" meetup-monitoring.yml
```
