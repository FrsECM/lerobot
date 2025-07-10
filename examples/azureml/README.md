# AzureML training Pipeline
In this section, we'll create stuffs necessary to train in azureml.
In order to use it, well need azure-cli :
```bash
pip install azure-cli
az login # Log with your account in azure...
```

## Create environment
First you need to create the environment that will contains all necessary dependancies.
```
environments/
└── lerobot_env/
    ├── Dockerfile
    └── env.yaml
```
Modify the script **create_env.sh** in order to create your environment with azure_cli.