# M1
Milestone 1 for Devops Project


<h2> Guidelines </h2>
* Go to jenkins folder and run create.yml. This will create the Vagrant VM and provision with the required software for jenkins. You can comment the part where it gets the crumb token etc. tasks responsible for creating a job<br>
* Create a github repo in your account with the files from checkbox folder<br>
* For now create two jobs i.e 1] one for building the checkbox job i.e fork profs repo 2] one for provisioning the checkbox i.e above repo. <br>
* Make sure that you select the build after other projects are built for the 2nd job. <br>
* As of now manually enter the github credentials for jenkins. <br>

<h2>Instruction for Vishal</h2>
* Create a job in jenkins with repo created with checkbox provision. <br>
* Make sure you have ansible installed on jenkins server. <br>
* Build the job by running ansible playbook createCheckboxVM.yml
