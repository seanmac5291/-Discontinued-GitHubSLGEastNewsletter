# GitHub State and Local / Regulated Industries Newsletter – September 2025

This is a personally curated newsletter for my customers, focused on the most relevant updates and resources from GitHub this month. Highlights for August include **Gemini 2.5 Pro now generally available**, **GPT-4.1 Copilot model for code completion**, **Copilot code review GA in Xcode**, and **enhanced coding agent capabilities**. If you have any feedback or want to dive deeper into any topic, please let me know. Feel free to share this newsletter with others on your team as well.

### 🌟 Highlighted Update 🌟

* **GPT-4.1 Copilot Model for Code Completion (`GA`)** – GitHub Copilot code completion now uses the new GPT-4.1 Copilot model, which expands on GPT-4.1's coding capabilities with an extended knowledge cutoff and additional high-quality training data. The model has been refined with reinforcement learning to improve suggestion relevance based on user feedback. - [[GPT-4.1 Code Completion]](https://github.blog/changelog/2025-08-27-copilot-code-completion-now-uses-the-gpt-4-1-copilot-model/)

---

### Copilot Updates

August brought significant model improvements, expanded IDE support, and enhanced enterprise controls for GitHub Copilot.

#### Major Model Updates
* **Gemini 2.5 Pro Generally Available (`GA`)** – Google's most advanced Gemini model is now generally available in GitHub Copilot, showing strong reasoning and code capabilities with leading performance on coding, math, and science benchmarks. Available across all Copilot interfaces. - [[Gemini 2.5 Pro GA]](https://github.blog/changelog/2025-08-20-gemini-2-5-pro-is-generally-available-in-copilot/)
* **GPT-5 Preview Access** – OpenAI GPT-5 is now available in public preview for GitHub Copilot, offering enhanced reasoning capabilities for complex development scenarios. - [[GPT-5 Preview]](https://github.blog/changelog/2025-08-07-openai-gpt-5-is-now-in-public-preview-for-github-copilot/)

#### Enhanced IDE Support
* **Copilot Code Review GA in Xcode (`GA`)** – Copilot code review is now generally available in Xcode, allowing developers to review staged or unstaged changes directly within their editor to catch logic, security, and performance issues early. - [[Code Review Xcode GA]](https://github.blog/changelog/2025-08-27-copilot-code-review-generally-available-in-xcode-and-new-admin-control/)
* **New Enterprise Admin Controls** – Organizations now have dedicated control over Copilot code review with independent settings, seamless transitions, and the ability to manage CCR separately from other Copilot features. - [[Enterprise Admin Controls]](https://github.blog/changelog/2025-08-27-copilot-code-review-generally-available-in-xcode-and-new-admin-control/)

#### Coding Agent Enhancements
* **AGENTS.md Custom Instructions Support (`GA`)** – The Copilot coding agent now supports AGENTS.md custom instructions, allowing teams to guide Copilot on project understanding, build processes, testing, and validation approaches. Supports nested AGENTS.md files for specific project areas. - [[AGENTS.md Support]](https://github.blog/changelog/2025-08-28-copilot-coding-agent-now-supports-agents-md-custom-instructions/)
* **Enhanced Pull Request Reviews** – Coding agent capabilities for pull request reviews have been improved, providing more thorough and contextual feedback on code changes. - [[PR Review Improvements]](https://github.blog/changelog/2025-08-05-copilot-coding-agent-improved-pull-request-review-experience/)

#### Enterprise Features
* **Premium Request Overage Policy (`GA`)** – Better cost control and usage visibility for Copilot Business and Enterprise customers with the premium request overage policy now generally available. - [[Premium Request Policy]](https://github.blog/changelog/2025-08-22-premium-request-overage-policy-is-generally-available-for-copilot-business-and-enterprise/)
* **Data Residency Support** – Copilot coding agent is now available in GitHub Enterprise Cloud with data residency, providing enhanced compliance capabilities for regulated industries. - [[Data Residency Support]](https://github.blog/changelog/2025-08-27-copilot-coding-agent-is-now-available-in-github-enterprise-cloud-with-data-residency/)

#### Stay up to date on the latest releases
- [GitHub Copilot Changelog](https://github.blog/changelog/label/copilot/)
- [VS Code Copilot Changelog](https://code.visualstudio.com/updates/#_github-copilot)
- [Visual Studio Copilot Changelog](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes#github-copilot)
- [JetBrains Copilot Changelog](https://plugins.jetbrains.com/plugin/17718-github-copilot/versions/stable)
- [XCode Copilot Changelog](https://github.com/github/CopilotForXcode/blob/main/ReleaseNotes.md)
- [Eclipse Copilot Changelog](https://marketplace.eclipse.org/content/github-copilot#details)

---

### Security & Platform Updates

August delivered important security updates and enterprise platform improvements, particularly for GitHub Enterprise Server deployments.

#### GitHub Enterprise Server Updates
* **GHES 3.15 Security Releases** – Multiple security patches released for GitHub Enterprise Server 3.15, including versions 3.15.9 through 3.15.12, addressing various security vulnerabilities and performance improvements. - [[GHES 3.15 Release Notes]](https://docs.github.com/en/enterprise-server@3.15/admin/release-notes)
* **Critical Performance Fixes** – Performance issues identified in GHES versions 3.15, 3.16, and 3.17 have been addressed. Customers should upgrade to 3.15.12, 3.16.8, 3.17.5, or later for optimal performance.

#### Security Enhancements
* **Advanced Security Improvements** – Enhanced Dependabot auto-triage rules are now generally available for organization owners and security managers, providing automated dismissal of alerts matching specific criteria. - [[Dependabot Auto-triage]](https://docs.github.com/en/code-security/dependabot/dependabot-security-updates/about-dependabot-auto-triage-rules)
* **Audit Log Enhancements** – Improved audit logging capabilities for security configurations provide better visibility into changes at organization and repository levels.

---

### Nicole's Notes

#### Did You Know? GPT-4.1 Brings More Accurate Code Completions

The new GPT-4.1 Copilot model represents a significant improvement in code completion accuracy. This model has been specifically refined using reinforcement learning based on real user feedback, meaning it learns from how developers actually use and accept suggestions.

What makes this particularly valuable is the extended knowledge cutoff and additional high-quality training data. This means better understanding of newer frameworks, libraries, and coding patterns that weren't available in previous model versions.

You'll automatically see this model in your code completion model picker – no action required on your part. The improvements are most noticeable in complex code scenarios, API usage patterns, and when working with modern development frameworks.

📚 Learn more: [GPT-4.1 Code Completion](https://github.blog/changelog/2025-08-27-copilot-code-completion-now-uses-the-gpt-4-1-copilot-model/) | [Code Completion Documentation](https://docs.github.com/en/copilot/using-github-copilot/getting-code-suggestions-in-your-ide-with-github-copilot)

---

### Webinars, Events, and Recordings

#### GitHub Universe 2025 - Registration Open!
Our annual two-day developer event returns to San Francisco on **October 29-30**, and you can also join virtually for free. This is your best opportunity to hear the latest product announcements, attend deep-dive sessions, and connect with the global developer community. **Early bird registration is still available**. - [[Register for Universe]](https://githubuniverse.com/)

#### Upcoming Virtual Events
| Date | Event | Categories |
| :--- | :--- | :--- |
| September 17 | [GitHub Advanced Security Deep Dive](https://resources.github.com/events/) | GHAS, Enterprise |
| September 24 | [Scaling GitHub Copilot in the Enterprise](https://resources.github.com/events/) | Copilot, Enterprise |
| October 1 | [GitHub Actions Security Best Practices](https://resources.github.com/events/) | Actions, Security |

Also, watch the [Copilot Fridays back catalog](https://resources.github.com/copilot-fridays-english-on-demand/): Prompt Fundamentals, Copilot for MLOps/Data Science, and more.

#### Recently Recorded Events
* **[Advanced GitHub Copilot for Enterprise Teams – On-Demand](https://github.ondemand.goldcast.io/on-demand/)**
* **[Security at Scale with GitHub Advanced Security – On-Demand](https://github.ondemand.goldcast.io/on-demand/)**

---

### The GovTech Grapevine

* [Federal Agencies Accelerate Zero Trust Adoption](https://statescoop.com/) (StateScoop) – Federal agencies are making substantial progress on zero trust implementations, with 67% now having comprehensive identity and access management frameworks in place.
* [State CIOs Prioritize AI Governance Frameworks](https://www.govtech.com/) (GovTech) – State technology leaders are developing robust AI governance policies to ensure responsible adoption while maintaining citizen trust and regulatory compliance.
* [Local Government Digital Transformation Continues](https://statescoop.com/) (StateScoop) – Local governments are expanding digital service offerings, with emphasis on mobile-first citizen services and improved accessibility compliance.
* [Cybersecurity Workforce Development Shows Progress](https://www.govtech.com/) (GovTech) – Government agencies report improved success in cybersecurity recruitment and retention through targeted training programs and competitive compensation packages.

If you have any questions or want to discuss these updates in detail, feel free to reach out. As always, I'm here to help you and your team stay informed and get the most value from GitHub.