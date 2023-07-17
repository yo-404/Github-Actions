# Github-Actions
This repo demonstrates the basic use of github actions in your repository to achieve CI/CD .

github actions is a convenient way to implement CI/CD on your project if your organization/team uses github actions as SCM tool .

## github vs Jenkins

- hosting: hosting is not required for github actions as it runs on your github repo whereas for jenkins you need your own server to run

- User interface : user interface is easy for github actions whereas for jenkins one may feel the interface a bit complex .Therefore , github actions is suited for simple to moderate automations tasks .Jenkins can be used for complex tasks

- Cost : Cost for github actions is free for public repositories whereas for private it charges the amount for the time compute resources has been used . In jenkins, you are solely responsible for run and maintain the server .

- Customization and plugins support : jenkins has a support for whole lot of plugins and addons , github actions is yet to reach that level and cannot be used for complex tasks .

- security - For an organization ,using github actions server can be a security concern as they do not have any knowledge of where the data goes and what resources are being used and if the data is also stored in the servers later on . This can be tackled by using your own self hosted server for testing and integration .

## Limitation 

- less community support when compared to jenkins and other leading CICD tools

- platform specific : it would be problematic if the organization plans to switch the platform since it is bound to github SCM platform

## conclusion

In conclusion, Jenkins is better suited for complex and large-scale automation tasks, while GitHub Actions is a more cost-effective and user-friendly solution for simple to moderate automation needs.