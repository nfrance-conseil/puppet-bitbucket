##2014-11-15 - Release 1.1.2
###Summary
- rename parameter manage_service to service_manage
- Fix Issue #30 Add params for stash::service
##2014-10-26 - Release 1.1.1
###Summary
- Replace mkrakowitzer-deploy with nanliu-staging as the default to deploy the install file.
- Add new parameter: jvm_permgen, defaults to 256m.
- Add $stop_stash parameter, This is usefull for when service is managed outside of the module,
such as in a cluster.
- Add test for upgrades
- Update the README file to comply with puppetlabs standards
  - https://docs.puppetlabs.com/puppet/latest/reference/modules_documentation.html
  - https://docs.puppetlabs.com/puppet/latest/reference/READMEtemplate.markdown

####Bugfixes
- None