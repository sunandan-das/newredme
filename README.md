### PR Workflow Steps

1. I have created a `dev` branch → pushed changes to it
2. Raised PR → `dev` to `master`  
3. CI pipeline ran automatically:  
   - Restore, Build, Test, Docker Push  
4. If successful → PR approved  
5. On merge → CI re-ran on `master`  
6. CD pipeline deployed latest Docker image to App Service  
7. Live URL confirmed successful deployment

---

### CI/CD Architecture Diagram

![CI/CD Architecture](./images/ci-cd-architecture.png)

---

### Workflow Flowchart

![Workflow Steps](./images/pr-workflow-diagram.png)
