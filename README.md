[![CARC](./images/carc-logo.png 'CARC')](https://carc.usc.edu)
# Biology with Conda on CARC - Workshop

This repository contains preconfigured Jupyter notebook, to run on USC CARC Discovery Cluster. 

## By participating in this workshop, you’ll:

* Learn the fundamental skills and tools required to manage conda environments on CARC Cluster

* Get a bit more familiar with Linux terminal

* Gain experience with biological data processing

* Learn how to create and manage your own conda environments

#### Duration: 1.5 hours
#### Prerequisites: An understanding of fundamental CARC Cluster setup and CARC Ondemand.
#### Suggested materials to satisfy prerequisites:
* [Gettting started with Discovery](https://www.carc.usc.edu/user-guides/hpc-systems/discovery/getting-started-discovery.html)

* [CARC Ondemand](https://www.carc.usc.edu/user-guides/carc-ondemand.html)


#### Hardware Requirements: Desktop or laptop computer capable of running the latest version of a modern web browser like Chrome, Safari, Edge or Firefox. 

#### Language: English

## Getting Started
To get started, use a web browser and log on to USC OnDemand Instance at [https://ondemand.carc.usc.edu](https://ondemand.carc.usc.edu) . You need to be on USC Network and need to your USC credentials to log in. More details on how to logon to USC Open OnDemand can be found at [our guide](https://www.carc.usc.edu/user-guides/carc-ondemand.html)

To start a Jupyter notebook server, Click on Interactive Apps and then select JupyterLab.

![Start JupyterLab](./images/jupyterlab-start.png)

When launching the Jupyter Lab, it is important to select the following
* For Cluster, specify Discovery
* For Account, specify the account you normally use, like `ttrojan_123`
* For Partition, specify main
* Set the number of CPUs to 1
* Set Memory to 2GB
* Set the number of hours to 4

For the regular CARC workshop, please do the above with the following change:
* For Account (CARC workshop), specify `hpcsuppt_613`
* For Account (DSR-626), specify `ujadhav_1068`
* For Account (BIOC-599), specify `rhie_131`


The above settings are important to ensure you start a JupyterLab Server on a node that is located on the Discovery cluster and has slurm management engine installed and configured

![Launch JupyterLab](./images/jupyterlab-launching.png)

Once your JupyterLab Session starts, Click Connect to JupyterLab button

![Connect to Running JupyterLab](./images/jupyterlab-running.png)

From there, Click on File -> New and then click on Terminal to get the terminal

![Shell Access In Jupyter](./images/terminal-start.png)

Once in the terminal, clone this GitHub Repository

```
module load usc git
git clone https://github.com/uschpc/biology-with-conda-on-carc.git
```

In Jupyter, navigate to the example you are interested in, and step through the notebook. 

For first-time users, we highly recommend to do the notebooks in order, as they build up on concepts in the previous notebooks.

