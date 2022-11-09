# python-app-azure-deployment

## Task 1 : To create application to save user data into database.
 For Repo - Use GitHub <br>
 For Infra as Code - Use Terraform<br>
 For Pipeline - Use Azure DevOps  (dev.azure.com)<br>

### SubTask 1 (Manual Creation)
- Create Account in Azure (portal.azure.com)
- Create Storage Account
- Create Service Principal


### SubTask 2 (Create Infrastructure using Terraform)

Using Terraform, Create Infrastructure that is required for this Project.
- SQL DB
- Azure Container Registry
- Azure Container Instance
- KeyVault
- Log Analytics WorkSpace


<img width="641" alt="Screenshot 2022-11-09 at 8 08 54 PM" src="https://user-images.githubusercontent.com/105220391/200930852-2364d611-fa19-4b8f-a2c1-bd725daa9ac3.png">

### SubTask 3 (Create Application)
1. Create a Simple UI ( Using Python Flask Application, BootStrap CSS & Jinja2 Template)
2. UI Should contain two fields ( Name, City) and Submit Button
3. Once Clicking on Submit Should save data into a Database 

<br>
<br>

## Instructions
1. Create a Branch in this repo, finish your coding & Raise a Pull Request
2. Create INSTRUCTIONS.md with full of instructions, steps and screenshots as required.
3. Follow best practises while writing terraform code. for ex: modules, naming conventions, locals, variables, tf.vars as needed
4. Use Azure DevOps YAML Pipelines

