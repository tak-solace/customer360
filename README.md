# Github Workflow configuration for Spring Cloud Stream with Asyncapi 
This repo will have the github workflow needed to plan, provision, and promote a Spring Cloud Stream application using Event Portal, Event Broker, and AsyncaPI 

## Things to note
- This workflow assumes an asyncapi.yml file in the root of the directory.
- Make sure github actions is enabled in your repo
  - Settings --> Actions --> General --> Allow all actions and reusable workflows
  - Settings --> Actions --> General --> Workflow permissions --> Enable read/write
- Confiure the secrets in your repo as per the [workflow files](.github/workflows)
- Edit this readme to match your project description
