# Ansible RSyslog

This is an [Ansible](http://www.ansible.com/) role to install, configure and ensure sure rsyslog is running.
Feedback, bug-reports, requests are welcomed and can be done via [github issues](https://github.com/New-Edge-Engineering/ansible-rsyslog/issues).

## Role Variables

The following variables can be overridden:

 * `rsyslog_sender_services`: A dictionary of services with lists of logfiles and associated tag, defaults to an empty dictionary.
 * `rsyslog_sender_logstash_host`: The IP Address or domain name of the [Logstash](https://www.elastic.co/products/logstash) server. Triggers the creation of the
   logstash configuration when defined.

## Dependencies
None known.

## License
Licensed under the MIT License. See the LICENSE file for details.