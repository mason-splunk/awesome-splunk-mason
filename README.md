# awesome-splunk-mason
Mason's curated list of awesome Splunk projects and resources

### Toc
- [awesome-splunk-mason](#awesome-splunk-mason)
        - [Toc](#toc)
    - [Community](#community)
    - [Cheat Sheets](#cheat-sheets)
    - [Data Ingestion](#data-ingestion)
    - [Monitoring Splunk](#monitoring-splunk)
    - [Open Source Utilities](#opensource-utils)
    - [Automation](#automation)
    - [CI & CD](#ci--cd)
    - [Splunk Conference](#splunk-conf)
    - [Splunkbase Addons](#splunkbase)
    
# Community
* [Slack](http://splk.it/slack) - Splunk's official community Slack team (splunk-usergroups)
* [Splunk Answers](https://answers.splunk.com/) - Splunk Answers Community Q&A

# Splunk Conference
* [Splunk Conference](https://conf.splunk.com/) - Splunk .conf website
* [Watch Splunk Conference Sessions](https://conf.splunk.com/watch/conf-online.html?#/) - Download slides and videos from previous Splunk .conf sessions

# Automation
* [Splunk Ansible](https://github.com/splunk/splunk-ansible/) - Splunk's official Ansible role (used by Splunk's official Docker image)
* [Splunk Docker](https://github.com/splunk/docker-splunk) - Splunk's official Docker image
* [Ansible Splunk Callback](https://docs.ansible.com/ansible/latest/plugins/callback/splunk.html) - Ansible callback for sending task and play logs to Splunk's HTTP Event Collector (HEC)
* [Chef Cookbook](https://github.com/cerner/cerner_splunk) - A Chef Cookbook for installing and configuring Splunk forwarders and servers

# Splunkbase Addons
*Visualizations*

*New Splunk Alert Actions*
* [HTTP Alert Action](https://splunkbase.splunk.com/app/4585/) - Send HTTP(S) requests [GET|POST] with custom headers, method, etc. with an option to ingest response to index
* [Syslog Mod Alert](https://splunkbase.splunk.com/app/4199/) - Send generic or CEF syslog events
* [Alert Manager](https://splunkbase.splunk.com/app/2665/)
* [Alert Schedule](https://splunkbase.splunk.com/app/3563/) - Create custom alert schedules using provided lookup files
* [SSH Alert Actions (for Linux 64-bit)](https://splunkbase.splunk.com/app/4398/) - Send search results over SFTP or execute shell commands on remote systems via SSH.
* [Sendresults](https://splunkbase.splunk.com/app/1794/) - Improved version of Splunk's email alert action that supports CSS, dynamic evaluation of email "to" and "subject" fields, multiple recipients, etc.

*Apps for Splunk Admins*
* [Lookup Editor](https://splunkbase.splunk.com/app/1724/) - Splunk Web App for Editing Lookup Files
* [DB Connect](https://splunkbase.splunk.com/app/2686/) - Splunk App for interacting with databases
* [Gemini KV Store Tools](https://splunkbase.splunk.com/app/3536/) - KV store backup/restore, delete key records, KV store alert action
* [TA-SyncKVStore](https://splunkbase.splunk.com/app/3519/) - Automatic synchronization of KV stores between separate Splunk instances, index local/remote KV stores as JSON using modular inputs
* [TrackMe](https://splunkbase.splunk.com/app/4621/) - Monitoring and alerting tool for availability of data sources within Splunk
* [License Monitor for Splunk](https://splunkbase.splunk.com/app/3521/) - Get insights about your actual license usage of your splunk enviroment
* [Unified Forwarder Monitoring App for Splunk](https://splunkbase.splunk.com/app/3805/) - Forwarder monitoring with metrics from DMC and DS combined
*Security Apps*
* [Security Essentials](https://splunkbase.splunk.com/app/3435/) - Splunk Security Essentials

# Open Source Utilities
* [Splunk Admin Alerts](https://github.com/gjanders/SplunkAdmins) - Splunk app with prepackaged alerts for monitoring and troubleshooting Splunk Enterprise deployments
* [KV Store Backup](https://github.com/georgestarcher/Splunk-backupkvstore) - Python script to backp up KVStore collections via the REST API
* [KV Store Synch](https://github.com/georgestarcher/TA-SyncKVStore) - Splunk TA to provide both modular inputs and a modular alert for synchronizing KVStore content across Splunk instances
* [HEC Modular Alert](https://github.com/georgestarcher/TA-Send_to_HEC) - Splunk Modular Alert to send search results to a Splunk HTTP Event Collector (HEC)
* [HEC Python Class](https://github.com/georgestarcher/Splunk-Class-httpevent) - Python class to submit events to Splunk HTTP Event Collector
* [Splunk Plugin for Hashicorp Vault](https://github.com/splunk/vault-plugin-splunk) - Hashicorp Vault plugin to securely manage Splunk admin accounts and password rotation
* [Docker Logging Driver](https://www.splunk.com/blog/2015/12/16/splunk-logging-driver-for-docker.html) - Docker Logging Driver for Splunk
