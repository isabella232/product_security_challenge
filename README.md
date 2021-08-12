# The Zendesk Product Security Challenge

Hello friend,

We are super excited that you want to be part of the Product Security team at Zendesk. Please follow the below instructions on making a "private" fork and use that for your work 

## Getting Started

Please use the first option (Github Import) for cloning this repo and working on it. If this does not work, please use the "Manually" instruction set.

### Github Import

1. Login to Github with your account. Next to your profile there is the "+" button. Click that and then "Import Repository".  
![Importing a new repository](./screenshots/1_import.png)  
2. Paste this [repository URL](https://github.com/zendesk/product_security_challenge) in the clone URL field. Give your repository a name and set it to private. Press the `Begin Import` button.  
![Importing a new repository](./screenshots/1_import.png)  
3. Clone your new repo and happy coding! When you are ready, let your Zendesk contact know and they will tell you who to share your repository with.

### Manually

1. Create a new **private** repository in your Github profile. A name like "product_security_challenge_<your_name>" should be fine.
2. Clone this repository:  
`git clone --bare https://github.com/zendesk/product_security_challenge`
3. Change into the cloned directory:  
`cd product_security_challenge`
4. Push this into your private repository from Step 1:  
`git push --mirror https://github.com/<your_username>/product_security_challenge_<your_name>.git`
5. Change out of this directory and delete the `product_security_challenge` folder:  
`cd .. && rm -rf product_security_challenge`
6. Clone your private repo and make changes there.  
`git clone https://github.com/<your_username>/product_security_challenge_<your_name>.git`
7. Happy programming! When you are ready, let your Zendesk contact know and they will tell you who to share your repository with.


## The Challenge

Implement an easy, secure authentication mechanism that allows users to:
- Create an account
- Log in and log out
- Reset their password

We have created the basic boilerplate for you (which you are free to modify) and it is up to you to implement the server-side functionality and expand from there. There is no restriction on language, frameworks or implementation, however we ask that: 
- You consider the security challenges that come with any authentication mechanism and implement controls to protect against common attacks.
- You document the controls you have implemented and come to your interview prepared to justify these decisions.
- Your submission is linked to your GitHub account (i.e. the forked repository you created) and contains all the source code and clear documentation on how to run the application (a dockerized, packaged, or compiled submission is welcome, but not essential). 
- You have fun and hopefully learn something! Whilst we know this isn’t strictly a developer role, the ability to understand what goes into secure design and implementation is an important part of our job. The time it takes to complete this task will vary based on your previous experience, but we don’t want you up until 2am every night trying to get this done. We are looking for a submission that demonstrates your abilities and knowledge.
 
If you are having trouble, for whatever reason, please reach out to us! 

