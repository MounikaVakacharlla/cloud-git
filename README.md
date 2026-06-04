Hello Cloud & Git
Learning Git Version Control

# DevOps Fundamentals - Day 1 Learning Notes

## 1. Cloud Computing

### What is Cloud Computing?

Cloud computing is the delivery of computing services such as servers, storage, databases, networking, and software over the internet. Instead of purchasing and maintaining physical hardware, organizations can rent resources from cloud providers and pay only for what they use.

In simple terms, cloud computing allows businesses to use computing resources on demand without owning the infrastructure.

### Why Cloud Computing Matters

Cloud computing helps organizations:

* Scale resources based on demand
* Reduce infrastructure costs
* Improve reliability and availability
* Deploy applications faster
* Focus on application development instead of hardware management

### Major Cloud Providers

#### Amazon Web Services (AWS)

AWS is a cloud computing platform provided by Amazon. It offers a wide range of services including virtual servers, storage, databases, and monitoring tools.

Popular Services:

* EC2 (Virtual Servers)
* S3 (Storage)
* RDS (Databases)
* CloudWatch (Monitoring)

#### Microsoft Azure

Azure is Microsoft's cloud computing platform that provides services for building, deploying, and managing applications through global data centers.

Popular Services:

* Azure Virtual Machines
* Azure Blob Storage
* Azure SQL Database
* Azure Monitor

#### Google Cloud Platform (GCP)

GCP is Google's cloud computing platform that provides infrastructure, storage, analytics, and machine learning services.

Popular Services:

* Compute Engine
* Cloud Storage
* Cloud SQL
* Google Kubernetes Engine (GKE)

### Benefits of Cloud Computing

#### Scalability

Resources can be increased or decreased based on workload demand.

#### Cost Efficiency

Organizations pay only for the resources they use instead of purchasing expensive hardware.

#### Reliability

Cloud providers maintain multiple data centers and backup systems to ensure high availability.

---

## 2. Deployment Basics

### What is Deployment?

Deployment is the process of moving an application from development environments to production environments where end users can access it.

In simple terms, deployment means releasing software so that users can use it.

### Deployment Lifecycle

Development → Staging → Production```

#### Development (Dev)

Developers write code, fix bugs, and perform initial testing.

#### Staging

The application is tested in an environment similar to production to validate functionality and performance.

#### Production (Prod)

The application is deployed to live users.

### Manual Deployment

Manual deployment requires a person to perform deployment steps such as copying files, configuring servers, and restarting applications.

Advantages:

* Easy to understand

Disadvantages:

* Time-consuming
* Error-prone
* Difficult to scale

### Automated Deployment

Automated deployment uses CI/CD pipelines and automation tools to deploy applications automatically.

Advantages:

* Faster deployments
* Fewer human errors
* Consistent deployment process

Examples of Tools:

* Jenkins
* GitHub Actions
* GitLab CI/CD
* Azure DevOps

---

## 3. Git Version Control

### What is Git?

Git is a distributed version control system that helps developers track changes in files and source code over time.

It acts as a history tracker for projects and allows teams to collaborate efficiently.

### Why Git is Important

Git helps developers:

* Track changes
* Collaborate with team members
* Maintain project history
* Restore previous versions
* Integrate with CI/CD pipelines

### Common Git Commands

#### Verify Git Installation

```bash
git --version
```

#### Configure Git Profile

```bash
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

#### Initialize Repository

```bash
git init
```

#### Check Repository Status

```bash
git status
```

#### Stage Files

```bash
git add README.md
```

#### Create Commit

```bash
git commit -m "Initial commit"
```

#### View Commit History

```bash
git log
```

### What I Learned

* Git tracks project changes using commits.
* Repositories store project files and history.
* Meaningful commit messages improve project maintainability.
* Git is a foundational tool used in DevOps and software development workflows.

---

## Conclusion

Today's learning focused on three fundamental DevOps concepts: Cloud Computing, Deployment Basics, and Git Version Control. Cloud computing enables organizations to use resources on demand, deployment makes applications available to users, and Git helps track and manage changes in software projects. Together, these concepts form the foundation of modern DevOps practices.

