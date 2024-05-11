This is an example of creating a virtual environment and submitting the job to NSCC ASPIRE 2A through the Job and Visualization Portal.

# Create a virtual environment.
In this example, the virtual environment is created with miniforge3/23.10, due to the reason that Anaconda was removed from the platform in January 2024 (https://help.nscc.sg/removal-of-anaconda-modules-on-aspire-2a/).

- Step1: Log in to NSCC
- Step2: Load miniforge3/23.10\
`module load miniforge3`

- Step3: Create a virtual environment and activate\
`conda create -n myenv python=3.9`\
`conda activate myenv`
- Step4: Install dependencies

	[Install PyTorch](https://pytorch.org/get-started/locally/)


# Submit the job through the portal 
Please follow the instructions [here](https://help.nscc.sg/wp-content/uploads/aspire2a-job-portal-guide.pdf) to submit run.sh.\
Choose ShellScript in the applications to avoid loading other environments. 


