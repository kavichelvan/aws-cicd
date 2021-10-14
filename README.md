# aws-cicd
To test the CICD pipeline of aws

aws-code pipeline => https://ap-south-1.console.aws.amazon.com/codesuite/codepipeline/pipelines/cicd-pipeline-dev/view?region=ap-south-1
aws-bean-stalk => https://ap-south-1.console.aws.amazon.com/elasticbeanstalk/home?region=ap-south-1#/environment/dashboard?applicationName=beanstak-dev&environmentId=e-wc8g22b5gm
aws-ec2 => https://ap-south-1.console.aws.amazon.com/ec2autoscaling/home?region=ap-south-1#/details

site via beanstalk: http://beanstakdev-env.eba-psuvusgx.ap-south-1.elasticbeanstalk.com/
site via alb: http://awseb-awseb-ubqsbttq74h6-1122269763.ap-south-1.elb.amazonaws.com/

git-> AWS codebuild -> code deploy -> beanstalk -> create ASG -> create LB -> instance create
*access the site either via beanstalk url or alb*