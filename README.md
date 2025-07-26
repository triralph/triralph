### Say Cheese 👋

```
variable "location" {
  type = map(any)
  default = {
    "onsite" = "Jupiter, Fl"
    "remote" = "US Based Remote, covering EST Time work schedule"
  }
}
```
## Certifications

*   AWS Certified SysOps Administrator - Associate
*   AWS Certified Cloud Practitioner


```
variable "cloud_providers" {
  type = map(any)
  default = {
    "aws" = "https://aws.amazon.com/"
  }
}
```
```
variable "ci_preferences" {
  type = map(any)
  default = {
    "github_actions"   = "https://github.com/features/actions"
    "aws_codepipeline" = "https://aws.amazon.com/codepipeline/"
    "aws_codebuild"    = "https://aws.amazon.com/codebuild/"
    "circleci"         = "https://circleci.com/"
    "bamboo"           = "https://www.atlassian.com/software/bamboo"
    "jenkins"          = "https://www.jenkins.io/"
  }
}
```
```
var "skills" {
  type = map(any)
  default = {
    "aws"            = [
      "cost_optimization",
      "ec2",
      "ecs",
      "alb",
      "dynamodb",
      "rds",
      "cloudformation",
      "route53",
      "s3",
      "iam",
      "vpc",
      "cloudwatch",
      "cloudtrail",
      "cloudfront",
      "elasticache",
      "elasticsearch",
      "codepipeline",
      "codebuild",
      "codecommit",
      "codedeploy",
      "codeartifact"
    ]
    "virtualization" = [
      "vmware",
      "citrix",
      "xenserver"
    ]
    "storage" = [
      "emc",
      "dell"
    ]
    "cisco" = [
      "firewalls",
      "routers",
      "switches",
      "ucs"
    ]
    "monitoring" = [
      "nagios",
      "pagerduty",
      "datadog",
      "newrelic",
      "honeybadger",
      "monyog",
      "splunk"
    ]
    "tools" = [
      "cloudformation",
      "docker",
      "terraform",
      "vscode",
      "CoPilot"
    ]
  }
}
```
