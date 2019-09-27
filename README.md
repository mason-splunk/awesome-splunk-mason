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

*Apps for Splunk Admins*
* [Lookup Editor](https://splunkbase.splunk.com/app/1724/) - Splunk Web App for Editing Lookup Files
* [DB Connect](https://splunkbase.splunk.com/app/2686/) - Splunk App for interacting with databases
* [Gemini KV Store Tools](https://splunkbase.splunk.com/app/3536/) - KV store backup/restore, delete key records, KV store alert action

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
