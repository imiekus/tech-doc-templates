# The Bug Report template guide
## Introduction

This template was created by Iga Miękus. Feel free to use it in your project. You can copy and paste it into your project documentation or use it as inspiration for your own idea.


## About Bug Report template

The [Bug Report template](https://github.com/imiekus/tech-doc-templates/blob/main/bug_report/template_bug_report.md) offers a consistent structure for documenting issues in a project, enabling both users and developers to quickly grasp the essential details needed to identify, replicate, and resolve bugs effectively.

Some sections in the template are marked as optional. However, for clarity, it's still recommended to fill them out if possible.

## Content of the template

### “Title” section

The title of a Bug Report should provide a concise yet descriptive name for the bug. It should be clear and specific, allowing others to quickly find it and understand the nature of the issue. A good title might include the affected feature, the type of problem, and any relevant context.

For example: "Login Page: Username field not accepting special characters".

### “Summary” section

The title of a Bug Report often can't capture all the nuances of an issue. Many bugs occur only under specific circumstances, and a summary helps provide this crucial context. This allows developers and managers to quickly grasp issues without needing to read through all the details. Keep it short but clear. Aim for 3-4 sentences that describe the problem well.

### “Environment” section

Environment details are vital for providing context about where a bug occurs. It should detail the hardware, software, and system configurations involved. This information is crucial for developers to:

- replicate the bug accurately
- identify platform-specific issues
- understand operational differences across systems.

Even if exact reproduction isn't possible, environment details can reveal key insights into system-specific behavior, guiding future development practices and bug resolution strategies.

### “Preconditions” section

Preconditions describe the initial state or setup required before the bug can be reproduced. This section is crucial for providing context and ensuring that the person attempting to reproduce the bug starts from the correct baseline. It may include:

- specific user roles or permissions
- data that needs to be present in the system
- particular system configurations or settings.

### “Steps to reproduce” section

Providing clear instructions for reproducing an issue is essential for developers to understand and replicate the problem. It should provide a clear, step-by-step guide that anyone can follow to consistently recreate the issue.

Be sure to mention any notable observations, such as unexpected outputs, visual anomalies, or unusual delays in processing. These details can be crucial for understanding and replicating the issue.

### “Expected result” section

This part of the template describes what should happen when the steps to reproduce are followed correctly. This helps clarify the intended functionality and provides a benchmark for comparing against the actual result. It's crucial to be specific and detailed in this section, as it sets the standard for what constitutes correct behavior in the system.

### “Actual result” section

This section describes what actually happened when the steps to reproduce were followed. It's crucial to provide a clear, detailed account of the observed behavior, including any error messages, unexpected outputs, or system responses. Be specific and objective in your description, avoiding assumptions or interpretations. If the actual result varies under different conditions, note these variations.

### “Proof” section

The "Proof" section is where you can provide tangible evidence of the bug. This might include screenshots, videos, error logs, or console outputs that clearly demonstrate the issue. Visual evidence can be particularly helpful for UI-related bugs, while logs or console outputs are valuable for backend issues.

Ensure that any sensitive information is redacted from the proof before sharing. When including logs or output, format them properly for readability.

### “Test data” section

The "Test data" section is where you provide specific information needed to reproduce the bug. This can include:

- user account details (use test accounts, not real user data)
- specific configuration settings
- input values or file samples.

Ensure all test data is anonymized and free of sensitive information.

### “Severity” section

The "Severity" section is crucial for prioritizing bug fixes and allocating resources effectively. It helps the development team understand the urgency and impact of the reported issue. When determining the severity of a bug, it's important to assess its overall effect on the system and users.

Classify the severity using a scale (e.g., Critical, High, Medium, Low) and provide a brief justification for the chosen severity level.

---
> Note that additional documentation templates are available in my [tech-doc-templates](https://github.com/imiekus/tech-doc-templates/tree/main) repository. This repository is a work in progress, with new templates being added regularly as needed. 
