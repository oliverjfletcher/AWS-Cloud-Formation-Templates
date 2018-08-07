<h1>Executive Summary & Architecture Rationale</h1>

This project was initiated as a learning excercise to further my knowledge of I.T and AWS best practices, standards, concepts, AWS Services and standard software & languages documented below.

The design decisions were made to demonstrate and document an automated deployment using AWS Cloudformation of n-tier architecture, by incorporating knowledge of the below best practices, standards, concepts, AWS Services and industry standard software & language documented below.


<h2>Resources</h2>
<ul style="list-style-type:disc">
<li><a href="https://aws.amazon.com/documentation/?nc2=h_ql_d&awsm=ql-5">AWS Documentation</a></li>
<li><a href="https://aws.amazon.com/architecture/well-architected/">AWS Well-Architected</a></li>
<li><a href="https://aws.amazon.com/whitepapers/">AWS Whitepapers</a></li>
<li><a href="https://aws.amazon.com/whitepapers/operational-checklists-for-aws/">AWS Operational Checklists</a></li>
</ul>
<h2>Architecture</h2>

<a href="https://s3-ap-southeast-2.amazonaws.com/oliverjamesfletcher/GitHub/AWS-Cloud-Formation-Templates-IAD.png">View Architecture</a>

<h3>Notes</h3>
<ol type="1">
<li>This is a on-going project, architecture is subject to change.</li>
<li>Network connection lines and data flow lines to be added to architecture.</li>
<li>Master CloudFormation template to be created.</li></ol>

</br>

<h2>Best Practices, Standards, Concepts, Software and Languages</h2>

<ul style="list-style-type:disc">
<h3><b>Standards, Concepts and Best Practices</b></h3>
<li>Distributed systems architecture</li>
<li>Loose coupling and Microservices</li>
<li>Elasticity and scalability</li>
<li>Security best practices</li>
<li>High Availibility</li>
<li>Self-healing techniques and fault-tolerant services</li>
<li>Disaster Recovery and fail-over strategies</li>
<li>Eventual consistency</li>
<li>Database and replication methodologies</li>
<li>System performance tuning</li></ul>

<ul style="list-style-type:disc">
<h4><b>DevOps</b></h4>
<li>Automated Deployments & Operations As Code (CloudFormation)</b></li>
<li>Continous Intergration, Continous Deployment and Blue/Green Deployments (S3, CodeCommit, CodeDeploy, CodePipeline, ECS)</li> <b> (R&D/WIP)</b></li>
<li>Containers (Docker/ECS)<b> (WIP)</b></li>
<li>Container Orchestration (Kubernetes/EKS) <b> (R&D/WIP)</b></li>
<li>Configuration Management (Puppet/OpsWorks)<b> (R&D/WIP)</b></li>
<li>Telemetery & Monitoring (CloudWatch & CloudTrail)<b> (WIP)</b></li></ul>

<ul style="list-style-type:disc">
<h4><b>Software & Languages</b></h4>
<li>PHP</li>
<li>SQL</li>
<li>HTML</li>
<li>CSS</li>
<li>Bash</li>
<li>YAML</li>
<li>Linux</li>
<li>Ngnix</li>
<li>MySQL</li>
<li>Memcached</li>
<li>Wordpress</li>
<li>Docker</li>
<li>Puppet</li></ul>

</br>

<h2>AWS Services</h2>

<h3><b>Networking & Content Delivery</b></h3>

<ul style="list-style-type:disc">
<li>Availability Zones</li>
<li>VPC</li>
<li>Subnets</li>
<li>Route Tables</li>
<li>NICs</li>
<li>Load Balancers</li>
<li>NAT Gateways</li>
<li>Internet Gateway</li>
<li>Elastic IPs</li>
<li>CloudFront</li>
<li>Route 53<b> (WIP)</b></li></ul>
<li>Security Groups</li></ul>

<h3><b>Compute</b></h3>
<ul style="list-style-type:disc">
<li>EC2</li>
<li>AMIs</li>
<li>Elastic Block Store</li>
<li>Auto Scaling Groups</li>
<li>Elastic Container Service <b> (WIP)</b></li></ul>

<h3><b>Storage</b></h3>
<ul style="list-style-type:disc">
<li>S3</li>
<li>Glacier</li></ul>

<h3><b>Database</b></h3>
<ul style="list-style-type:disc">
<li>RDS</li>
<li>ElastiCache</li></ul>

<h3><b>Security, Identity & Compliance</b></h3>
<ul style="list-style-type:disc">
<li>IAM</li></ul>
<li>Certificate Manager<b> (WIP)</b></li></ul>

<h3><b>Application Integration</b></h3>
<ul style="list-style-type:disc">
<li>Simple Notification Service <b>(WIP)</b></li></ul>

<h3><b>Developer Tools</b></h3>
<ul style="list-style-type:disc">
<li>CodeCommit</li>
<li>CodeBuild<b> (WIP)</b></li>
<li>CodePipeline<b> (WIP)</b></li></ul>
 
<h3><b>Management Tools</b></h3>
<ul style="list-style-type:disc">
<li>CloudWatch <b>(WIP)</b></li>
<li>CloudFormation</li>
<li>CloudTrail <b>(WIP)</b></li></ul>
