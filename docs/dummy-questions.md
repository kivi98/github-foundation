# GitHub Foundations Exam Practice Questions

1. What project management feature in GitHub can simply track the amount of open and closed tasks for a specific goal?

- [ ] GitHub Wiki
- [ ] GitHub Notifications
- [ ] GitHub Discussions
- [x] GitHub Milestones

2. What does forking a repo in GitHub do?

- [ ] It deletes the original repository
- [ ] It contributes your changes directly to the original repository
- [ ] It pins the repository to your GitHub homepage
- [x] It creates a personal copy of the repository in your account

3. Which Git command allows you to check out and create a new branch simultaneously?

- [ ] git branch new-branch
- [x] git checkout -b new-branch
- [ ] git merge new-branch
- [ ] git init new-branch

4. What are the differences between GitHub for individuals and GitHub Business?

- [x] GitHub Business provides SAML single sign-on support while GitHub Individual does not
- [ ] GitHub Individuals comes with a built-in CI/CD tool, while GitHub Business requires additional setup for CI/CD
- [ ] GitHub Individuals allow creating organizations, while GitHub Business does not
- [x] GitHub Business allows unlimited collaborators in private repositories, GitHub Individuals allows unlimited collaborators only in public repositories

5. Which type of GitHub repository is unique to GitHub Enterprise accounts?

- [x] Internal Repositories
- [ ] Forked Repositories
- [ ] Private Repositories
- [ ] Public Repositories

6. What best describes the use-case for Personal Access Tokens (PATs) in GitHub?

- [ ] For two-factor authentication during sign-in
- [ ] To encrypt repository data
- [x] Is a replacement for password authentication when using the GitHub API or Git over HTTPS
- [ ] To provide administrative access to all repositories in an organization

7. What CodeQL Analysis perform in GitHub?

- [ ] It monitors commit activity and contributor statistics
- [ ] It manages software workflows like building, testing, and deploying code
- [x] It automates the analysis of code for detecting vulnerabilities and errors
- [ ] It scans for sensitive information in the repository

8. Which three files can be automatically created during the initial creation of a GitHub repository? (Choose 3)

- [x] LICENSE
- [x] README.md
- [ ] CHANGELOG.md
- [ ] CONTRIBUTING.md
- [x] .gitignore

9. What are special profile badges that can be earned and appear on your GitHub Profile by completing certain objectives?

- [ ] Sponsor Badge
- [x] GitHub Achievements
- [ ] GitHub Stars Program Badge
- [ ] Contributor Badge

10. In a GitHub repository, where are Issue Forms templates stored?

- [ ] In the templates/issues/ directory
- [x] In the .github/ISSUE_TEMPLATE/ directory
- [ ] In the .github/ISSUE_FORMS/ directory
- [ ] In the docs/ directory

11. What best describes GitHub Copilot?

- [ ] It is GitHub's cloud-hosted CI/CD service
- [ ] It is GitHub's service for automating pull request reviews
- [ ] It is GitHub's repository dashboard for understanding project activity
- [x] It is GitHub's AI-powered code completion tool

12. Which GitHub cloning method requires the use of a Personal Access Token? (Choose 2)

- [x] GitHub CLI
- [ ] ZIP
- [x] HTTPS
- [ ] SSH

13. What does the on: attribute do in a GitHub Actions workflow file?

- [ ] It defines the location of the workflow file in the repository
- [ ] It indicates the time when the workflow should run
- [ ] It designates the programming language used in the workflow
- [x] It specifies the events that trigger the workflow

14. What is the difference between GitHub Codespaces and Github.dev?

- [ ] GitHub Codespaces is a real-time collaboration tool, while GitHub.dev is a version control system
- [ ] GitHub Codespaces is a full, cloud-hosted development environment, while GitHub.dev is an AI-powered code review tool
- [ ] GitHub Codespaces is a cloud-based code editor, while GitHub.dev is a full development environment hosted on the cloud
- [x] GitHub Codespaces provides a complete, configurable, and collaborative development environment in the cloud, while GitHub.dev is a lightweight, instant code editor available directly in the browser from any repository

15. How do you add a custom Readme page to your GitHub User Profile?

- [ ] Add a README.md file to the repository and commit it
- [ ] Turn on custom readme in Account Setting under user profile
- [x] Create a new repository with the same name as your GitHub username
- [ ] Enable GitHub Pages for the repository
- [ ] Submit a request to GitHub support for profile customization

16. Which light-weight version control workflow focuses on simplicity and effective use of branches and pull requests?

- [x] GitHub Flow
- [ ] Trunk-Based Development
- [ ] Continuous Integration (CI) Workflow
- [ ] Centralized Version Control

17. What configuration options can you set when you Launch a GitHub Codespace?

- [x] Choose the geographical location of the codespace's hosted server
- [ ] Preload the codespace with a selected region of the codebase
- [x] Set up specific packages and tools for the codespace
- [x] Define environment variables for the codespace
- [ ] Customize the color theme of the codespace's editor

18. What keyboard hotkey will instantly open up GitHub.dev Editor in a GitHub Repo?

- [ ] `,` (comma)
- [ ] `-` (hyphen)
- [ ] `/` (forward slash)
- [x] `.` (period)

19. What is the purpose of the CODEOWNERS file?

- [ ] To store passwords and API keys securely
- [ ] To manage permissions and access control of the repository
- [ ] To display the coding standards for the repository
- [x] To assign automatic review requests to certain team members when changes are made to parts of the codebase

20. What is the main feature of the Roadmap layout for GitHub Projects?

- [ ] It facilitates automated code reviews and pull request merges
- [ ] It provides an interactive Kanban board for managing issues and pull requests
- [x] It enables a Gantt chart view to visualize and plan tasks and deadlines in a timeline
- [ ] It allows to filter items by labels or milestones

21. When using GitHub's advanced search, which of the following syntax options correctly searches an organization for pull requests that contain information about payments?

- [x] org:organization_name is:pr payments
- [ ] user:organization_name pulls about:payments
- [ ] repo:organization_name/type:pulls payments
- [ ] organization_name/payments in:pulls

22. What are two ways you can collect payments via GitHub Sponsors? (Choose 2)

- [x] Direct Bank Transfer
- [x] Through GitHub.com
- [ ] Through Patreon
- [ ] By Mail

23. What best describes GitHub Projects?

- [ ] A leaderboard of the most popular repositories on GitHub
- [ ] A marketplace for buying and selling source code
- [x] A task management tool to plan and track work, using cards and columns
- [ ] A feature for hosting and sharing PDF documents

24. What is the use-case for Milestones on GitHub?

- [ ] To monitor the real-time activities in a repository
- [ ] To implement version control
- [x] To group together issues and pull requests for specific features or phases of work
- [ ] To bookmark repositories for easier access

25. What does the "base" branch in a pull request represent?

- [ ] The default branch of the repository
- [x] The branch into which the changes will be merged
- [ ] A backup branch that is rarely used or updated
- [ ] The branch containing the new changes to be merged

26. What is the difference between a GitHub Issues Template and a GitHub Pull Request Template?

- [ ] A GitHub Issues Template automatically resolves issues, and a Pull Request Template automatically merges pull requests
- [x] A GitHub Issues Template guides the creation of new issues, and a Pull Request Template guides the creation of new pull requests
- [ ] A GitHub Issues Template is for projects, and a Pull Request Template is for code
- [ ] A GitHub Issues Template is for public repositories, and a Pull Request Template is for private repositories

27. When creating private Gists on GitHub, in which way are they not completely secure?

- [x] They can be accessed by anyone who has the URL
- [ ] They are publicly visible on your profile
- [ ] They can be forked by any GitHub user

28. Which file is used to configure the developer environment such as programs installed or base docker image for GitHub Codespaces?

- [x] .devcontainer/devcontainer.json
- [ ] environment.json
- [ ] github/workflows/setup.yml
- [ ] github/init/setup.json

29. What is the purpose of the CONTRIBUTING file in a GitHub repo?

- [ ] It serves as a guide for future development plans
- [x] It outlines instructions and guidelines for contributing to the project
- [ ] It automatically adds contributors to the project

30. What GitHub feature allows users to use products or features that are available in beta?

- [x] GitHub Feature Preview
- [ ] GitHub Labs
- [ ] GitHub Beta Access

31. When exploring files in a GitHub repo, what hotkey can be quickly used to focus the search box to search through files?

- [x] T
- [ ] P
- [ ] . (period)

32. Which security feature of GitHub can you use to prevent pushing secrets to your repo?

- [x] Secret Scanning
- [ ] Dependency Graph
- [ ] CodeQL Analysis

33. What does Dependabot alerts do?

- [x] They notify you about outdated dependencies in your repository
- [ ] They notify you when your repository size exceeds quota
- [ ] They send notifications about failed build processes
- [ ] They send alerts about critical software runtime errors

34. How do you subscribe to a notifications thread in GitHub?

- [x] Click the "Subscribe" button on the right side of an issue or pull request page
- [ ] Leave a comment on the thread
- [ ] Fork the repository
- [ ] Use the "Watch" button at the top of the repository

35. What is the primary purpose of enabling Two-Factor Authentication (2FA) for your GitHub account?

- [x] To provide an extra layer of security by requiring a second form of verification besides your password
- [ ] To enable automated code merging in pull requests
- [ ] To customize the appearance and theme of your GitHub profile
- [ ] To increase the storage capacity of your repositories

36. What distinguishes GitHub Copilot for Business from GitHub Copilot for Individuals?

- [x] GitHub Copilot for Business is designed for enterprise-scale deployment and administrative controls, whereas GitHub Copilot for Individuals is for personal use
- [ ] GitHub Copilot for Business offers cloud-based storage, whereas GitHub Copilot for Individuals offers local storage only
- [ ] GitHub Copilot for Business allows code sharing, while GitHub Copilot for Individuals does not
- [ ] GitHub Copilot for Business includes project management tools, whereas GitHub Copilot for Individuals focuses on code completion

37. Which is NOT a role for GitHub Organization collaborators?

- [ ] Triage
- [x] Collaborator
- [ ] Admin
- [ ] Write

38. What is Markdown primarily used for on GitHub?

- [x] For writing formatted text in issues, pull requests, and files like READMEs
- [ ] For styling GitHub Pages with CSS
- [ ] For querying data in GitHub's database
- [ ] For scripting automated actions in GitHub Actions

39. Which feature in Git allows you to develop new features, fix bugs, or safely experiment with new ideas in isolated environments within the same repository?

- [ ] Commit History
- [ ] Staging Area
- [ ] Merge Requests
- [x] Git Branch

40. How can you start a GitHub Codespace? (Choose 2)

- [x] By selecting the 'New codespace' button at the top of a GitHub repository page
- [ ] By sending a request to GitHub support to set up a codespace for your repository
- [ ] By cloning the repository to your local machine and then migrating it to a codespace
- [x] By opening the repository and using the command palette to create a new codespace