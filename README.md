# Multi-Tier Java Web Application on Premises

## Description
This repository demonstrates the creation and automation of a multi-tier Java web application hosted on local infrastructure using various virtualization and provisioning tools. The project is divided into two parts:

- **Project1**: Manual setup of the multi-tier web application with individual configuration of each service within virtual machines.
- **Project2**: Automating the entire process using shell scripts to provision services like Tomcat, Nginx, RabbitMQ, Memcached, MySQL, and manage them within a Vagrant-based virtualized environment.

Each project provides hands-on experience with key technologies including Vagrant, VirtualBox/VMware, Tomcat, Nginx, RabbitMQ, Memcached, MySQL, Maven, and Git.

## Objectives:
- Build a Java-based web application with a multi-tier architecture. 
- Configure services manually to understand each component's setup process.
- Automate the entire configuration using shell scripts to streamline deployment.
- Develop troubleshooting and debugging skills during integration and setup.

## Key Features:
- **Vagrant**: For managing virtual machines.
- **VirtualBox/VMware**: For virtualization.
- **Tomcat**: For hosting Java web applications.
- **Nginx**: For reverse proxy and static content serving.
- **RabbitMQ**: For message brokering.
- **Memcached**: For distributed caching.
- **MySQL**: For relational data storage.
- **Maven**: For Java project build automation.
- **Git**: For version control.

##multi-tier-java-web-app/
- ├── Project1/       # Contains manual setup project files
- ├── Project2/       # Contains automation project files
- ├── docs/           # Documentation for both projects
- └── README.md       # Main project overview and description

## Project1: Manual Setup
In **Project1**, each component of the multi-tier Java web application is manually installed and configured on its own virtual machine.

### Steps:
1. **Set Up Vagrant Environment**: 
   - Install [Vagrant](https://www.vagrantup.com/).
   - Create `Vagrantfile` to configure VM settings for each service.
   
2. **Create Virtual Machines**:
   - Use Vagrant to create VMs for:
     - Tomcat (for the Java application)
     - Nginx (as reverse proxy)
     - RabbitMQ (for messaging)
     - Memcached (for caching)
     - MySQL (for database)

3. **Manual Configuration**:
   - Install and configure each service on its respective VM.
     - Tomcat: Deploy Java web application.
     - Nginx: Configure as reverse proxy.
     - RabbitMQ: Set up message brokering.
     - Memcached: Enable caching mechanism.
     - MySQL: Configure database for the application.
   
4. **Integration**:
   - Connect all services together to create a multi-tier architecture.

5. **Testing**:
   - Verify the application and troubleshoot any issues.

6. **Documentation**:
   - Record configuration steps and troubleshooting techniques.

## Project2: Automating Setup with Shell Scripts
In **Project2**, the setup process is automated through shell scripts, simplifying the installation and configuration of all components.

### Steps:
1. **Set Up Vagrant Environment**: 
   - Install Vagrant and configure the virtual machine settings.

2. **Develop Shell Scripts**:
   - Write shell scripts to automate the installation and configuration of the following services:
     - Tomcat
     - Nginx
     - RabbitMQ
     - Memcached
     - MySQL

3. **Create Virtual Machines**:
   - Use Vagrant to create separate VMs for each service.

4. **Automate Configuration**:
   - Use the developed shell scripts to automatically configure the VMs.

5. **Integration**:
   - Ensure that all services are correctly integrated.

6. **Testing**:
   - Validate the automated setup and resolve any issues.

7. **Documentation**:
   - Document the shell scripts and procedures used .

## Documentation
Detailed documentation for both manual and automated setups, including troubleshooting guides and additional configuration options, is available in the `docs/` directory.

---

By completing both Project1 and Project2, you will gain essential skills for building, deploying, and automating scalable multi-tier web applications in a real-world environment.
