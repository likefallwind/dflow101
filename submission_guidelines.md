# How to submit your dflow proposal to dflow101

## Step 1. Refine your documentation
To make it easy for others to read and understand the content of your project, you need to prepare following documentation in your own GitHub repository. 
- README.md document
- Executable script
- Other supporting files in your repository

### README.md
This file in your repository is supposed to illustrate the overview of your dflow proposal and the details of the corresponding dflow codes.

- Title

You'd better use several keywords to describe the workflow.

- Introduction

You need to specify what you want to do with dflow. For instance, you can describe the traditional workflow and then state how you can achieve the automatic workflow based on dflow. Naturally, you are encouraged to state why using dflow is beneficial.

- Details
You are encouraged to state the traditional application scenarios and the corresponding problems. Besides, you'd better describe your OP and step, including input(parameter, artifacts, etc.), output, execute and how to use OP templates by adding step. Last but not least, it will be appreciated if you point out where the user needs to make personalized changes, for example, the VASP execute environment, slurm connection, etc.

### Executable script
If you have more than one scripts, you are expected to describe the relationship between them in the Details part in README.md

### Supporting
- Upload files

If your dflow needs to upload files in step, you need to prepare example files.

- Dockerfile

If you use your own docker images, you are supposed to specify all the packages of the images or provide Dockerfile.

- Others...

## Step 2. Open an issue
If you are ready to submit your own dflow proposal to [dflow101](https://github.com/likefallwind/dflow101), you can open an issue [there](https://github.com/likefallwind/dflow101/issues). There is [an example](https://github.com/likefallwind/dflow101/issues/3) for your reference. In order to present all dflow101 issues more clearly to others, here are some rules you must follow.

- Title

Please open an issue with the title, dflow101_keyword 1_keyword 2_keyword 3, for instance, dflow101_electronic structure calculation_VASP_pymatgen.

As shown above, three keywords are supposed to describe your dflow proposal briefly. Moreover, the three key words are the relationship from the big aspect to the small aspect. Of course, you can use only two keywords or four keywords, which is up to you. But the keywords are supposed to be able to describe your dflow proposal to some degree.

- Comment

In the comment part, cover letter is required and the corresponding dflow repo link.


## Step 3. Response to reviewers
After you submit your dflow project, reviwers will give their suggestions and comments in the form of issues. And then you need to response to reviewers in the form of issues.


## Step 4. Pull request
Once your dflow project is ready to be published, you can add your dflow repo link in [dflow101 README.md](https://github.com/likefallwind/dflow101#dflow-projects) and pull request. 