# Devops
# Content
- Introduction
- Information

# Introduction

**What is DevOps?**
> The term DevOps, which is a combination of the English terms development (development) and operations (operations), refers to the union of people, processes and technology to offer value to customers on a constant basis.

**Advantages of DevOps**
> Teams that embrace DevOps culture, practices, and tools improve performance and create higher-quality products in less time, increasing customer satisfaction. This improvement in collaboration and productivity is also essential to achieve business objectives.

**What is Docker?**
> Docker is a software platform that allows you to quickly create, test, and deploy applications. Docker packages software in standardized units called containers that include everything necessary for the software to run, including libraries, system tools, code, and runtime. With Docker, you can quickly deploy and scale applications in any environment with the certainty that your code will run.

**What is Jenkins?**
> Jenkins is our test automation, it downloads the latest version of our branch where a change was made and performs the tests that we have and if they fail, it prevents us from breaking our main branch and tells us which tests were that failed to correct it.

### Homogeneous Environments for Applications

One of the ways to solve the "it works on my machine" is by having homogeneity in the environments. Running code on our local machine should look as close to the test and production environment as possible.

Docker is recommended, it works for all operating systems (WIN10 Pro only) and it is reproducible, we can have an infrastructure that shares everything. The images are reproducible, programmable and the documentation is in the same code.

### Artifacts
Artifacts is our unit that will pass to all environments, it must be something immutable. It's something we can store for a certain amount of time, maybe a year in case we need to rollback.

### Continous delivery 
Continous delivery is a fairly innovative software development concept that is being heard more and more frequently. Thanks to this practice, the production phases that include development, quality control and delivery, are not final, but are repeated in an automated way over and over again throughout the development process through a continuous pipeline. delivery. The main advantage is that, in this way, a software can undergo quality controls every so often in each of its development phases, allowing deliveries to be made, even if the team continues to work on the development of the final product. In addition, there is constant feedback that comes from the pipeline, which allows us to improve the software immediately after each modification made to the source code.

<div>
  <img src = "https://www.atuservicio.net/wp-content/uploads/integracion-continua-768x467.png" width "100%">
</div>

# Information

For more information you can check de [DevOps Platzi Course](https://platzi.com/clases/devops/)
