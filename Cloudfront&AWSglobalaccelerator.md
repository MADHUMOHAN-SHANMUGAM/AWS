# Cloudfront
- Content Delivery Network(CDN)
- Improves read performance, content is cached at the edge
- improves users experience
- 216 points of presence globally(edge location)
- DDoS protection (because worldwide), integration with shield, AWS Web Application Firewall
## Cloudfront Origin
- S3 bucket
  - For distributing files and caching them at the edge location
  - For uploading files to S3 through CloudFront
  - Secured using OAC(Origin Access Control)
- VPC Origin
  - for applications hosted in VPC private subnets
  - Application Load Balancer / Network Load Balancer / EC2 instances
- Custom Origin(HTTP)
  - S3 website (must first enable the bucket as a static S3 website)
  - Any public HTTP backend you want   
