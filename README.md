# Obsidian Folder Link

Have you ever wanted to link to a folder? This plugin adds a frequently requested feature to Obsidian.

**Features:**

-   Click on Folder Link reveals folder in navigation
-   Folder Links styling behaves like regular internal links in Reading Mode (resolved/unresolved)

## How to use

Add a `/` add the end of a regular internal link. If the folder exists it will be revealeled.

**Warning:** Renaming or moving a folder you already linked won't update those folder links (for now).

```markdown
[[MyFolder/]]
```

## Roadmap

(ordering is random)

-   Live Preview / Source Mode support
    -   resolved/unresolved styling
    -   folder suggestion box
-   Updating existing folder links on rename/move
    -   and warning on delete (similar to regular internal links)
-   _maybe:_
    -   provide option to instead of revealing folder in navigation open a index view in a tab/view that shows context of that folder
