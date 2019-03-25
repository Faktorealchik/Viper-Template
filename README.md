# Viper-Template

### Usage
1. Run [`generamba setup`](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands#basic-generamba-configuration) in the project root folder. This command helps to create [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure) that define all configuration needed to generate code. You can modify this file directly in future.
2. Add template planned to use in the project to the generated [Rambafile](https://github.com/rambler-digital-solutions/Generamba/wiki/Rambafile-Structure). 
 ```bash
 {name: viper, git: 'https://github.com/Faktorealchik/Viper-Template'}
 ```
3. Run [`generamba template install`](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands#template-installation). All the templates will be placed in the '/Templates' folder of your current project.
4. Run [`generamba gen [MODULE_NAME] viper`](https://github.com/rambler-digital-solutions/Generamba/wiki/Available-Commands#module-generation) - It creates module with specific name from viper template.
