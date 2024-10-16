# Chef Essentials Workshop - Official Chef Training

**Product ID**: 20161
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: CHEFBC
**Vendor Code**: CM
**Vendor Name**: CPrime
**URL**: [Course Link](https://www.fastlaneus.com/course/cprime-chefbc)

## Objective
- Use Chef Resources to define the state of your system
- Write and use Chef recipes and cookbooks
- Automate testing of cookbooks
- Manage multiple nodes with Chef Server
- Create Organizations
- Bootstrap nodes
- Assign Roles to nodes
- Deploy nodes to environments
- Enable Chef’s search features with your automation
- Create acceptance and production environments

## Essentials
Students who have completed the self-paced Fundamentals of DevOps eLearning course have found it very helpful when completing this course.

## Audience
- IT Managers and Leaders
- Developers and Application Teams
- System Administrators
- IT Operations Staff
- Release Engineers
- Configuration Managers
- Anyone involved with IT infrastructure
- ScrumMasters
- Software Managers and Team Leads

## Outline
Chef Introduction



- Overview and expectations for the class
- The Chef Lab System Architecture
Group lab: Pre-built workstation

2. Using Chef Resources



- Using Chef to install packages on your virtual workstation
- Using the chef-client command
- Creating a basic Chef recipe file
- Defining Chef Resources
- Test and repair
Lab: The 'file' resource

3. Building Cookbooks



- Modify a recipe
- Collaboration and version control
- Generating a Chef cookbook
- Defining a Chef recipe that sets up a web server
Group exercise: Version Control

Lab: Set up Git

Lab: Setting up web servers

4. Chef client



- Locally applying multiple cookbooks' recipes with chef-client
- Applying a run list
- Including a recipe from within another recipe
Lab: Update the apache Cookbook

5. Testing Cookbooks



- Using Test Kitchen to verify your recipes converge on a virtual instance
- Reading the ServerSpec documentation
- Writing and execute tests
- Where do tests live?
Group exercise: Test configuration

Lab: Converge the kitchen

Lab: Commit your work
Lab: Testing Apache

6. Details About a System



- Managing large numbers of servers
- Capturing details about a system
- Using the node object within a recipe
- Using Ruby's string interpolation
- Updating the version of a cookbook
Lab: Update the Cookbook version

Lab: Node Details in the Webserver

Lab: Commit your work

7. Desired State and Data



- Cleaner recipes
- When to use a template resource
- Creating a template file
- Using ERB tags to display node data in a template
- Defining a template resource
- Using kitchen test on the "apache" cookbook
- Using chef-clientto apply the "apache" cookbook's "default" recipe
- Updating the "apache" cookbook's version for this patch=
- Committing the changes
Lab: Update the version

8. Local Workstation Installation



- Installing ChefDK on your laptop
- Executing commands to ensure everything is installed
- Installing a local editor like Atom
Lab: You will run the following commands and report their versions: $chef, $chef-client, $knife, $ohai, $berks, $kitchen, $foodcritic, $rubocop

9. The Chef Server



- Connecting to a Chef Server
- Managing Additional systems
- Managing User traffic
- Uploading cookbooks to a Chef Server
- Bootstrapping a node
- Managing a node via a Chef Server
- Hosted Chef
Lab: Uploading cookbooks and managing cookbook dependencies

10. Community Cookbooks



- Find cookbooks on the Chef supermarket
- Create a wrapper cookbook
- Example: load balancer
- Amazon EC2 instances
- Replace the existing default values
- Upload a cookbook to Chef Server
- Bootstrap a new node that runs the cookbook
Discussion: Can your teams benefit from the supermarket?

11. Managing Multiple Nodes



- Managing user traffic
- Bootstrapping and updating the run_list
- Running chef-client on a node
- Appending values to an attribute within a recipe
- Versioning cookbooks and uploading to Chef Server
Lab: Another new node

Lab: Test and update the load balancer

Lab: Run $berks install

Lab: Converging the cookbook

12. Roles



- Assigning, defining, and configuring
- The 'knife' role
- Verifying roles
- Roles for everyone
Lab: Define a web role

13. Search



- Update a Cookbook to Dynamically Use Nodes with the Web Role
- Describe the query syntax used in search
- Build a search into your recipe code
- Create a Ruby Array and Ruby Hash
- Update the myhaproxy wrapper cookbook


Lab: Updating, load balancing, uploading and running the new search-capable cookbook

14. Environments



- Keeping your infrastructure current
- Creating a production environment
- Creating an acceptance environment
- Deploying a node to an environment
- Updating a search query to be more exact
Lab: Set new nodes to production

Lab: Acceptance environment

Lab: Create a new environment file

15. Course wrap and further resources



- Beyond essentials
- Valuable reading
- Events and online resources
- Customizing Chef

## Summary
nan

## Course Duration
2 days

## Last Changed
2023-08-21T13:06:16.000Z
