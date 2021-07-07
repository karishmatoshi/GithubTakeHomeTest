**Company: Dunder Mifflin Technologies**

Version control platform(s): They currently use Gerrit, out-of-the-box Git, Subversion, and Team Foundation Server.

**Customer requests:**

1) Help us modernize our practices: Dunder Mifflin is worried they are falling behind their industry. They have lots of legacy software and development patterns that were created 20 years ago. They have found it incredibly difficult to change any aspect of their SDLC because of their infrastructure, processes, and long-tenured team members who are resistant to change.

Answer: Currently, this is the is the subject that many companies are struggling with. This is something with requires both technical and cultural change internally. GitHub understand how it is important for a company to improve their deliveries to keep in with the market competitions. In order to help with the same, Github recommend hosting a workshop led by our team members in order to demo our product offerings and how it can change their software development methodologies where they can deliver something pretty fast and with all modern tech. Also, help them define a roadmap to migrate their current stack to GHE.
Lastly, encourage your hiring managers to seek talent that fits the model you strive for, not the model you currently have. As you begin to bring new talent into the company, they will inevitably help disrupt the stagnant SDLC processes in place and push for more modern tech.

2) Help us release more often: Dunder Mifflin releases software four times a year. They are shipping largely web-based applications. They want to increase more frequently, but they are unsure of the best first steps. What areas would you explore with the customer to help them move this goal forward?

Answer: One of the fastest ways to increase your delivery speed is to have a devops culture in the team where they get introduced to the automation of the build and deployment with the CI/CD tools and integrating the ci/cd tools with other devops tools which will do the automated testing, automated security checks on the code developed. 
GITHUB is a very good tool for CI/CD implementation and there are other tools which can be checked in the market place and can be opted as per your needs. GITHUB as repository can be integrated with all major CI/CD tools in the market. GITHUB also have features such as code reviews and Pull requests which will enhance the complete automated solution around code check-in till its deliveries.

3) Commit/merge/deploy permissions: Dunder Mifflin has expressed concern about moving away from Gerrit. They have asked how they can control repository access, merging, and deployment permissions within GitHub, and what aspects of their desired security setup can be enforced programmatically.

Answer:
After the implementation of automated build and deployments by CI/CD, questions around access to code and deployments begin to fall into two primary groups: Repo Access and Automated Deployments.
Repo Access:
Access to repos can be managed by the use of the TEAMS feature provided by GITHUB and automation can be achieved around that via GITHUB API for modifying the addition and deletions of the users from the teams employees join and leave the company.
Automated Deployments:
GITHUB has two great features such as Branch Protection and Pull Requests that are great methods of ensuring the quality of code that makes it to your primary branch. The CI/CD pipelines can be triggered on the branching strategy with some checks around the successful code reviews of the PULL REQUESTS raised. Quality gates like test coverage or security scans can be added a pre-requisite in the ci/cd pipeline before code can be merged, even if the code has already been reviewed and approved.
