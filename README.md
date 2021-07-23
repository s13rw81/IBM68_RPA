# IBM68_RPA
This is a workflow that i created using `Robotic Process Automation` and `UiPath`. The purpose of this project is to automate performing tasks on the `IBM68 platform`.

## About IBM68
Now defunct, [IBM68](https://www.ibm68.com/xml/#/login) is a fraudulent website and has no relation with [International Business Machines Corporation (IBM)](https://www.ibm.com/). It offered daily cash rewards for performing "tasks" on their platform. Tasks were generally, clicking on like and subscribe buttons on YouTube videos, the urls of which would be supplied to you.
To join this platform, you would need to be referred by an active member. You would need top make an initial upfront payment based on the number of tasks you wanted to perfrom. Each level had an associated amount for completing a task.

## About the Workflow
This is a simple workflow that does not use the Robotic Enterprise Framework(RE Framework) of UiPath.
The workflow collects "tasks" on the IBM68 platform and navigates to the YouTube URL and check if the color on the like and subscribe buttons are Gray and Red respectively. If they are, it will automatically click these buttons.

## Run this workflow
Start `UiPath`, on the *BackStage view* on the *Start Tab*, click on the *Clone or CheckOut* and paste the URL of this repository.