# ECS-CFN-Combo
A CloudFormation script for building an ECS environment with selectable inclusion of a number of extra features.
Basically trying to keep all the useful bits that I use often in one place.

Selectable features

*debug
*cloudwatch instance metrics - http://docs.aws.amazon.com/AmazonCloudWatch/latest/DeveloperGuide/mon-scripts.html
*cloudwatch logs - http://docs.aws.amazon.com/AmazonECS/latest/developerguide/using_cloudwatch_logs.html
*cloudwatch container logs - https://docs.docker.com/engine/admin/logging/awslogs/
*cloudwatch docker storage metrics - https://aws.amazon.com/blogs/compute/optimizing-disk-usage-on-amazon-ecs/
*efs - https://github.com/awslabs/amazon-ecs-amazon-efs
*ami versions
*task scaling - http://docs.aws.amazon.com/AmazonECS/latest/developerguide/service-auto-scaling.html
*task iam roles - http://docs.aws.amazon.com/AmazonECS/latest/developerguide/task-iam-roles.html
*service discovery - https://github.com/awslabs/ecs-refarch-service-discovery https://github.com/awslabs/service-discovery-ecs-dns https://github.com/awslabs/service-discovery-ecs-consul
*Example Apps
*ecr
*task kite - https://github.com/awslabs/ecs-task-kite
*SSM - http://docs.aws.amazon.com/AmazonECS/latest/developerguide/ec2-run-command.html
*Private subnet
*cloudtrail?
