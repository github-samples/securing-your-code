# Extra Credit - Lab 7 - Advanced CodeQL Setup

We set up Code Scanning with CodeQL using the default method. Now, let's try using the **[advanced setup](https://docs.github.com/en/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning)**!

## Exercise

Why might you want to use the advanced setup? Here are some reasons:

- More control over triggers and schedule
- When pulling in packages from a private feed, you may have to provide instructions on authorizing to the NuGet, NPM, Maven, etc. feed.
- For compiled languages, providing more instructions on how to build the code
- Ability to customize the CodeQL configuration (such as query suites used)
- Manage code scanning settings "as code"
- Utilize 3rd party code scanning tooling

> [!NOTE]
> In case the reason why you need advanced setup is a private registry, be aware that you can configure one private registry per organization for [Code scanning default setup](https://docs.github.com/en/code-security/securing-your-organization/enabling-security-features-in-your-organization/giving-org-access-private-registries#code-scanning-default-setup-access-to-private-registries) for some package managers.

### Assignment

Your assignment here is to switch to the **[advanced setup](https://docs.github.com/en/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning)**. You can start under the **Settings** --> **Code Security** page.

Your goal is to have a CodeQL workflow committed that successfully scans your code. Pay attention to some of the configuration options for the CodeQL scanning action. Refer to the [documentation](https://docs.github.com/en/code-security/code-scanning/creating-an-advanced-setup-for-code-scanning/configuring-advanced-setup-for-code-scanning) for more details.

## Summary

In this lab, you have learned how to set up and configure advanced code scanning. There is no definitive answer as to whether the default or advanced setup is better. The default setup is ideal for quickly configuring CodeQL on repositories without requiring code changes or PR approvals. However, the advanced setup offers more customization and flexibility.

➡️ Head to the next [extra credit lab](lab8-ec.md).
