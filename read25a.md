# Docker
Docker is a containerization tool used for spinning up isolated, reproducible application environments.
Docker is really just Linux containers which are a type of virtualization.
How could multiple programmers use the same single machine? The answer was virtualization and specifically virtual machines which are complete copies of a computer system from the operating system on up.But What’s the downside to a virtual machine? Size and speed. A typical guest operating system can easily take up 700MB of size. So if one physical server supports three virtual machines, that’s at least 2.1GB of disk space taken up along with separate needs for CPU and memory resources.
How do the virtual environments differ from containers?
Virtual environments are used to isolate Python software packages locally. We can create an isolated box for individual projects so one can use Python 2.7 and Django 1.5 while another can use Python 3.5 and Django 2.1 on the same computer. Virtual environments are great.
## Library Website and API

> *Django REST Framework works alongside the Django web framework to create web APIs.* 
>> **We cannot build a web API with only Django Rest Framework** *it must be added to a project after Django itself has been installed and configured.*

___

## Traditional Django

> *First we need a dedicated directory on our computer to store the code.* 
> **The location really does not matter.**