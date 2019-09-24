# Packer

![Image description](https://image.slidesharecdn.com/coscup2017-infrastructureascode-smalltown-170805070201/95/coscup-2017-infrastructure-as-code-21-638.jpg?cb=1501916793)

What is Packer?
* Packer is an open source tool that creates ideantical machine images for multiple platforms from a single source configuration
* Packer runs on every OS
* The machine images it creates contain pre-configured OS and installed software that can be used to quickly create new running machines

Why use Packer?
* Packer allows you to automate the building of machine images
* You can spin up pre-configured machines in an instant
* Fast infrastructure deployment, multi-provider capability, stability, and testability

A couple basic Packer commands:
* packer validate packer.json -- checks that the template is valid
* packer build packer.json -- builds the machine image from the template provided
* packer build -var 'base_ami=ami-1234' packer.json -- allows the user to enter their own values for variables listed in the template

Refer to https://www.packer.io for installation details and further information about getting started with Packer.