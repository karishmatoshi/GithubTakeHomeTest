**Company: Acme computers**

Version control platform(s): Many GitHub Enterprise instances installed throughout the company by different teams. Acme Computers is trying to standardize on GitHub Enterprise and consolidate their GitHub usage onto a single instance. The company has many instances of other Git hosting solutions installed as well. Some are fully supported applications. Other instances are on machines under people's desks.

**Customer requests:**

1) Shrink large repository: Acme wants GitHub to help them shrink the large repository to a more manageable size that is performant for common Git operations. The large repo is a project that is high visibility with an aggressive roadmap. They request that we help them within the month. It's a large, monolithic repository.

Answer: The repository can be refactored/optimized in different ways. Firstly, I will strat with doing review of files that are in the repository and then remove those that are unnecessary, e.g. database dumps, duplicate files, binaries. There might be also vendor code, which can be replaced by Git submodules. Lastly, the big repo can be splitted into small ones (this can be organized around business capabilities/functionalities). 

2) Consolidate instances: Acme wants you to tell them the best way to move all the other teams, using GitHub Enterprise or other Git solutions, onto their consolidated GitHub Enterprise instance. They have asked you to give them five or six bullet points about how you would approach that initiative, both technically and culturally.

Answer: 
Depending on the type of the repository, the migration to a consolidated GHE instance might have a different approach:

• Migration from other GHE Server instances - GitHub has excellent documentation on migrat content from one GitHub Enterprise Server instance to another: https://docs.github.com/en/enterprise-server@2.19/admin/user-management. This process allows for the migration of repos and other related data such as Teams:
In a migration, everything revolves around a repository. Most data associated with a repository can be migrated. For example, a repository within an organization will migrate the repository and the organization, as well as any users, teams, issues, and pull requests associated with the repository.

• Migration from non-GHE Sources - GITHUB importer can be used for the same. GITHUB has documented the steps to achieve the same : https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/importing-a-repository-with-github-importer

From Cultural perspective I will suggest the below points:
•	Schedule a presentation about GitHub Enterprise during working hours for all technical employees, with emphasis on why Git is better than other Version Control Systems and why particularly GHE is the best solution existing in 2018.
•	Prepare one-day session on how to use Git (beginners and advanced)
•	Prepare one-day session about GHE for developers, QA, and system administrators (introduction to GHE interface, Pull Request flow, integration with CI/CD)
•	Workshop where some volunteers from every team start migrating repositories to GHE
•	Q&A session, with emphasis on problems found and how they were solved

3) Migrate an SVN repo: The customer has one SVN repository that hasn't migrated over to a Git solution. They would like help moving this one large repository over. The team has a trunk based development pattern with this repository and is unfamiliar with Git.

Answer: 
The import can be done seanlessly. We can use GitHub Importer (https://docs.github.com/en/github/importing-your-projects-to-github/importing-source-code-to-github/importing-a-repository-with-github-importer) that will allows for seamless migration from Subversion to GitHub.

From the cultural perspective, I will recommend some learning Lab /workshop for the team members that will introduce them to the github and make them more confident.
