### GitHub State and Local / Regulated Industries Newsletter – July 2025

This is a personally curated newsletter for my customers, focused on the most relevant updates and resources from GitHub this month. As your partner, my goal is to keep you informed on how our platform is evolving to meet the specific needs of state and local government.

Highlights for this month include **enhanced supply chain security** with new Dependabot capabilities, **customizable push protection rules**, and Copilot Coding Agent being **made available for Copilot Business users**. If you have any feedback or want to dive deeper into any topic, please let me know. Feel free to share this newsletter with others on your team as well.

### 🌟 Highlighted Update 🌟

* **Enhanced Supply Chain Security (`GA`)** – July brings significant improvements to dependency management and supply chain security. Dependabot now supports single pull requests for multi-ecosystem updates, reducing PR noise while improving security. New minimum package age configuration helps agencies ensure dependencies are battle-tested before adoption. Additionally, CodeQL now supports Rust in public preview, expanding security coverage for memory-safe applications. - [[Dependabot Updates]](https://github.blog/changelog/2025-07-01-dependabot-single-pull-request-for-multi-ecosystem-package-updates/) [[CodeQL for Rust]](https://github.blog/changelog/2025-07-01-codeql-for-rust-is-now-in-public-preview/)

---

### Copilot Updates

This month's updates focus on expanding access to powerful new features and providing administrators with better control and visibility.

#### Latest Releases
* **Anthropic Claude Sonnet 4 and Claude Opus 4 (`GA`)** – The latest Claude models are now generally available in GitHub Copilot, providing enhanced reasoning capabilities and code understanding for complex development tasks. - [[Read the Announcement]](https://github.blog/changelog/2025-06-25-anthropic-claude-sonnet-4-and-claude-opus-4-are-now-generally-available-in-github-copilot/)
* **Copilot Search on GitHub Docs (`GA`)** – GitHub documentation now includes Copilot-powered search capabilities, making it easier to find relevant information and examples when working with GitHub features and APIs. - [[Try Copilot Search]](https://github.blog/changelog/2025-06-30-copilot-search-now-on-github-docs/)
* **Copilot in Xcode Enhancements (`GA`)** – Xcode users now have access to Copilot Vision for visual code understanding, custom instructions for project-specific guidance, and locale response support for international development teams. - [[Xcode Updates]](https://github.blog/changelog/2025-06-30-github-copilot-in-xcode-explore-with-copilot-vision-custom-instructions-and-locale-response-support/)
* **Copilot Coding Agent for Business Users (`PREVIEW`)** – Previously limited to Enterprise plans, the powerful Copilot coding agent is now in preview for Copilot Business users. You can now assign issues to Copilot to autonomously work on a solution, create a branch, and open a pull request for review, all within its own secure cloud environment. - [[Read the Announcement]](https://github.blog/changelog/2025-06-24-github-copilot-coding-agent-is-now-available-for-copilot-business-users/)
* **Remote GitHub MCP Server (`PREVIEW`)** – The Model Context Protocol (MCP) server is now available remotely, enabling Copilot to access GitHub repository information and perform actions across your organization's repositories more effectively. - [[MCP Server Details]](https://github.blog/changelog/2025-06-12-remote-github-mcp-server-is-now-in-public-preview/)
* **Premium Model Billing Now in Effect (`GA`)** – As of June, the monthly premium request allowances for Copilot plans are now enforced. This provides predictability for your standard usage, which remains unlimited for core chat and completions, while giving you pay-as-you-go control over usage of more advanced models like Claude. You can monitor usage and set spending limits in your billing settings. - [[View the Billing Update]](https://github.blog/changelog/2025-06-18-update-to-github-copilot-consumptive-billing-experience/)
* **Larger Context in Copilot Chat (`PREVIEW`)** – Copilot Chat can now understand more of your conversation and accept larger pasted snippets of code and text. This enhancement allows for more complex questions and troubleshooting without breaking up your thoughts, making the chat experience much more powerful. - [[See the Improvement]](https://github.blog/changelog/2025-06-25-improved-attachments-and-larger-context-in-copilot-chat-in-public-preview/)

#### Copilot at Scale
* **GitHub Desktop Commit Message Generation (`GA`)** – GitHub Desktop 3.5 now includes generally available Copilot-powered commit message generation, helping development teams maintain consistent and descriptive commit histories across desktop workflows. - [[Desktop 3.5 Release]](https://github.blog/changelog/2025-06-24-github-desktop-3-5-github-copilot-commit-message-generation-now-generally-available/)
* **Copilot Spaces for Issues and Pull Requests (`PREVIEW`)** – Copilot Spaces now support working directly with issues and pull requests, enabling more comprehensive project management and code review workflows within the Spaces environment. - [[Spaces Updates]](https://github.blog/changelog/2025-06-19-copilot-spaces-now-support-issues-and-pull-requests-public-preview/)

#### Stay up to date on the latest releases
* [GitHub Copilot Changelog](https://github.blog/changelog/label/copilot/)
* [VS Code Copilot Changelog](https://code.visualstudio.com/updates/#_github-copilot)
* [Visual Studio Copilot Changelog](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes#github-copilot)
* [JetBrains Copilot Changelog](https://plugins.jetbrains.com/plugin/17718-github-copilot/versions/stable)
* [XCode Copilot Changelog](https://github.com/github/CopilotForXcode/blob/main/ReleaseNotes.md)
* [Eclipse Copilot Changelog](https://marketplace.eclipse.org/content/github-copilot#details)

---

### Security & Platform Updates

Key updates this month focus on giving you more granular control over your security policies, improving supply chain security, and enhancing on-premises performance and governance.

#### Supply Chain Security Enhancements
* **Dependabot Single Pull Request for Multi-Ecosystem Updates (`GA`)** – Dependabot can now consolidate updates across multiple package ecosystems into a single pull request, reducing notification noise and making dependency management more efficient for large codebases. - [[Read the Announcement]](https://github.blog/changelog/2025-07-01-dependabot-single-pull-request-for-multi-ecosystem-package-updates/)
* **Dependabot Minimum Package Age Configuration (`GA`)** – Security teams can now configure Dependabot to ignore updates for packages younger than a specified age, ensuring your agency only adopts well-tested dependencies that meet your stability requirements. - [[Configure Minimum Age]](https://github.blog/changelog/2025-07-01-dependabot-supports-configuration-of-a-minimum-package-age/)
* **Dependency Auto-Submission for NuGet (`GA`)** – The dependency submission API now supports NuGet packages, expanding automated dependency tracking for .NET applications commonly used in government environments. - [[NuGet Support Details]](https://github.blog/changelog/2025-07-01-dependency-auto-submission-now-supports-nuget/)

#### Security Analysis & Code Protection
* **CodeQL for Rust (`PREVIEW`)** – CodeQL static analysis now supports Rust in public preview, bringing security scanning to memory-safe applications increasingly adopted for security-critical government workloads. - [[CodeQL Rust Support]](https://github.blog/changelog/2025-07-01-codeql-for-rust-is-now-in-public-preview/)
* **Customizable Push Protection Patterns (`PREVIEW`)** - Security teams can now choose exactly which secret scanning patterns are included in push protection. This gives your agency the power to block a much wider and more specific set of secrets relevant to your internal tools, preventing them from ever being committed to your repositories. - [[Read the Announcement]](https://github.blog/changelog/2025-06-25-configuring-which-secret-scanning-patterns-are-included-in-push-protection-is-in-public-preview/)

#### Platform & Enterprise Features
* **Enhanced Artifact Management (`GA`)** – New bulk actions and advanced filtering for artifact attestations support software supply chain integrity requirements, making it easier to manage and verify the provenance of your builds. - [[Artifact Management Updates]](https://github.blog/changelog/2025-07-01-bulk-actions-and-filtering-for-artifact-attestations/)
* **Cost Center Management API (`GA`)** – New API endpoints enable programmatic management of cost centers, valuable for agencies tracking GitHub usage and costs across multiple departments and projects. - [[API Documentation]](https://github.blog/changelog/2025-07-01-cost-center-management-api/)
* **GitHub Enterprise Server 3.17 (`GA`)** – The latest on-premises release is now available. GHES 3.17 brings System for Cross-domain Identity Management (SCIM) into general availability for easier user lifecycle management. It also enhances code security with new standalone product offerings (Secret Protection & Code Security), and allows GitHub Apps to be owned at the enterprise level for simpler administration. - [[See the Release Notes]](https://docs.github.com/en/enterprise-server@3.17/admin/release-notes)
* **Standalone Security for Azure DevOps (`GA`)** – For agencies using Azure DevOps, you can now purchase **GitHub Secret Protection** and **GitHub Code Security** as standalone products. This brings GitHub's best-in-class security features, including CodeQL scanning and secret scanning push protection, directly to your Azure DevOps repositories. - [[Learn More]](https://devblogs.microsoft.com/devops/github-secret-protection-and-github-code-security-for-azure-devops/)

---

### Nicole's Notes

#### Did You Know? You Can Add Custom Instructions for GitHub Copilot

You can guide GitHub Copilot’s behavior in Copilot Chat by adding a `.github/copilot-instructions.md` file to your repository. This allows you to tailor suggestions to your project’s conventions without manually specifying context every time. Make Copilot Instructions part of a repository template when creating new repositories so that you can share best practices across your Organization!

📚 Learn more: [Custom Copilot Instructions in VSCode](https://code.visualstudio.com/docs/copilot/copilot-customization#_types-of-custom-instructions) | [Create a Repository Template](https://docs.github.com/en/enterprise-cloud@latest/repositories/creating-and-managing-repositories/creating-a-template-repository)

---

### Events & Education

#### GitHub Universe
Our annual two-day developer event returns to San Francisco on **October 28-29**, and you can also join virtually for free. This is your best opportunity to hear the latest product announcements, attend deep-dive sessions, and connect with the global developer community. **Super Early Bird Registration ends July 8th**, offering a $700 discount on in-person passes. - [[Register and Save $700]](https://githuniverse.com/pricing)

#### Upcoming Virtual Events
| Date | Event | Categories |
| :--- | :--- | :--- |
| July 8 | [Best Practices for Mastering GitHub Copilot Chat](https://developer.microsoft.com/en-us/reactor/events/25941/) | Copilot, AI, Visual Studio Code |
| July 30 | [Secure Your Code with GitHub: Advanced Security Activation Bootcamp for State and Local](https://msit.events.teams.microsoft.com/event/a0295860-16f2-4f3e-aeef-d9a567e2db84@72f988bf-86f1-41af-91ab-2d7cd011db47) | GitHub Advanced Security, Getting Started |

*Also, watch the [Copilot Fridays back catalog](https://resources.github.com/copilot-fridays-english-on-demand/): Prompt Fundamentals, Copilot for MLOps/Data Science, and more.*

#### On-Demand Events
* **[Scale GitHub Copilot: Governance, Enablement, and Reporting – On-Demand](https://github.ondemand.goldcast.io/on-demand/014b7829-28a2-4c62-bf18-ccd2a16c440e)**
* **[MCP with GitHub Copilot – On-Demand](https://github.ondemand.goldcast.io/on-demand/bb52e8a7-4c49-4417-aa99-ac958098dd65)**

---

### The GovTech Grapevine

* [PDFs are the tip of the spear for Code for America's new AI studio](https://statescoop.com/code-for-america-ai-pdf-accessibility-2025/) (StateScoop) – With new federal accessibility rules looming, government agencies are turning to AI to tackle the massive and tedious job of making thousands of PDF documents accessible to people with disabilities. Code for America has developed a new tool that uses a machine learning algorithm to automatically classify and help remediate these files, turning a manual chore into a manageable tech problem.
* [Senate kills off proposed moratorium on state AI law enforcement](https://statescoop.com/state-ai-moratorium-dies-senate/) (StateScoop) – In a nearly unanimous 99-1 vote, the U.S. Senate removed a controversial provision from a budget bill that would have blocked states from creating or enforcing their own AI-related laws for ten years. The move is being hailed as a major victory for state and local governments, preserving their authority to regulate AI and protect citizens from potential harms.
* [Budget and cyber pressures impede tech upgrades by state and local governments, finds EY survey](https://www.ey.com/en_us/newsroom/2025/06/budget-and-cyber-pressures-impede-tech-upgrades-by-state-and-local-governments-finds-ey-survey) (EY / StateScoop) – According to a new EY survey of 300 state and local IT leaders, the top priorities for this fiscal year are reducing costs (56%) and improving cybersecurity (54%). Modernizing legacy systems, while a long-term goal, is taking a backseat to these more immediate pressures, even as AI adoption has roughly tripled in the past five years.

If you have any questions or want to discuss these updates in detail, feel free to reach out. As always, I’m here to help you and your team stay informed and get the most value from GitHub.
