# GitHub State and Local / Regulated Industries Newsletter – August 2025

This is a personally curated newsletter for my customers, focused on the most relevant updates and resources from GitHub this month. Highlights for this month include **GitHub Spark for rapid app development**, **Agent Mode now available across all major IDEs**, **enhanced Copilot coding agent capabilities**, and **strengthened supply chain security with new secret scanning features**. If you have any feedback or want to dive deeper into any topic, please let me know. Feel free to share this newsletter with others on your team as well.

### 🌟 Highlighted Update 🌟

* **GitHub Spark (`PREVIEW`)** – Build and deploy web applications using natural language with GitHub Spark, now in public preview for Copilot Pro+ subscribers. This revolutionary tool allows you to create full-stack applications through conversational prompts, democratizing app development for your entire organization. - [[Learn About GitHub Spark]](https://github.blog/changelog/2025-07-23-github-spark-in-public-preview-for-copilot-pro-subscribers/)

---

### Copilot Updates

#### Latest Releases
* **GitHub Copilot App Modernization for .NET (`PREVIEW`)** – Modernize legacy .NET applications with AI assistance. Copilot now helps identify modernization opportunities and generates updated code patterns for your existing .NET systems. - [[.NET App Modernization]](https://github.blog/changelog/2025-07-21-github-copilot-app-modernization-for-net-enters-public-preview/)
* **Enhanced Copilot Activity Reporting (`GA`)** – New GitHub Copilot activity reports provide enhanced authentication insights and detailed usage analytics, giving administrators better visibility into adoption patterns and security posture across your organization. - [[Activity Report Details]](https://github.blog/changelog/2025-07-18-new-github-copilot-activity-report-with-enhanced-authentication-and-usage-insights/)
* **Model Context Protocol Support (`GA`)** – MCP support in VS Code is now generally available, enabling Copilot to access external tools and data sources for more comprehensive assistance. The coding agent also now supports remote MCP servers for enhanced capabilities. - [[MCP in VS Code]](https://github.blog/changelog/2025-07-14-model-context-protocol-mcp-support-in-vs-code-is-generally-available/) [[Remote MCP Servers]](https://github.blog/changelog/2025-07-09-copilot-coding-agent-now-supports-remote-mcp-servers/)
* **Copilot Chat on GitHub (`GA`)** – New Copilot Chat features are now generally available directly on GitHub, including enhanced context understanding and improved code suggestions within your browser workflow. - [[GitHub Chat Features]](https://github.blog/changelog/2025-07-09-new-copilot-chat-features-now-generally-available-on-github/)
* **GitHub Mobile Code Review (`GA`)** – Copilot code review is now generally available on GitHub Mobile, enabling AI-powered code reviews on the go for busy engineering managers and team leads. - [[Mobile Code Review]](https://github.blog/changelog/2025-07-09-copilot-code-review-now-generally-available-on-github-mobile/)

#### Improved IDE Feature Parity
* **Agent Mode Universal Availability**
    * **Agent Mode for JetBrains, Eclipse, and Xcode (`GA`)** – Agent mode is now generally available across JetBrains IDEs, Eclipse, and Xcode, bringing autonomous task execution to all major development environments. - [[Multi-IDE Agent Mode]](https://github.blog/changelog/2025-07-16-agent-mode-for-jetbrains-eclipse-and-xcode-is-now-generally-available/)
    * **Enhanced Eclipse Integration** – GitHub Copilot in Eclipse is now smarter, faster, and more integrated with improved code completions and chat functionality. - [[Eclipse Improvements]](https://github.blog/changelog/2025-07-22-github-copilot-in-eclipse-smarter-faster-and-more-integrated/)

#### Copilot at Scale
* **Custom Instructions Support** – The GitHub Copilot coding agent now supports `.instructions.md` custom instructions, allowing teams to define project-specific guidelines that the agent follows when implementing features and fixes. - [[Custom Instructions Guide]](https://github.blog/changelog/2025-07-23-github-copilot-coding-agent-now-supports-instructions-md-custom-instructions/)
* **Enhanced Agent Configuration** – New capabilities for the Copilot coding agent include configurable internet access, base branch selection for tasks, and optimized premium request usage (one request per session). - [[Internet Access Config]](https://github.blog/changelog/2025-07-16-configure-internet-access-for-copilot-coding-agent/) [[Base Branch Selection]](https://github.blog/changelog/2025-07-23-agents-page-set-the-base-branch-for-github-copilot-coding-agent-tasks/) [[Premium Request Optimization]](https://github.blog/changelog/2025-07-10-github-copilot-coding-agent-now-uses-one-premium-request-per-session/)

#### Stay up to date on the latest releases
- [GitHub Copilot Changelog](https://github.blog/changelog/label/copilot/)
- [VS Code Copilot Changelog](https://code.visualstudio.com/updates/#_github-copilot)
- [Visual Studio Copilot Changelog](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes#github-copilot)
- [JetBrains Copilot Changelog](https://plugins.jetbrains.com/plugin/17718-github-copilot/versions/stable)
- [XCode Copilot Changelog](https://github.com/github/CopilotForXcode/blob/main/ReleaseNotes.md)
- [Eclipse Copilot Changelog](https://marketplace.eclipse.org/content/github-copilot#details)

---

### Security & Platform Updates

Key updates this month focus on strengthening secret scanning capabilities, improving dependency management, and enhancing enterprise security controls.

#### Enhanced Secret Protection
* **Expanded Secret Scanning Validity Checks (`GA`)** – Secret scanning now includes validity checks for over 40 additional secret detectors, plus new support for Doppler and Defined Networking tokens. This reduces false positives and helps security teams focus on actual credential exposures. - [[40+ New Detectors]](https://github.blog/changelog/2025-07-22-secret-scanning-adds-validity-checks-for-over-40-secret-detectors/) [[Doppler & Defined Networking]](https://github.blog/changelog/2025-07-01-secret-scanning-adds-validity-checks-for-doppler-and-defined-networking/)
* **GitHub Apps Secret Scanning Integration (`GA`)** – GitHub Apps can now review secret scanning push protection bypass and alert dismissal requests, enabling automated workflows for security incident response and compliance tracking. - [[Apps Integration]](https://github.blog/changelog/2025-07-22-github-apps-can-now-review-secret-scanning-push-protection-bypass-and-alert-dismissal-requests/)

#### Code Security & Analysis
* **Delegated Alert Dismissal (`GA`)** – Code scanning delegated alert dismissal is now generally available, allowing security teams to designate trusted developers who can dismiss false positives without requiring direct admin intervention. - [[Delegated Dismissal]](https://github.blog/changelog/2025-07-01-delegated-alert-dismissal-for-code-scanning-is-now-generally-available/)
* **CodeQL Configuration Flexibility (`GA`)** – Security configurations now support running CodeQL in either default or advanced setup, giving organizations more control over their static analysis workflows. - [[CodeQL Configuration]](https://github.blog/changelog/2025-07-15-security-configurations-support-for-running-codeql-in-either-default-or-advanced-setup/)

#### Supply Chain & Dependencies
* **Centralized Dependabot Registry Configuration (`GA`)** – Centralized private registry configuration for Dependabot is now generally available, simplifying dependency management across large organizations with private package repositories. - [[Centralized Configuration]](https://github.blog/changelog/2025-07-22-centralized-private-registry-configuration-for-dependabot-is-now-generally-available/)
* **Python Dependency Auto-Submission (`GA`)** – Dependency auto-submission now supports Python packages, expanding automated dependency tracking for Python-based government applications. - [[Python Support]](https://github.blog/changelog/2025-07-08-dependency-auto-submission-now-supports-python/)

#### Enterprise & Platform Features
* **GitHub Actions M2 Pro Runners (`PREVIEW`)** – GitHub Actions now offers M2 Pro-powered hosted runners in public preview, providing enhanced performance for iOS and macOS application development workflows. - [[M2 Pro Runners]](https://github.blog/changelog/2025-07-17-github-actions-now-offers-m2-pro-powered-hosted-runners-in-public-preview/)
* **Enterprise-Level GitHub Apps (`GA`)** – GitHub Apps can now be owned at the enterprise level with new installation automation APIs, simplifying app governance across multiple organizations. - [[Enterprise Apps]](https://github.blog/changelog/2025-07-01-enterprise-level-access-for-github-apps-and-installation-automation-apis/)
* **Enhanced Repository Creation (`PREVIEW`)** – The improved repository creation experience is now available in public preview, streamlining the setup process for new projects with better templates and configuration options. - [[Repository Creation]](https://github.blog/changelog/2025-07-08-improved-repository-creation-experience-now-available-in-public-preview/)

---

### Nicole's Notes

#### Did You Know? You Can Set Custom Base Branches for Copilot Coding Agent Tasks

When using the GitHub Copilot coding agent to implement features or fix issues, you can now specify which branch the agent should use as its starting point. This is particularly valuable for organizations with complex branching strategies or when you want the agent to work from a specific release branch rather than main.

This capability, combined with custom instructions support, gives your team unprecedented control over how AI assistance integrates with your established development workflows and governance practices.

📚 Learn more: [Agents Page Base Branch Configuration](https://github.blog/changelog/2025-07-23-agents-page-set-the-base-branch-for-github-copilot-coding-agent-tasks/) | [Custom Instructions Documentation](https://github.blog/changelog/2025-07-23-github-copilot-coding-agent-now-supports-instructions-md-custom-instructions/)

---

### Events & Education

#### GitHub Universe
Our annual two-day developer event returns to San Francisco on **October 28-29**, and you can also join virtually for free. This is your best opportunity to hear the latest product announcements, attend deep-dive sessions, and connect with the global developer community. **Registration is still open** with early bird pricing available. - [[Register for Universe]](https://githubuniverse.com/)

#### Upcoming Virtual Events
| Date | Event | Categories |
| :--- | :--- | :--- |
| August 13 | [Spotlight on GitHub Advanced Security](https://developer.microsoft.com/en-us/reactor/series/S-1311/#registrationForm) | GHAS, Supply Chain Security |
| August 21 | [GitHub Roadmap Webinar, Q3 2025](https://resources.github.com/webcasts/github-roadmap-webinar-q3-americas-europe/) | Platform, GHAS, Copilot |


*Also, watch the [Copilot Fridays back catalog](https://resources.github.com/copilot-fridays-english-on-demand/): Prompt Fundamentals, Copilot for MLOps/Data Science, and more.*

#### On-Demand Events
* **[Scale GitHub Copilot: Governance, Enablement, and Reporting – On-Demand](https://github.ondemand.goldcast.io/on-demand/014b7829-28a2-4c62-bf18-ccd2a16c440e)**
* **[MCP with GitHub Copilot – On-Demand](https://github.ondemand.goldcast.io/on-demand/bb52e8a7-4c49-4417-aa99-ac958098dd65)**

---

### The GovTech Grapevine

* [States Rush to Implement AI Governance Before Federal Mandates](https://statescoop.com/states-ai-governance-federal-mandates-2025/) (StateScoop) – State governments are proactively developing AI governance frameworks ahead of anticipated federal regulations, with 15 states having enacted comprehensive AI oversight policies this year.
* [Cybersecurity Mesh Architecture Gains Traction in Local Government](https://www.govtech.com/security/cybersecurity-mesh-architecture-local-government) (GovTech) – Local governments are increasingly adopting cybersecurity mesh architectures to better protect distributed digital services and remote work environments.
* [Digital Equity Grants Show Mixed Results in Rural Areas](https://statescoop.com/digital-equity-grants-rural-broadband-2025/) (StateScoop) – New analysis reveals that while digital equity initiatives have improved broadband access, rural communities still face significant challenges in digital service adoption and digital literacy.
* [AI-Powered Fraud Detection Prevents $2.3B in Improper Payments](https://www.govtech.com/artificial-intelligence/ai-fraud-detection-improper-payments-2025) (GovTech) – State unemployment agencies using AI-powered fraud detection systems have prevented $2.3 billion in improper payments over the past 18 months, demonstrating the technology's value in protecting public resources.

If you have any questions or want to discuss these updates in detail, feel free to reach out. As always, I'm here to help you and your team stay informed and get the most value from GitHub.