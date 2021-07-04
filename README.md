<h1 align="center"> ☁️ Cloud Native Fundamentals</h1>

<!-- Section Snippet -->
<!-- <details>
<summary></summary>
</details> -->

<!-- Image Snippet -->
<!-- ![imageName](path) -->

<details>
<summary>Lesson 3: Container Orchestration with Kubernetes</summary>

## Transitions From VMs to Containers

* In the past the default way to deploy application is to spin a VM.
* Copy the necessary binaries and artifacts and start the application.

![Transition from VMs to Containers](/images/Screenshot%202021-07-04%20at%208.50.31%20PM.png)

* `Infrastructure` is a set of servers or a physical machine.
* `Hypervisor` is a software used for virtualization. It can be used to run multiple VMs on a single machine.
* #### Pros
  * Standardization of a structure.
  * Multiple VMs in a single machine.
* #### Cons
  * Replicated OS in every VM. OS takes gigabytes which is a lot of usage of resources.
* A new way to virtualize the OS in the VM:
* #### Containerized Applications
![Virtualizing of OS](/images/Screenshot%202021-07-04%20at%208.53.21%20PM.png)
![Containerized Applications](/images/Screenshot%202021-07-04%20at%208.50.31%20PM.png)
* Instead of having multiple VMs, we can have one HostOS. `Containers` contains Apps. `Docker` is the container management tool.

</details>

