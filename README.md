# Advanced Terraform - FORK
This is the repository for the LinkedIn Learning course Advanced Terraform. The full course is available from [LinkedIn Learning][lil-course-url].

![Advanced Terraform][lil-thumbnail-url] 

Terraform simplifies and accelerates the configuration and deployment of infrastructure, including cloud-based environments. In this project-based course, David Swersky highlights a series of advanced Terraform use cases. David goes over the steps to create a new Terraform configuration, then explores intermediate concepts like variables, looping, expression and functions, modules, and more. He explains advanced concepts, such as custom modules, defining a remote state backend, and deploying configurations across multiple environments. The course is capped with an example model for a complete Continuous Integration/Continuous Delivery pipeline for deploying Terraform configurations.

## Instructions
This repository has branches for each of the videos in the course. You can use the branch pop up menu in github to switch to a specific branch and take a look at the course at that stage, or you can add `/tree/BRANCH_NAME` to the URL to go to the branch you want to access.

## Branches
The branches are structured to correspond to the videos in the course. The naming convention is `CHAPTER#_MOVIE#`. As an example, the branch named `02_03` corresponds to the second chapter and the third video in that chapter. 
Some branches will have a beginning and an end state. These are marked with the letters `b` for "beginning" and `e` for "end". The `b` branch contains the code as it is at the beginning of the movie. The `e` branch contains the code as it is at the end of the movie. The `main` branch holds the final state of the code when in the course.

When switching from one exercise files branch to the next after making changes to the files, you may get a message like this:

    error: Your local changes to the following files would be overwritten by checkout:        [files]
    Please commit your changes or stash them before you switch branches.
    Aborting

To resolve this issue:
	
    Add changes to git using this command: git add .
	Commit changes using this command: git commit -m "some message"


### Instructor

David Swersky 
                            
DevOps and enterprise architect

                            

Check out my other courses on [LinkedIn Learning](https://www.linkedin.com/learning/instructors/david-swersky).

[lil-course-url]: https://www.linkedin.com/learning/advanced-terraform-18720794?dApp=59033956
[lil-thumbnail-url]: https://media.licdn.com/dms/image/C560DAQGfrjsVMJJlFg/learning-public-crop_675_1200/0/1673639139822?e=2147483647&v=beta&t=Po6XcY4t4DcIZ__O-16BY24eHt0MPhPODwJl90L1rs0
