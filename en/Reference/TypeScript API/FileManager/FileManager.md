---
alias: "obsidian.FileManager.md"
cssClass: hide-title
---

<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[`FileManager`](obsidian.FileManager.md)

## FileManager class

Manage the creation, deletion and renaming of files from the UI.

**Signature:**

```typescript
export class FileManager 
```

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [`generateMarkdownLink(file, sourcePath, subpath, alias)`](obsidian.FileManager.generateMarkdownLink.md) |  | Generate a markdown link based on the user's preferences. |
|  [`getNewFileParent(sourcePath, newFilePath)`](obsidian.FileManager.getNewFileParent.md) |  | Gets the folder that new files should be saved to, given the user's preferences. |
|  [`processFrontMatter(file, fn)`](obsidian.FileManager.processFrontMatter.md) |  | <p>Atomically read, modify, and save the frontmatter of a note. The frontmatter is passed in as a JS object, and should be mutated directly to achieve the desired result.</p><p>Remember to handle errors thrown by this method.</p> |
|  [`renameFile(file, newPath)`](obsidian.FileManager.renameFile.md) |  | Rename or move a file safely, and update all links to it depending on the user's preferences. |
