streaming-server
================

For an Amazon deployment. The licode_config.js should set cloudProvider like this.

```javascript
config.cloudProvider.name = 'amazon';
//In Amazon Ec2 instances you can specify the zone host. By default is 'ec2.us-east-1a.amazonaws.com'
config.cloudProvider.host = ''// 'ec2.us-east-1.amazonaws.com';
config.cloudProvider.accessKey = 'XXXXXXXXX';
config.cloudProvider.secretAccessKey = 'XXXXXXXX';
```

For the access keys, you can add a user on the IAM aws console with the `AmazonEC2ReadOnlyAccess` permission
