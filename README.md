# devops-challenge

## Welcome

Welcome to Audibene's DevOps challenge :)

Please try to complete the below 2 taks. Please send us a link to your public github repo containing the solution code or alternatively give us your GitHub username so we can grant you permissions to this repository.

## Taks 1

### Situation

The company you´re working for operates servers on AWS that could not easily be re-created from scratch because they contain data that is stored locally. For example, think about it like an old-fashioned Jenkins, a Spunk or a Jira server.

### Requirements

Please describe, how you would handle automated backups and restoring the latest backup in case of emergency. Do not provide any code here. Just describe what tools or AWS services you would like to use and how the whole process should work.

## Taks 2

### Situation

The company wants to deploy some static landing pages to AWS. One for US, one for Asia and one for Europe. S3 and CloudFront should be used for this. Because developers will deploy new versions very often the origin S3 buckets should be located in the appropriate regions to minimize latentency when fetching objects from origins.

### Requirements

Please provide some terraform code (best version 12) that creates the 3 buckets in the regions and 3 Cloudfront distributions each pointing to one of the buckets as an origin. Please keep in mind that your company might want to add new pages in other regions or additional ones in the regions that are already used at a later time.
