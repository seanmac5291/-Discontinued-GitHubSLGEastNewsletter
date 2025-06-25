### GitHub State and Local / Regulated Industries Newsletter – July 2025

This is a personally curated newsletter for my customers, focused on the most relevant updates and resources from GitHub this month. As your partner, my goal is to keep you informed on how our platform is evolving to meet the specific needs of state and local government.

Highlights for this month include the last chance for **GitHub Universe Super Early Bird pricing**, the general availability of **GitHub Enterprise Server 3.17**, and new **customizable push protection rules** to enhance your security posture. If you have any feedback or want to dive deeper into any topic, please let me know. Feel free to share this newsletter with others on your team as well.

### 🌟 Highlighted Update 🌟

* **GitHub Universe 2025: Super Early Bird Ends July 8th!** – Our annual two-day developer event returns to San Francisco on **October 28-29**, and you can also join virtually for free. This is your best opportunity to hear the latest product announcements, attend deep-dive sessions, and connect with the global developer community. **Super Early Bird Registration ends July 8th**, offering a $700 discount on in-person passes. - [[Register and Save $700]](https://githubuniverse.com/pricing)

---

### Copilot Updates

This month's updates focus on expanding access to powerful new features and providing administrators with better control and visibility.

#### Latest Releases
* **Copilot Coding Agent for Business Users (`PREVIEW`)** – Previously limited to Enterprise plans, the powerful Copilot coding agent is now in preview for Copilot Business users. You can now assign issues to Copilot to autonomously work on a solution, create a branch, and open a pull request for review, all within its own secure cloud environment. - [[Read the Announcement]](https://github.blog/changelog/2025-06-24-github-copilot-coding-agent-is-now-available-for-copilot-business-users/)
* **Premium Model Billing Now in Effect (`GA`)** – As of June, the monthly premium request allowances for Copilot plans are now enforced. This provides predictability for your standard usage, which remains unlimited for core chat and completions, while giving you pay-as-you-go control over usage of more advanced models. You can monitor usage and set spending limits in your billing settings. - [[View the Billing Update]](https://github.blog/changelog/2025-06-18-update-to-github-copilot-consumptive-billing-experience/)
* **Larger Context in Copilot Chat (`PREVIEW`)** – Copilot Chat can now understand more of your conversation and accept larger pasted snippets of code and text. This enhancement allows for more complex questions and troubleshooting without breaking up your thoughts, making the chat experience much more powerful. - [[See the Improvement]](https://github.blog/changelog/2025-06-25-improved-attachments-and-larger-context-in-copilot-chat-in-public-preview/)

#### Stay up to date on the latest releases
* [GitHub Copilot Changelog](https://github.blog/changelog/label/copilot/)
* [VS Code Copilot Changelog](https://code.visualstudio.com/updates/#_github-copilot)
* [Visual Studio Copilot Changelog](https://learn.microsoft.com/en-us/visualstudio/releases/2022/release-notes#github-copilot)
* [JetBrains Copilot Changelog](https://plugins.jetbrains.com/plugin/17718-github-copilot/versions/stable)

---

### Security & Platform Updates

Key updates this month focus on giving you more granular control over your security policies and improving on-premises performance and governance.

* **Customizable Push Protection Patterns (`PREVIEW`)** - Security teams can now choose exactly which secret scanning patterns are included in push protection. This gives your agency the power to block a much wider and more specific set of secrets relevant to your internal tools, preventing them from ever being committed to your repositories. - [[Read the Announcement]](https://github.blog/changelog/2025-06-25-configuring-which-secret-scanning-patterns-are-included-in-push-protection-is-in-public-preview/)
* **GitHub Enterprise Server 3.17 (`GA`)** – The latest on-premises release is now available. GHES 3.17 brings System for Cross-domain Identity Management (SCIM) into general availability for easier user lifecycle management. It also enhances code security with new standalone product offerings (Secret Protection & Code Security), and allows GitHub Apps to be owned at the enterprise level for simpler administration. - [[See the Release Notes]](https://docs.github.com/en/enterprise-server@3.17/admin/release-notes)
* **Standalone Security for Azure DevOps (`GA`)** – For agencies using Azure DevOps, you can now purchase **GitHub Secret Protection** and **GitHub Code Security** as standalone products. This brings GitHub's best-in-class security features, including CodeQL scanning and secret scanning push protection, directly to your Azure DevOps repositories. - [[Learn More]](https://devblogs.microsoft.com/devops/github-secret-protection-and-github-code-security-for-azure-devops/)

---

### Nicole's Notes

#### Did You Know? You Can Secure Your Supply Chain Directly in Your Pull Request.

A common challenge for government agencies is ensuring that every new piece of code doesn't introduce a vulnerable open source dependency. Manually checking licenses and vulnerabilities for every change is impossible at scale.

This is where the **Dependency Review Action** comes in. You can configure this GitHub Action to run automatically on every pull request. It scans for dependencies being changed, added, or removed and checks them against your defined policies. It will flag any packages with known vulnerabilities or non-compliant licenses (like copyleft licenses) *before* they are merged into your main branch. It’s a powerful, automated control that hardens your software supply chain, a key requirement for secure development.

📚 Learn more: [About the Dependency Review Action](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/about-dependency-review) | [Configuring Dependency Review](https://docs.github.com/en/code-security/supply-chain-security/understanding-your-software-supply-chain/configuring-dependency-review)

---

### Events & Education

#### Upcoming Virtual Events
| Date | Event | Categories |
| :--- | :--- | :--- |
| July 11 | [GitHub Copilot for Educators](https://resources.github.com/events/github-copilot-for-educators-emea-amer/) | Copilot, Education, AI |
| July 16 | [Florida Digital Government Summit](https://events.govtech.com/florida-digital-government-summit.html) | GovTech, Digital Services, AI |
| July 24 | [Texas Digital Government Summit](https://events.govtech.com/texas-digital-government-summit.html) | GovTech, Security, Cloud |

*Also, watch the [Copilot Fridays back catalog](https://resources.github.com/copilot-fridays-english-on-demand/): Prompt Fundamentals, Copilot for MLOps/Data Science, and more.*

#### Where is my GitHub team this month?
* **Denver, CO – Oct 12-15** – [NASCIO Annual Conference](https://www.nascio.org/events/annual-conference/) - *Note: The NASCIO Annual Conference, a key event for State CIOs, is in October, not July. It's a great event to plan for!*

---

### The GovTech Grapevine

* [State Lawmakers Push Back on Federal Proposal to Limit AI Regulation](https://statescoop.com/state-lawmakers-push-back-federal-proposal-limit-ai-regulation/) (StateScoop) – Over 260 state legislators are opposing a federal 10-year moratorium on state-level AI laws, arguing for the need to address local concerns around AI harms and governance.
* [Arizona is Building on its Mobile Driver's License Program](https://statescoop.com/video/arizona-is-building-on-its-mobile-drivers-license-program/) (StateScoop) – A look at how Arizona is expanding its successful mobile ID program to serve as a foundational credential for accessing a wide range of state services online.

If you have any questions or want to discuss these updates in detail, feel free to reach out. As always, I’m here to help you and your team stay informed and get the most value from GitHub.