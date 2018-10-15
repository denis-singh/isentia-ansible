---
Used for creatinf ECS cluster

Usage:
for creating a stack
`ansible-playbook -vvv -i localhost deploy_infra_app_stack.yml -e "app_version=na app_stack=ecs_cluster env=dev create_or_destroy=create"`
