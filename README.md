# Aws-Ec2-Tutorial
<h4>AWS-ECS</h4>
1.ECS is one of the orchestor service available on AWS.</br>
<img width="300" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/2497cd97-a3e0-402d-acbd-26e639302057">
<h4>Docker</h4>
1.We cannot scale the docker using docker-compose, because we need to manually need to set the docker-compse on aws to deploy out 
<img width="300" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/d029598f-ec40-4310-9d0e-d31dca11d140"> <br
                                                                                                                                              
1.AWS ECS has two launch types <br/>
A) EC2 launch type (Need to plan for the deployment and upgrades) <br/>
B) ECS FARGATE (This is s serverless service where the infra is taken care by AWS) <br/>

<img width="300" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/d557dc7d-4f3b-423c-95d8-39c43b8ea5df"> 
<img width="300" height ='200' alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/d3d22026-d57d-4d63-8a53-236e5c7b7467"><br/>

<b>Fargate (ECS-Fargate)</b> <br/>
<img width="600" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/24c5cbda-c8bb-4358-b2ee-da6a5b6bed79"> <br/>
<b>Task Definition file</b> <br/>
1. Task definition file is used to define settings for each container <br/>
<img width="400" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/cb66796e-cecd-4fda-aee8-ac206869e810">
<img width="580" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/7f6de821-a7ad-40f8-9bbe-2bf2d117efef">

<h4>ECS-Service</h4><br/>
ECS service automatically takes care of launching the container.
<img width="590" alt="image" src="https://github.com/vamshikrish007/Aws-Ec2-Tutorial/assets/17798810/2516b6fe-6d7b-44c7-a74b-3fdc35fa10a8">




