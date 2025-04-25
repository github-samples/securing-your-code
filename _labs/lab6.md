# Lab 6 - Hands-on with Security Overview

We've covered how to review alerts in a single repository, but how is your org or team doing? Next, we'll check out the Security Overview at the organizational level to see how we can get a high-level view of the security posture of our organization.

This lab covers parts of the following exam domains:

- Domain 6: Describe GitHub Advanced Security best practices

> [!NOTE] This lab is only available if you are using an organization as the owner of the repository.

## Exercise 1: Navigating to Security Overview

The Security Overview can be used by anyone inside of an organization; it shows repositories that **you** have access to. If you are an org owner or a security manager, you would see all alerts. If you are a regular org member, you would only see alerts for repositories by default that you have write access to.

> [!NOTE]
> Security alerts for a repository are visible to people with write, maintain, or admin access to the repository and, when the repository is owned by an organization, organization owners. You can give additional teams and people access to the alerts.

1. Navigate to the organization you created the repository for the lab. You can do so by **clicking on the org name** in the repository breadcrumbs in the upper left hand corner.
    - You can also navigate to your orgs by clicking on your profile picture and "**Your organizations**"
2. Click on the **Security** tab.
3. Review (and click on!) the different views on the left-hand side:
    - **Overview**: visualize trends in Detection, Remediation, and Prevention of security alerts ([docs](https://docs.github.com/en/enterprise-cloud@latest/code-security/security-overview/viewing-security-insights#about-security-insights))
    - **Risk**: explore the risk from security alerts of all types or focus on a single alert type and identify your risk from specific vulnerable dependencies, code weaknesses, or leaked secrets ([docs](https://docs.github.com/en/enterprise-cloud@latest/code-security/security-overview/assessing-code-security-risk))
    - **Coverage**: assess the adoption of code security features across repositories in the organization ([docs](https://docs.github.com/en/enterprise-cloud@latest/code-security/security-overview/assessing-adoption-code-security))
    - **Enablement trends**: see how quickly different teams are adopting security features
    - **CodeQL pull request alerts**: assess the impact of running CodeQL on pull requests and how development teams are resolving code scanning alerts ([docs](https://docs.github.com/en/enterprise-cloud@latest/code-security/security-overview/viewing-metrics-for-pull-request-alerts))
    - **Secret scanning**: find out which types of secret are blocked by push protection and which teams are bypassing push protection ([docs](https://docs.github.com/en/enterprise-cloud@latest/code-security/security-overview/viewing-metrics-for-secret-scanning-push-protection))

> [!TIP]
> You can export a CSV of nearly from most of these views using the **Export CSV** button in the upper right.

4. Under the **Overview** view, navigate the sub-views, specifically **Detection** and **Remediation**.
    - Note the trends - this is useful information to evaluate the security posture of your organization. Are we getting better over time?
    - Being secure requires "constant vigilance"
5. Navigate to the **Risk** view.
6. On the right-hand side, click the **Teams ▾** button/dropdown.
7. Click on the **all users** team - this team is only added to a different sample repo, so note how the total alerts changes.
    - This can be really useful for a manager, architect, or developer to see which repositories assigned to the teams have security features enabled and how many alerts they are generating.
8. At the bottom of the options on the left, you will see **Security Campaigns**.
    - Security campaigns are a new feature designed to help administrators and security managers create targeted campaigns and track remediation progress effectively.
9. ⚠️ Please don't create a new security campaign as to not introduce noise to your fellow attendees ⚠️

> [!TIP] If your If your company is using GitHub Enterprise or GitHub Teams plan and is not yet using GitHub Secrets Protection, you can run a [secret risk assessement](https://docs.github.com/en/code-security/securing-your-organization/understanding-your-organizations-exposure-to-leaked-secrets/about-secret-risk-assessment) at no cost to understand exposure to data leaks and to get an overview of your organization's secret leak footprint. 

## Summary

That's the security overview! Use these views to monitor and manage your security posture effectively. By leveraging the detailed insights provided in each section, you can identify potential threats, take proactive measures, and ensure your systems remain secure.

If you want to learn more about the security overview or about what a particular view shows, check out the [docs](https://docs.github.com/en/enterprise-cloud@latest/code-security/security-overview/about-security-overview)!

Congrats, you have finished all of the main labs! 🎉 If you have time or are up for a challenge, try out the extra credit labs!

➡️ If you want, you can now head to the first [extra credit lab](lab7-ec.md).

