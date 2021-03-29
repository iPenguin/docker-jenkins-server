This is a custom Jenkins image, it is designed with
configuration as code in mind. And includes the [Configuration as Code plugin](https://github.com/jenkinsci/configuration-as-code-plugin)

Things you can customize:
  - JENKINS_USER - The default admin user
  
  - JENKINS_PASS - The default admin password

  - JENKINS_PLUGINS - a list of (space separated) plugins to install in addition to configuration-as-code
    (ie. JENKINS_PLUGINS="blueocean:1.24.5 kubernetes:1.29.2 nodejs:1.4.0" )

You should provide a mount point for /var/jenkins_home if you want to persist the data for the server.

See also: 
  - https://www.digitalocean.com/community/tutorials/how-to-automate-jenkins-setup-with-docker-and-jenkins-configuration-as-code
  - https://www.popularowl.com/jenkins/automating-jenkins-install-docker-terraform/

