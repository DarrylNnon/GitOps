# GitOps
Practical understanding of GitOps in CICD Pipeline

![image](https://github.com/user-attachments/assets/015655aa-c01a-40b7-afea-f6f4f2a1930e)

## Agenda

![image](https://github.com/user-attachments/assets/5b7c2c8f-ef23-4f40-aab3-943814b16ba1)

### What is GitOps?
GitOps is an operational framework that take devOps best practices used for application development such as version control, collaboration, compliance, and CI/CD, and applies them to infrastructure automation.

GitOps is going to have this caracteriques:
- Describe the system Declaratively (I define what i want and the system is going to figure out how to achieve it)
- Use Git as source of thruth (am sugin git as a single source of thruth where i pull my code)
- Ensure my Actual State converges towards my Desired state (here i have to specify my desired state and a tool call argoCD will make sure that my current state reflete my desired state by continuously update my current state)
- Seaprate branch for each environment (I use it for security reason and control)

![image](https://github.com/user-attachments/assets/7673ad2c-f3ba-4bd7-b1e2-8952588b08cb)

#### GitOps CICD Pipeline (Pull based)

![image](https://github.com/user-attachments/assets/e10ccfa1-dc7a-4d83-bde5-e5d40aaee77e)

##### GitOps Operators
- Helm operator
- ArgoCD
- FluxCD
- Flagger
- Gitkube

I choose argoCD because of his facility to help me manage and troubleshooting thought the dasboard.

Note: Please find the full video explanation here:
![https://www.youtube.com/watch?v=lG_UflEQPlg]
