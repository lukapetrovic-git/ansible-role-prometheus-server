# Ansible role: Prometheus Server
Simple Ansible Prometheus role

# Requirements
No special requirements, note that this role requires root access, so either run with a global become: yes, or invoke the role in your playbook.

# Role Variables
Variables for this role are listed below:
```
prometheus_name: [your Prometheus domain name]
prometheus_url: [Prometheus download URL]
prometheus_checksum:
htpasswd_user:
htpasswd_pw:
```
