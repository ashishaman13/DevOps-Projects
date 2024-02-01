In this excercise we are optimizing the cost of cloud.

The steps :

1) We will create a lamda fucntions that identify those EBS snapshot which are stale. With stale I mean, those snapshot which are not in use, corresponding volumes does not exist nor the ec2.
2) For snapshot which are 30 days old, Send a notification (email) with the Excel attached to it containing Snapshot details.
3) For snapshot which are 60days old, delete it.
