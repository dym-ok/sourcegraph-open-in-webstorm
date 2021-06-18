# Open in WebStorm Sourcegraph extension

Provides a button for the sidebar of the Sourcegraph app that will open the current file in [WebStorm](https://www.jetbrains.com/webstorm/).

Based on [sourcegraph/sourcegraph-open-in-intellij](https://github.com/sourcegraph/sourcegraph-open-in-intellij).

<picture>
<source srcset="https://user-images.githubusercontent.com/37420160/96809054-23450b80-13e8-11eb-8e76-a0556e3b41e6.png" media="(prefers-color-scheme: dark)" />
<source srcset="https://user-images.githubusercontent.com/37420160/96809032-16281c80-13e8-11eb-9b24-3787300ee66f.png" media="(prefers-color-scheme: light)" />
<img src="https://user-images.githubusercontent.com/37420160/96809032-16281c80-13e8-11eb-9b24-3787300ee66f.png" alt="Screenshot" />
</picture>

## Settings

- `openInWebstorm.basePath` - The absolute path on your computer where your git repositories live. This extension requires all git repos to be already cloned under this path with their original names. `"/Users/yourusername/src"` is a valid absolute path, while `"~/src"` is not.

