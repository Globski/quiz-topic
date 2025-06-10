# Question: What installation requirements exist for Docker and Kubernetes on Linux?

**Answer:** Users must refer to their Linux distribution's documentation for installation instructions.

---

# Question: What is required for using Docker Desktop on Windows and Mac?

**Answer:** Docker Desktop must be installed with Kubernetes enabled.

---

# Question: According to Wikipedia, what is microservices architecture a variant of?

**Answer:** Service-Oriented Architecture (SOA).

---

# Question: How does microservices architecture structure an application?

**Answer:** As a collection of **loosely coupled** services.

---

# Question: What does “fine-grained” mean in the context of microservices?

**Answer:** Each service has its **own specific responsibilities**.

---

# Question: What types of lightweight protocols are commonly used in microservices?

**Answer:** **HTTP** and **gRPC**.

---

# Question: How is a monolithic application typically built and deployed?

**Answer:** As **one single unit**, often compiled together and deployed as a single package onto servers.

---

# Question: What is the impact of scaling a monolithic system?

**Answer:** You must spin up **new VMs** and **deploy the entire system** on each one.

---

# Question: What is an example of a monolithic application architecture?

**Answer:** A **three-tier (3-tier)** application.

---

# Question: Despite separation into layers, why is a monolithic 3-tier app still considered tightly coupled?

**Answer:** Because all components (web, business layer, etc.) **run in the same address space** and require direct **project references**.

---

# Question: How are microservices different from monolithic systems in terms of scaling?

**Answer:** Each microservice can be **scaled independently**.

---

# Question: How do microservices expose their functionality?

**Answer:** Through an **API**, often over **HTTP** or **gRPC**.

---

# Question: Can microservices be developed using different programming languages?

**Answer:** Yes, teams can use languages like **Go**, **PHP**, **C#**, etc.

---

# Question: How can microservices handle data storage?

**Answer:** Each service can use its own **domain-specific database**.

---

# Question: What is the recommended deployment approach for microservices?

**Answer:** **Independent deployment** of each service.

---

# Question: What pattern did Martin Fowler describe for migrating monoliths to microservices?

**Answer:** The **Strangler pattern**.

---

# Question: How does the Strangler pattern facilitate monolith-to-microservices migration?

**Answer:** By placing a **facade** that routes calls to the legacy system initially, and then to the new microservice as it replaces the old code.

---

# Question: What happens to the legacy system as the Strangler pattern progresses?

**Answer:** The **legacy code is gradually replaced**, and eventually, the monolith becomes obsolete.

---

