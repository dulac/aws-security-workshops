# Module 2: Attack Simulation

In this module you will be configuring all the initial detective and remediation controls for your environment.  You'll be running the first of two CloudFormation templates which will automate the creation of some of these controls and then you will manaually configure the rest. Below is a visual representation of what you'll be configuring in your environment.

## Deploy the CloudFormation Template

To initiate the attack simulation you will need to run the module 2 CloudFormation template: 

Region| Launch
------|-----
US West 2 (Oregon) | [![Launch Module 2 in us-west-2](../images/launch-stack-button.png)](https://console.aws.amazon.com/cloudformation/home?region=us-west-2#/stacks/new?stackName=ThreatDetectionWksp-Attack&templateURL=https://s3-us-west-2.amazonaws.com/sa-security-specialist-workshops-us-west-2/02-attack-simulation.yml)

### Launch Instructions

1. Click the **Launch Stack** button above.  This will automatically take you to the console to run the template.  The file for the CloudFormation template (**01-environment-setup.yml**) is also available in the [templates](../templates/) folder if you'd like to download it and manually upload it to create a stack.
2. Leave everything on the next pages as the **Default** settings. 
3. Finally acknowledge the template will create IAM roles and click **Create**

![IAM Capabilities](../images/iam-capabilities.png)

This will bring you back to the CloudFormation console. You can refresh the page to see the stack starting to create. Before moving on, make sure the stack is in a **CREATE_COMPLETE** status as shown below.

![Stack Complete](../images/01-stack-complete.png)