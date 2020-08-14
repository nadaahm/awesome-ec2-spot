# Awesome EC2 Spot
A curated list of awesome AWS EC2 Spot related tools, open source repos, guides, blogs, and other resources.


## Contributing

Contributions are welcome!

Let's get srtarted!

## Contents

- [Hands-on](#hands-on)
- Workloads
    - [General](#--general)
    - [Data Analytics](#--data-analytics)
    - [Containers](#--containers)
        - [Amazon EKS and Kubernetes](#amazon-eks-and-kubernetes)
        - [Amazon ECS and Fargate Spot](#amazon-ecs-and-fargate-spot)
    - [Web Applications](#--web-applications)
    - [CI/CD](#--cicd)
    - [Machine Learning](#--machine-learning)
    - [Autonomous Vehicle](#--autonomous-vehicle)
- [Tools](#tools)
- [Tutorials](#tutorials)
- [Customer Stories](#customer-stories)
- [News and Announcements](#news-and-announcements)


### Hands-on
* https://ec2spotworkshops.com – 90mins use-case focused self-paced workshops.
* https://github.com/awslabs/ec2-spot-labs – Sample code snippets to get started with Spot.

## Workloads

### - General

* [Best practices for handling EC2 Spot Instance interruptions](https://aws.amazon.com/blogs/compute/best-practices-for-handling-ec2-spot-instance-interruptions/)
* [Introducing Instance Refresh for EC2 Auto Scaling](https://aws.amazon.com/blogs/compute/introducing-instance-refresh-for-ec2-auto-scaling/)

### - Data Analytics
* [Best practices for running Apache Spark applications using Amazon EC2 Spot Instances with Amazon EMR](https://aws.amazon.com/blogs/big-data/best-practices-for-running-apache-spark-applications-using-amazon-ec2-spot-instances-with-amazon-emr/)
* [Best practices for running Spark applications using Spot instances on Amazon EMR](https://pages.awscloud.com/Best-Practices-for-Running-Spark-Applications-Using-Spot-Instances-on-EMR_2019_0820-CMP_OD.html?&trk=ep_card-el_a131L0000057bPMQAY&trkCampaign=NA-FY19-AWS-DIGMKT-WEBINAR-SERIES-August_2019_0820-CMP&sc_channel=el&sc_campaign=pac_2018-2019_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)

### - Containers

#### Amazon EKS and Kubernetes

* [Article] [Building for Cost optimization and Resilience for EKS with Spot Instances](https://aws.amazon.com/blogs/compute/cost-optimization-and-resilience-eks-with-spot-instances/)
* [Video] [Save costs running Kubernetes clusters with EC2 Spot instances](https://pages.awscloud.com/Save-Costs-Running-Kubernetes-Clusters-with-EC2-Spot-Instances_2020_0401-CMP_OD.html?&trk=ep_card-el_a131L0000084iG2QAI&trkCampaign=NA-FY20-AWS-DIGMKT-WEBINAR-SERIES-April_2020_0401-CMP&sc_channel=el&sc_campaign=pac_2018-2019_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)
* [Video] [Optimize AI/ML, Kubernetes and Big data workloads at your startup](https://pages.awscloud.com/Optimize-AI-ML-Kubernetes-and-Big-Data-Workloads-at-Your-Startup_2020_0009-CMP_OD.html?&trk=ep_card-el_a134p000006BsCyAAK&trkCampaign=OnDemand_2020_0009-CMP&sc_channel=el&sc_campaign=pac_2018-2020_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)

#### Amazon ECS and Fargate Spot

* Leverage EC2 Spot with ECS Capacity Providers to manage compute capacity and scaling for your cluster.[Link](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/cluster-capacity-providers.html)
* Handle interruptions, use automated draining for Spot instance in ECS cluster.[Link](https://docs.aws.amazon.com/AmazonECS/latest/developerguide/container-instance-spot.html)
* [Deep dive into Fargate Spot to run your ECS Tasks for up to 70% less.](https://aws.amazon.com/blogs/compute/deep-dive-into-fargate-spot-to-run-your-ecs-tasks-for-up-to-70-less/)
* Monitor Fargate Spot task interruption notifications to ensure workload resiliency.[Link](https://docs.amazonaws.cn/en_us/AmazonECS/latest/developerguide/ecs_cwe_events.html)
* [Using Fargate Spot to Optimize costs for serverless containers](https://pages.awscloud.com/Using-Fargate-Spot-to-Optimize-Costs-for-Serverless-Containers_2019_1203-CON_OD.html?&trk=ep_card-el_a131L0000058gpwQAA&trkCampaign=NA-FY19-AWS-DIGMKT-WEBINAR-SERIES-December_2019_1203-CON&sc_channel=el&sc_campaign=pac_2018-2019_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)


### - Web Applications

* [Running Web Applications on Amazon EC2 Spot Instances](https://aws.amazon.com/blogs/compute/running-web-applications-on-amazon-ec2-spot-instances/)
* [How to build scalabe web applications with EC2 Spot](https://pages.awscloud.com/How-to-Build-Scalable-Web-Based-Applications-for-Less-with-Amazon-EC2-Spot-Instances_2020_0327-CMP_OD.html?&trk=ep_card-el_a131L0000084iGQQAY&trkCampaign=NA-FY20-AWS-DIGMKT-WEBINAR-SERIES-March_2020_0327-CMP&sc_channel=el&sc_campaign=pac_2018-2019_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)

### - CI/CD

* [Cost Optimize your Jenkins CI/CD pipelines using EC2 Spot Instances](https://aws.amazon.com/blogs/compute/cost-optimize-your-jenkins-ci-cd-pipelines-using-ec2-spot-instances/)
* [Running Enteprise CI/CD workloads with Spot instances and Cloudbees](https://pages.awscloud.com/Running-Enterprise-CI-CD-workloads-with-Amazon-EC2-Spot-Instances-and-CloudBees_2019_0616-CMP_OD.html?&trk=ep_card-el_a131L000005v8UtQAI&trkCampaign=NA-FY19-AWS-DIGMKT-WEBINAR-SERIES-June_2019_0616-CMP&sc_channel=el&sc_campaign=pac_2018-2019_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)


### - Machine Learning

* [Article] [Train Deep Learning Models on GPUs using Amazon EC2 Spot Instances](https://aws.amazon.com/blogs/machine-learning/train-deep-learning-models-on-gpus-using-amazon-ec2-spot-instances/)
* [Article] [TensorFlow Serving on Kubernetes with Amazon EC2 Spot Instances](https://aws.amazon.com/blogs/compute/tensorflow-serving-on-kubernetes-spot-instances/)
* [Video] [Reduce Inferencing costs by up to 90% Using Elastic Inference and Spot Instances](https://pages.awscloud.com/Reduce-Inferencing-Cost-by-Up-to-90-Percent-Using-Amazon-Elastic-Inference-and-Amazon-EC2-Spot-Instances_2020_0002-CMP_OD.html?&trk=ep_card-el_a131L0000083Ub9QAE&trkCampaign=NA-FY20-AWS-DIGMKT-WEBINAR-SERIES-OnDemand_2020_0002-CMP&sc_channel=el&sc_campaign=pac_2018-2019_exlinks_ondemand_OTT_evergreen&sc_outcome=Product_Adoption_Campaigns&sc_geo=NAMER&sc_country=mult)

### - Autonomous Vehicle

* [Autonomous Vehicle and ADAS development on AWS Part 1: Achieving Scale](https://aws.amazon.com/blogs/industries/autonomous-vehicle-and-adas-development-on-aws-part-1-achieving-scale/)

### Tools
* [Spot Instance Advisor](https://aws.amazon.com/ec2/spot/instance-advisor/)
* [AWS Node Termination Handler](https://github.com/aws/aws-node-termination-handler)
* [Amazon EC2 Instance Selector](https://github.com/aws/amazon-ec2-instance-selector)
* [Amazon EC2 Metadata Mock](https://github.com/aws/amazon-ec2-metadata-mock)
* [AutoSpotting](https://github.com/AutoSpotting/AutoSpotting)
* [EC2 Spot Interruption Dashboard](https://github.com/aws-samples/ec2-spot-interruption-dashboard)

### Tutorials 

* [Amazon EKS with EC2 Spot Instances](https://aws.amazon.com/getting-started/hands-on/amazon-eks-with-spot-instances/)
* [Running Batch jobs at scale for less with EC2 Spot instances](https://aws.amazon.com/getting-started/hands-on/run-batch-jobs-at-scale-with-ec2-spot/)
* [Optimizing Amazon EMR clusters with EC2 Spot instances](https://aws.amazon.com/getting-started/hands-on/optimize-amazon-emr-clusters-with-ec2-spot/)
* [Optimizing and Scaling Machine Learning Training  with managed Spot Trainig for Amazon Sagemaker](https://aws.amazon.com/getting-started/hands-on/managed-spot-training-sagemaker/)

### Customer Stories

* https://aws.amazon.com/ec2/spot/testimonials/ - Examples of how customers have achieved business agility, cost savings, and scale with EC2 Spot instances.
* [Capacity-Optimized Spot Instance allocation Strategy in action at Mobileye and Skyscanner](https://aws.amazon.com/blogs/aws/capacity-optimized-spot-instance-allocation-in-action-at-mobileye-and-skyscanner/)
* [Western Digital HDD Simulation at Cloud Scale – 2.5 Million HPC tasks, 40K EC2 Spot Instances](https://aws.amazon.com/blogs/aws/western-digital-hdd-simulation-at-cloud-scale-2-5-million-hpc-tasks-40k-ec2-spot-instances/)
* [Nearmap Builds AWS-Powered ML Pipeline to Help Others Analyze the World](https://aws.amazon.com/solutions/case-studies/nearmap-spot/)


### News and Announcements
* [Jul-2020] [Amazon EMR now supports Managed Scaling – automatically resizing clusters to lower cost](https://aws.amazon.com/about-aws/whats-new/2020/07/amazon-emr-now-supports-managed-scaling-automatically-resizing-clusters-to-lower-cost/)
* [Jul-2020] [AWS Marketplace AMIs now supported with Spot Instances in the EC2 Launch Instance Wizard](https://aws.amazon.com/about-aws/whats-new/2020/07/aws-marketplace-amis-supported-with-spot-instances-in-ec2-launch-instance-wizard/)
* [Jun-2020] [Amazon EMR uses real-time capacity insights to provision spot instances to lower cost and interruption](https://aws.amazon.com/about-aws/whats-new/2020/06/amazon-emr-uses-real-time-capacity-insights-to-provision-spot-instances-to-lower-cost-and-interruption/)
* [Jan-2020] [Amazon EC2 Spot instances can now be stopped and started similar to On-Demand instances](https://aws.amazon.com/about-aws/whats-new/2020/01/amazon-ec2-spot-instances-stopped-started-similar-to-on-demand-instances/)
* [Dec-2019] [Amazon ECS Capacity Providers Now Available](https://aws.amazon.com/about-aws/whats-new/2019/12/amazon-ecs-capacity-providers-now-available/)

