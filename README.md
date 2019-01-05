# Ansible-Artifactory
Playbook is used to download the Artifactory and Install. 

This playbook installs artifactory at /opt location .

##Playbook variables

We have defined below mentioned variables for our playbook.

    artifactory_version: artifactory-pro-6.5.9
    artifactory_dir: /opt/{{ artifactory_version }}
    artifactory_zip_file: artifactory-pro-6.5.9.zip
    artifactory_zip_url: http://dl.bintray.com/content/jfrog/artifactory/jfrog-"{{ artifactory_zip_file }}"
