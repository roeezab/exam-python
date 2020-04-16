# exam-python
Simple project for the devops candidate exam

## Instructions
In order to continue developing this project and test your changes, do the following:
1. Clone this repo
2. Make your changes to the code
3. Push your changes. This will trigger a build in [Jenkins](http://18.132.80.194:8080/job/exam-python/)
4. Download and install [VirtualBox](https://www.virtualbox.org/) and [Vagrant](https://www.vagrantup.com/)
5. Cd into devops/ directory
6. Run **vagrant up** and wait a few minutes for everything to be ready
7. Go to http://localhost:5000 to see your app
8. If you want to make more changes: change the code, push the changes, and then run **vagrant provision** to update your local VM
9. When you're done, remove the VM with **vagrant destroy**
