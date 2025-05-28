# Question: What was the major limitation of running applications before virtualization technology like VMware?

**Answer:**
Only one application could safely and securely run per server, which led to underutilization of hardware and inefficiency.

---

# Question: What key innovation did VMware introduce that changed how applications run on servers?

**Answer:**
VMware introduced the virtual machine (VM), allowing multiple business applications to run safely and securely on a single server.

---

# Question: How did virtual machines improve server utilization for businesses?

**Answer:**
They allowed IT departments to run multiple applications on existing servers with spare capacity, reducing the need to buy new, oversized servers and getting more value from existing hardware.

---

# Question: Besides resource consumption, what other issues do virtual machines have?

**Answer:**
They require patching and monitoring for each OS, may need separate licenses, are slow to boot, and have poor portability between hypervisors and cloud platforms.

---

# Question: How do containers differ from virtual machines in terms of operating system usage?

**Answer:**
Containers share the host’s operating system, whereas each virtual machine requires its own full OS, saving system resources like CPU, RAM, and storage.

---

# Question: What are some benefits of containers compared to virtual machines?

**Answer:**
Containers save time, resources, and capital by reducing OS overhead and licensing costs, they start quickly, and are highly portable across different environments.

---

# Question: Which company contributed significantly to the development of modern Linux container technologies?

**Answer:**
Google LLC contributed many container-related technologies to the Linux kernel.

---

# Question: Name some key technologies that enabled the growth of modern containers.

**Answer:**
Kernel namespaces, control groups, union filesystems, and Docker are major technologies that enabled container growth.

---

# Question: Why did containers remain complex and inaccessible before Docker?

**Answer:**
Containers required deep technical knowledge and complex setup, making them difficult for most organizations to use effectively.

---

# Question: How did Docker change the use of containers?

**Answer:**
Docker simplified containers, making them accessible and usable for a wide audience beyond just technical experts.

---

# Question: Have container technologies always been new? Give examples of older OS virtualization technologies.

**Answer:**
No, container-like technologies date back to older systems like System/360 on Mainframes, BSD Jails, and Solaris Zones.

---

# Question: What recent effort has Microsoft made regarding containers?

**Answer:**
Microsoft has worked hard to bring Docker and container technologies to the Windows platform.

---

# Question: On which Windows platforms are Windows containers available?

**Answer:**
Windows containers are available on certain versions of Windows 10 and later, and Windows Server 2016 and later.

---

# Question: How has Microsoft collaborated to enable containers on Windows?

**Answer:**
Microsoft worked closely with Docker, Inc. and the open-source community to develop Windows Containers and user-space tooling that integrates with Docker.

---

# Question: Why can’t a Windows container run on a Linux Docker host, and vice versa?

**Answer:**
Because a container shares the host machine’s kernel, Windows containers require a Windows host, and Linux containers require a Linux host.

---

# Question: How can Linux containers run on Windows machines?

**Answer:**
Linux containers on Windows run either inside a lightweight Hyper-V VM or using the Windows Subsystem for Linux (WSL), with WSL being the newer, more performant option.

---

# Question: Are there native Mac containers?

**Answer:**
No, but Linux containers can run on Macs via Docker Desktop inside a lightweight Linux VM.

---

# Question: What is Kubernetes and why is it important?

**Answer:**
Kubernetes is an open-source container orchestrator from Google, widely used for deploying and managing containerized applications.

---

# Question: What container runtime does Kubernetes use by default, and what might replace it in the future?

**Answer:**
Kubernetes uses Docker as the default container runtime but may replace it with containerd in the future.

---

# Question: What is containerd in relation to Docker?

**Answer:**
Containerd is a small, specialized part of Docker responsible for the low-level tasks of starting and stopping containers.

---

# Question: How does Kubernetes relate to Docker in terms of container operations?

**Answer:**
Kubernetes is a higher-level platform that currently uses Docker for its low-level container-related operations.

---

# Question: What was the traditional approach every time a business needed a new application before VMware?

**Answer:**
The IT department had to buy a brand-new server for each new application.

---

# Question: What problem did VMware solve for IT departments?

**Answer:**
VMware allowed multiple applications to run safely on a single server, improving utilization and driving more value from existing IT assets.

---

# Question: Despite its benefits, why is the VM model not perfect?

**Answer:**
Because each VM requires a full OS, which consumes additional resources and overhead.

---

# Question: How did containers improve upon the VM model?

**Answer:**
Containers are more efficient and lightweight, sharing the host OS and using fewer resources.

---

# Question: Why were containers initially only used by large web companies?

**Answer:**
Containers were complex to implement and required specialized Linux kernel engineering knowledge.

---

# Question: What role did Docker, Inc. play in container technology?

**Answer:**
Docker simplified and democratized containers, making them accessible to a wider range of users beyond large tech companies.

---

# Question: What are the two meanings of the term “Docker” as used in container technology?

**Answer:**
“Docker” can refer to Docker, Inc. (the company) or Docker (the container technology/software).

---

# Question: What does Docker software do?

**Answer:**
Docker runs on Linux and Windows, creating, managing, and orchestrating containers.

---

# Question: From what open-source project is Docker software built?

**Answer:**
Docker is built from various tools from the Moby open-source project.

---

# Question: Who founded Docker, Inc., and where is the company based?

**Answer:**
Docker, Inc. was founded by Solomon Hykes, a French-born American developer, and is based in San Francisco.

---

# Question: What was Docker, Inc.'s original platform called, and what was it built on?

**Answer:**
The original platform was called dotCloud, a platform-as-a-service built on Linux containers.

---

# Question: How did the Docker technology get its name?

**Answer:**
The name “Docker” comes from a British expression for a dock worker who loads and unloads cargo from ships.

---

# Question: What are the two meanings of the term “Docker” as used in container technology?

**Answer:**
“Docker” can refer to Docker, Inc. (the company) or Docker (the container technology/software).

---

# Question: What does Docker software do?

**Answer:**
Docker runs on Linux and Windows, creating, managing, and orchestrating containers.

---

# Question: From what open-source project is Docker software built?

**Answer:**
Docker is built from various tools from the Moby open-source project.

---

# Question: Who founded Docker, Inc., and where is the company based?

**Answer:**
Docker, Inc. was founded by Solomon Hykes, a French-born American developer, and is based in San Francisco.

---

# Question: What was Docker, Inc.'s original platform called, and what was it built on?

**Answer:**
The original platform was called dotCloud, a platform-as-a-service built on Linux containers.

---

# Question: How did the Docker technology get its name?

**Answer:**
The name “Docker” comes from a British expression for a dock worker who loads and unloads cargo from ships.

---

# Question: What major change did Docker, Inc. make in 2013?

**Answer:**
They shut down the struggling PaaS side of the business, rebranded as Docker, Inc., and focused on bringing Docker and containers to the world.

---

# Question: What products is Docker, Inc. focusing on to help streamline application deployment?

**Answer:**
Docker Desktop and Docker Hub.

---

# Question: What are the three main components of Docker technology?

**Answer:**
The runtime, the daemon (engine), and the orchestrator.

---

# Question: What is the role of the Docker runtime?

**Answer:**
It operates at the lowest level, responsible for starting and stopping containers and building OS constructs like namespaces and cgroups.

---

# Question: What is the low-level runtime in Docker called, and what does it do?

**Answer:**
It’s called runc, and it interfaces with the OS to start and stop containers.

---

# Question: What is containerd, and how does it relate to runc?

**Answer:**
containerd is a higher-level runtime that manages the full lifecycle of containers, including pulling images and managing runc instances. It works alongside runc to run containers.

---

# Question: How is containerd pronounced and what notable projects use it?

**Answer:**
It’s pronounced “container-dee” and is used by both Docker and Kubernetes as a container runtime.

---

# Question: What process controls the runc instances in a typical Docker installation?

**Answer:**
A single containerd process (docker-containerd) controls the runc (docker-runc) instances for each running container.

---

# Question: What is the role of the Docker daemon (dockerd)?

**Answer:**
The Docker daemon performs higher-level tasks such as exposing the Docker remote API, managing images, volumes, networks, and provides a user-friendly interface that abstracts the lower-level components.

---

# Question: What is Docker Swarm?

**Answer:**
Docker Swarm is Docker’s native clustering and orchestration technology for managing clusters of Docker nodes.

---

# Question: Why do most companies prefer Kubernetes over Docker Swarm?

**Answer:**
Although Docker Swarm is easy to use, most companies prefer Kubernetes due to its widespread adoption and advanced orchestration features.

---

# Question: What is the Open Container Initiative (OCI)?

**Answer:**
OCI is a governance council focused on standardizing fundamental components of container infrastructure, especially image format and container runtime.

---

# Question: What was the conflict that led to the formation of OCI?

**Answer:**
CoreOS created a competing open standard called appc and an implementation called rkt, which threatened to fracture the container ecosystem with competing standards.

---

# Question: What is the purpose of OCI standards like image-spec and runtime-spec?

**Answer:**
These standards define the “rail tracks” (standard sizes and properties) for container images and runtimes, allowing innovation in other areas while ensuring compatibility.

---

# Question: What analogy is often used to explain OCI’s role in container standards?

**Answer:**
OCI standards are like agreed-upon rail tracks that allow everyone else to build better trains.

---

# Question: How do the OCI specifications impact Docker’s architecture?

**Answer:**
Since Docker 1.11, the Docker Engine architecture conforms to the OCI runtime specification, reflecting a major influence of OCI standards on Docker’s core design.

---

# Question: Under which organization is the Open Container Initiative (OCI) organized?

**Answer:**
The OCI is organized under the Linux Foundation.

---

# Question: What are the main focuses of Docker, Inc. and Docker technology?

**Answer:**
Docker, Inc. aims to change how software is built and run, having been a key instigator of the modern container revolution. Docker technology focuses on running and managing application containers on Linux and Windows.

---

# Question: On which platforms can Docker be installed and run?

**Answer:**
Docker can be installed and run on Linux and Windows platforms, and virtually anywhere.

---

# Question: What role does Docker play in Kubernetes?

**Answer:**
Docker is currently the most popular container runtime used by Kubernetes.

---

# Question: What was the key role of the Open Container Initiative (OCI) in the container ecosystem?

**Answer:**
The OCI standardized container runtime and image formats, enabling greater compatibility and fostering ecosystem growth.

---

# Question: What analogy is used to describe the importance of container standards?

**Answer:**
The analogy of standard rail tracks is used—just as standardized tracks allow better trains, signaling, and stations to be built safely and compatibly, container standards enable innovation without fragmentation.

---

