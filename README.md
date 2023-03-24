# Alternatives to Kubernetes

Compared to the applications of big companies, I have a small application.

On the other hand I want to learn new stuff, because I am curious.

Before choosing a Containerization Platforms, I create this list to get an overview.

My background: I like self-hosting (aka on-premise). I use Linux since 1996 and
can help myself in most cases.

My application needs: Python, Django, PostgreSQL, S3, Redis, Nginx, a task-queue.

Update 2023: I started this list two years ago. While comparing Kubernetes to other alternatives
I realized that I want to work with Kubernetes. I work for [Syself.com](//syself.com) since January 2023. 
The rest of this text is propably outdated.

# Nomad

[nomand](https://www.nomadproject.io/) made by HashiCorp looks promissing. 

# VPS, with docker-compose via systemd

I could use a simple and cheap VPS (virtual private server). This way I have a linux
with full root access and can do whatever I want.

For example I could use systemd to run docker-compose to run my services.

# Heroku

I could use Heroku.

But: Vendor Lock-In.

# AWS

But: Vendor Lock-In.

# Kubernetes Hosted

GKE, EKS, AKS or other 

# Kubernetes on VPSs

But which Kubernetes implementation?

* https://rancher.com/docs/k3s/latest/en/ Lightweight Kubernetes. Easy to install, half the memory, all in a binary of less than 100 MB.
* ....

# Docker Swarm

...

