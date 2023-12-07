# aws

# cloud computing
<img width="1440" alt="Screenshot 2023-12-06 at 8 46 56 PM" src="https://github.com/dhirukumar/aws/assets/146316525/ec50b195-d62f-4003-b768-6ffb1bc6366c">

- Simply put, cloud computing is the delivery of computing services—including servers, storage, databases, networking, software, analytics, and intelligence—over the internet (“the cloud”) to offer faster innovation, flexible resources, and economies of scale.

# Advantages of cloud computing
<img width="1440" alt="Screenshot 2023-12-06 at 8 47 02 PM" src="https://github.com/dhirukumar/aws/assets/146316525/3353028a-3add-4009-8d86-05d209f7c75e">

- Scalability

- Collaboration

- Automatic software integration

- Data recovery

- Sustainability

- Data security

# Disadvantages of Cloud Computing
<img width="1440" alt="Screenshot 2023-12-06 at 8 47 09 PM" src="https://github.com/dhirukumar/aws/assets/146316525/0b05401e-2660-42d0-865d-fec48e3cde40">

- data loss or theft.
  
- data leakage.
 
- account or service hijacking.
  
- insecure interfaces and APIs.
  
- denial of service attacks.
  
- technology vulnerabilities, especially in shared environments.

 <img width="1000" alt="Screenshot 2023-12-06 at 8 47 25 PM" src="https://github.com/dhirukumar/aws/assets/146316525/5bdef18c-7018-4278-baea-2424be6ed141">
<img width="1000" alt="Screenshot 2023-12-06 at 8 47 30 PM" src="https://github.com/dhirukumar/aws/assets/146316525/a334551f-1c28-49e7-a193-cf71fe28f3fe">
<img width="1440" alt="Screenshot 2023-12-06 at 8 47 35 PM" src="https://github.com/dhirukumar/aws/assets/146316525/197a3238-3f57-4cf6-9a6f-85427efdbff8">

## There are also three main types of cloud computing services: Infrastructure-as-a-Service (IaaS), Platforms-as-a-Service (PaaS), and Software-as-a-Service (SaaS).
<img width="1440" alt="Screenshot 2023-12-06 at 8 47 44 PM" src="https://github.com/dhirukumar/aws/assets/146316525/6650ba8f-d95c-4374-9792-a436c92ac834">

## aws

- AWS is designed to allow application providers, ISVs, and vendors to quickly and securely host your applications – whether an existing application or a new SaaS-based application. You can use the AWS Management Console or well-documented web services APIs to access AWS's application hosting platform.
<img width="1440" alt="Screenshot 2023-12-06 at 8 47 53 PM" src="https://github.com/dhirukumar/aws/assets/146316525/1b99d6e8-bce3-4ba1-8ccf-01f3804e7ff9">

## what is compute services

- Compute services are also known as Infrastructure-as-a-Service (IaaS)
<img width="1440" alt="Screenshot 2023-12-06 at 8 48 00 PM" src="https://github.com/dhirukumar/aws/assets/146316525/f7f26aa6-b9eb-40a2-8e47-a7299cbccbdb">

## aws storage services

- There are three main cloud storage types: object storage, file storage, and block storage. Each offers its own advantages and has its own use cases.
- S3
- EBS : Amazon Elastic Block Storage is a storage service wherein each block of storage acts like a separate hard drive (volume) .
  
- EFS : dont need to assign any volume , can do on its own , seamless storage , database on EC2 instances
Archival service - Glacier : Amazon Glacier is extremely low cost, secure, and durable storage service for data archiving and backup. That data stored which are not needed instantly , eg old data . Takes time min 4 hours or 1 day to retrieve request ( S3 instantly returns request)

<img width="1440" alt="Screenshot 2023-12-06 at 8 48 07 PM" src="https://github.com/dhirukumar/aws/assets/146316525/bdacc05c-29fb-4247-a4f0-0a154cafd424">

## Network Services

- It is a cloud computing empire that leverages cloud-based services to provide flexible virtual infrastructure for its customers

- VPC : own insolated environment in a public cloud
  
- Domain Name Service - Route 53

### Instance storage = the storage comes with EC2 to like storage come with laptop

### No doubt instance a storage is faster but when we shut down EC2 to instance a storage is gone in some EC2  instance storage comes
<img width="1440" alt="Screenshot 2023-12-06 at 9 41 39 PM" src="https://github.com/dhirukumar/aws/assets/146316525/ca0a6a03-e52d-427c-a26b-4f78ea8fe822">

  - WHAT TYPE OF EC2

    - c type EC2 = more CPU
   
    - m type EC2 = for genral purpose
   
    - r type EC2 = more RAM
   
    - t type EC2 = It is credi base instance in which you use your 10% of instance CPU then you collect your 90% credit and when you hit is increase then you use your credit to your need
   
- public subnet : can receive traffic from outerworld
  
- private subnet : cannot receive traffic from outerworld but may or may not send traffic to outerworld
<img width="1440" alt="Screenshot 2023-12-06 at 9 41 48 PM" src="https://github.com/dhirukumar/aws/assets/146316525/8f98f384-ca17-4f2c-8ddd-cd90ea58d356">

- Apache web server works on layer 7 , using single apache server one can deploy multiple applications on different ports based on paths (URLbased) (virtual hosts) . virtual hosting can only work on layer 7
<img width="1440" alt="Screenshot 2023-12-06 at 9 41 18 PM" src="https://github.com/dhirukumar/aws/assets/146316525/56418bda-0285-4dac-8798-29000435f84c">

- What Is Object Storage

  - Object storage is a data storage architecture that manages data as distinct units, known as objects. Each object contains the actual data, metadata, and a unique identifier. The metadata stored alongside the data can include information such as creation date, size, and custom attributes. This approach to data storage offers substantial benefits in terms of scalability, cost-efficiency, and ease of use. It is a primary form of storage used in cloud computing infrastructure.
 
- What Is Block Storage?

   - Block storage is a data storage architecture that divides data into fixed-size blocks, each with a unique address. Block storage devices, such as hard disk drives and solid-state drives, use block-level access protocols like iSCSI and Fibre Channel to read and write data. This storage method is ideal for low-latency, high-performance environments where data access speed is crucial.
 <img width="1440" alt="Screenshot 2023-12-06 at 9 41 24 PM" src="https://github.com/dhirukumar/aws/assets/146316525/8291432e-9750-43ad-8cee-f633a4a66b4c">
<img width="1440" alt="Screenshot 2023-12-06 at 9 41 34 PM" src="https://github.com/dhirukumar/aws/assets/146316525/a7c06073-2548-4701-a32a-ddb4e2e1d712">

## load balencer
<img width="1440" alt="Screenshot 2023-12-05 at 8 27 42 PM" src="https://github.com/dhirukumar/aws/assets/146316525/4b1da62a-2d39-43df-b076-1847e66c9fa9">

- Load balancing in cloud computing is the process of distributing workloads and traffic across multiple resources

- security group = it is act like fire wall for instance

- ELB(elistic load balancer) = Elastic Load Balancing (ELB) is a load balancing service that distributes incoming application traffic to multiple targets

## how to deploy load balencer

1) make a instance in any os but this is amazon linux
2) Run nginx

   1) Connect to your Amazon Linux Instance
      
               ssh -i "youkeyfile.pem" ec2-user@{instancePublicIP}
      instancepublicIP change with your public IP
   3) Update the Package Repository
      
              sudo dnf update -y
   5) Install Nginx
      
           sudo dnf install nginx -y
   7) Start Nginx Once the installation is complete, start the Nginx service using the following command:
      
            sudo systemctl start nginx
     ##### if ngnix not showing than change inbound to all trafic and my ip in costom box
     
3) creat a traffic group
4) make a load balencer in which you add traffic group and also check the helth condition 
<img width="1440" alt="Screenshot 2023-12-05 at 8 27 42 PM" src="https://github.com/dhirukumar/aws/assets/146316525/cc969283-10c8-4a20-ba5f-77be8a8d77ac">
<img width="1440" alt="Screenshot 2023-12-05 at 8 28 02 PM" src="https://github.com/dhirukumar/aws/assets/146316525/d255240b-03b0-4f74-b593-9164cbecff0c">
<img width="1440" alt="Screenshot 2023-12-05 at 8 30 34 PM" src="https://github.com/dhirukumar/aws/assets/146316525/5fb836be-f29f-45f3-b011-dcdd9aa046f4">
<img width="1440" alt="Screenshot 2023-12-06 at 6 16 54 PM" src="https://github.com/dhirukumar/aws/assets/146316525/638a7a7f-8805-4412-bf45-e09119a0ff76">
<img width="1440" alt="Screenshot 2023-12-06 at 6 18 40 PM" src="https://github.com/dhirukumar/aws/assets/146316525/f96f718f-c750-447d-a6c6-6803f47bf9ae"><img width="1440" alt="Screenshot 2023-12-06 at 6 19 26 PM" src="https://github.com/dhirukumar/aws/assets/146316525/703d72c9-e2e0-4d23-abb6-3c8fd9fa0c5a">
<img width="1440" alt="Screenshot 2023-12-06 at 6 20 44 PM" src="https://github.com/dhirukumar/aws/assets/146316525/1da554ef-91a6-4047-998a-c7f84863bf5e">
<img width="1440" alt="Screenshot 2023-12-06 at 6 34 37 PM" src="https://github.com/dhirukumar/aws/assets/146316525/701fc7bf-77f2-4cca-9ba1-9fbc1104177c">
<img width="1440" alt="Screenshot 2023-12-06 at 6 46 44 PM" src="https://github.com/dhirukumar/aws/assets/146316525/61d5b996-19b1-42a2-b3fa-e625ef925786">
<img width="1440" alt="Screenshot 2023-12-06 at 7 13 19 PM" src="https://github.com/dhirukumar/aws/assets/146316525/ad51b055-5ecf-41b3-a229-78f3385b2dd5">
<img width="1440" alt="Screenshot 2023-12-06 at 8 03 59 PM" src="https://github.com/dhirukumar/aws/assets/146316525/2b25b3d7-32a1-43c9-b9e7-15fd51c5deb9">













