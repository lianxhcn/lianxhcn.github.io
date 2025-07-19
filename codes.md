---
title: "特殊格式"
layout: page
---

参见 [just-the-docs: alerts](https://raw.githubusercontent.com/just-the-docs/just-the-docs-tests/refs/heads/main/docs/alerts.md) &rarr; [输出效果](https://github.com/just-the-docs/just-the-docs-tests/blob/main/docs/alerts.md)

## Alerts

This file is intended for browsing on the GitHub repo, to illustrate how GitHub's alerts look in light and dark mode.

Copied from [GitHub Docs](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#alerts):

> Alerts are a Markdown extension based on the blockquote syntax that you can use to emphasize critical information. On GitHub, they are displayed with distinctive colors and icons to indicate the significance of the content.
>
> Use alerts only when they are crucial for user success and limit them to one or two per article to prevent overloading the reader. Additionally, you should avoid placing alerts consecutively. Alerts cannot be nested within other elements.
>
> To add an alert, use a special blockquote line specifying the alert type, followed by the alert information in a standard blockquote. Five types of alerts are available:

```markdown
> [!NOTE]
> Useful information that users should know, even when skimming content.
```

输出效果为：

> [!NOTE]
> Useful information that users should know, even when skimming content.

> [!TIP]
> Helpful advice for doing things better or more easily.

> [!IMPORTANT]
> Key information users need to know to achieve their goal.

> [!WARNING]
> Urgent info that needs immediate user attention to avoid problems.

> [!CAUTION]
> Advises about risks or negative outcomes of certain actions.
```