# gitlab-cicd-test
EYALATOX_GITHUB

```
aws/
  components/           
    vpc/
      variables.tf    
      main.tf       
      outputs.tf       
    <component>/
    ...
  organizations/
    eyalatox/	
      infrastructure/
        main.tf	
        configdb/	
          main.tf	
        <account>/
      <organizational-unit>/
  terraform/     
<cloud>/
...
```

avoid putting functions or services here!
documentDb, rds, ecr
visualStudio, AzureDevOps, hockeyApp, logAnalytics - securityCenter - batch
storage and others s3 buckets

A `cloud` is a cloud provider, such as AWS (`aws`) Azure (`azure`)

The following directories are still used by teams.
`modules`, `templates`, `us-east-1`, `us-west-1`
