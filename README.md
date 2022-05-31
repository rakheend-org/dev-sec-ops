                        Qodana                  GHAS/CodeQL                     SemGrep                                     SonarQube
Code analysis                                                                           
Languages               Java, python, js        java, python, js, c#            Infrastucture               
                                                Go                              Docker, k8s, nginx, AWS, Terraform
Pre commit                                       
    Jetbrains           Y                       N                               Y
    VS Code             N                       CodeQL                          Y
    cli/docker          Y                       N                               N
commit trigger                                  N 
    GithubAction    
    Jenkins
    AzureDevops
Source control
    GithubAction    
    Jenkins
    AzureDevops
pr, schedule 
    GithubAction        Y                       Y 
    AzureDevops         Y                       N
    Jenkins             Y                       via Sarif*    
    SonarQube Sarif

SCA         
SAST
DAST

results
    Findings            Comprehensive           Comprehensive                   Untested                   ?
    Format              Sarif                   Sarif                               
   // Community           -                       Strong                          Y
    False positives

Issues                  Still EAP
                        No C# support

POCs
Links

Maturity                EAP                     
Community

Organisation
    Overview
    Audit
    Licence
    Pricing model
                             

Evaluation
Does it support programming languages my company uses?
Is it easy to hook into my CI systems? (Github actions. Gitlab, CircleCI, Jenkins, Azure DO AWS CodePipeline etc)
Am I going to have to manage a server that runs the tool?
Will I have to share access to source code?
Is it easy to extend/customize to my environment?






SCA 
Software Composition Analysis (SCA) is verification of the third-party libraries, frameworks and components used within your application; all of the code that you and your team did not write is considered by SCA tools.

SAST
SAST (Static Application Security Testing) is the automated analysis of written code (compiled or uncompiled) for security vulnerabilities.



SpectralOps
Veracode



|   | Qodana  | GHAS/CodeQL  |  SonarQube |   |
|---|---|---|---|---|
|Code analysis languages   |  Java, python, js |   |   |   |
|   |   |   |   |   |
|   |   |   |   |   |
