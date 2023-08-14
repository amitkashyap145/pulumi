Infrastructure as Code (IaC) is the process of managing and provisioning computer data centres through machine-readable definition files, rather than physical hardware configuration or interactive configuration tools. It's the practice of treating your infrastructure like you would treat your code. Meaning, you can check in the definition files in a source control system, review it, version it and it produces the same environment every time it is used.

## Pulumi is a Modern Infrastructure as Code with which you can create, deploy and manage infrastructure on any cloud using familiar programming languages and tools.

### Pulumi supports these programming languages: Go, Python, JavaScript, TypeScript, C#, F# and Visual Basic (.NET Core)

### Why Pulumi?
Some reasons I think Pulumi is great:

1. Programming model - You can write your infrastructure like you write your code in a programming language and tools of your choice This is HUGE. Having the flexibility to provision your infrastructure with your preferred programming language is a big productivity boost. On top of that you can bring in the same software development practices and principles like composition, abstraction, testability etc. for your infrastructure and use the favourite tools you are accustomed to, such as IDEs etc.

2. Familiar tools
IDEs, refactoring, testing tools, package management etc. Improves productivity from the get go
3. Configuration Management
4. Testability
With the power of programming language you can actually test your infrastructure like you would for your code. No one is stopping you to bring back the TDD from dead, if you will ;)
Faster feedback loop With programming language, testability and ability to preview the plans before you actually update/apply your changes comes very handy while writing the infrastructure code.
4. Multi cloud support
Pulumi allows you to provision resources in multiple clouds and SaaS services. Even though you will be writing separate code for targeting to different clouds (providers) but you can have all of them in a single solution/project at one place. On top of that, you can have your entire end-to-end across clouds and SaaS infrastructure in a single place that you can check in your source code repository in GitHub.
Some important command used in Pulumi are :
1. pulumi login
2. pulumi logout
3. pulumi logs
4. pulumi status
5. pulumi whoami
6. pulumi refresh
7. pulumi stack output
8. pulumi config remove <key>
9. pulumi config get <key>
10. pulumi config set <key> <value>
11. pulumi stack select <stack_name>
12. pulumi stack init <stack_name>
13. pulumi new template-name (e.g pulumi new aws-python)
14. pulumi preview
15. pulumi up
16. pulumi up --yes
17. pulumi destroy
    
![image](https://github.com/amitkashyap145/pulumi/assets/92769132/fc03b69e-63da-4a0b-906d-12aa4734fdd1)

