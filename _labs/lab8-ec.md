# Extra Credit - Lab 8 - Custom Patterns for Secret Scanning

We are just using the out of the box secret scanning settings. Perhaps you are interested in finding other patterns, such as credit card patterns, committed in the code.


## Exercise

Your assignment here is to implement a secret scanning custom pattern. You can start under the **Settings** --> **Advanced Security** page.

If you are looking for an example of what to search for, we suggest creating a pattern for finding a credit card! A developer may or may not have accidentally committed customer credit card numbers to the repository and we need to alert on this.

Create a pattern, run a dry-run, and hopefully you find the pattern! If so, save the custom secret scanning pattern to implement.


> [!TIP]
> AI can help you get started generating those pesky regular expressions using natural language.  Look for the **Generate with AI** button in the top right corner.
> For increased precision, you can check out [examples for custom patterns for secret scanning](https://github.com/advanced-security/secret-scanning-custom-patterns/tree/main?tab=readme-ov-file#personally-identifiable-information-pii), including a credit card example (under PII), in the [advanced-security/secret-scanning-custom-patterns](https://github.com/advanced-security/secret-scanning-custom-patterns/tree/main?tab=readme-ov-file#personally-identifiable-information-pii) repo!

## Summary

In this lab, you should have identified the credit card number that was accidentally committed. Custom secret scanning patterns offer an excellent way to implement additional scanning patterns that are crucial for your organization!

➡️ Head back to the [labs](README.md) page.
