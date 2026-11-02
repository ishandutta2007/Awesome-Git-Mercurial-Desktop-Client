# Awesome-Git-Mercurial-Desktop-Client

# Awesome Git & Mercurial Desktop Client

> A curated list of top Git and Mercurial desktop clients — both commercial/proprietary tools and open-source alternatives.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [Commercial / Proprietary Clients](#-commercial--proprietary-clients)
  - [Sourcetree](#sourcetree)
  - [GitKraken](#gitkraken)
  - [GitHub Desktop](#github-desktop)
  - [Tower](#tower)
  - [Fork](#fork)
  - [SmartGit](#smartgit)
  - [Sublime Merge](#sublime-merge)
- [Open-Source Software](#-open-source-software)
  - [Magit](#magit)
  - [TortoiseGit](#tortoisegit)
  - [SourceGit](#sourcegit)
  - [GitButler](#gitbutler)
  - [GitWand](#gitwand)
  - [Lazygit](#lazygit)
  - [TortoiseHg](#tortoisehg)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 Commercial / Proprietary Clients

Desktop Git clients that are free (sometimes with paid tiers) or commercially licensed. These are not open-source but are included as reference points for feature comparison.

### Sourcetree
**Platforms:** Windows, macOS | **License:** Free (proprietary)  
Atlassian's free Git and Mercurial GUI. Offers a clean visual interface for beginners while retaining power features like interactive rebase, Git-flow, Git LFS, and local commit search. Works seamlessly with Bitbucket and other hosting services [citation:3]. A solid choice for teams already in the Atlassian ecosystem.

### GitKraken
**Platforms:** Windows, macOS, Linux | **License:** Free tier / Paid (~$10/mo Pro)  
A full-featured commercial Git GUI with a polished visual graph, built-in merge conflict editor, interactive rebase, and AI-assisted commit messages. Integrates natively with GitHub, GitLab, Bitbucket, and Jira. The free tier covers public repos and basic workflows; Pro unlocks private repos and advanced features [citation:4][citation:13].

### GitHub Desktop
**Platforms:** Windows, macOS | **License:** Free (proprietary, source available)  
GitHub's official desktop client, designed to hide Git complexity. Clone, branch, commit, push, and open PRs with minimal friction. The ideal choice for beginners or teams whose repositories live entirely on GitHub. Limitations include a basic diff viewer and no interactive rebase [citation:5][citation:13][citation:15].

### Tower
**Platforms:** Windows, macOS | **License:** Paid ($69/yr Basic, $129/yr Pro)  
A premium native Git client known for polish and productivity features. Supports drag-and-drop, undo everything (⌘+Z), stacked branches, conflict wizard, interactive rebase, worktrees, and Git LFS. A favorite among professionals who want a finished, reliable daily driver [citation:6][citation:13].

### Fork
**Platforms:** Windows, macOS | **License:** Paid ($59.99 one-time)  
A fast, native Git client with a calm interface. Includes interactive rebase, worktrees, file history, Git-flow, and custom actions. No Linux build, and PR support is create-and-view rather than full review. A strong choice for developers who prefer a one-time purchase over subscriptions [citation:7][citation:13].

### SmartGit
**Platforms:** Windows, macOS, Linux | **License:** Free (non-commercial) / Paid (commercial)  
A mature Git and Mercurial client from Syntevo. Supports both version control systems natively, with a detailed file view, index editor for partial staging, and a Review layout. Free for non-commercial use; commercial licenses are available [citation:8].

### Sublime Merge
**Platforms:** Windows, macOS, Linux | **License:** Paid ($99 one-time, 3 years updates)  
Built on Sublime Text's custom toolkit, Sublime Merge is exceptionally fast and transparent. Its standout feature is the command log: every action shows the exact Git command it ran, making it a learning tool as well as a client. No PR workflow and no AI features, but unmatched speed on large repositories [citation:9][citation:13].

---

## 🟩 Open-Source Software

Self-hosted, community-driven alternatives. All listed projects offer source code you can inspect, modify, and build yourself.

### Magit
**Stack:** Emacs Lisp | **License:** GPL-3.0 | **Platforms:** Anywhere Emacs runs  
A complete Git porcelain inside Emacs. Magit is not just a GUI wrapper — it is deeply integrated into Emacs and allows experienced Git users to perform nearly all daily version control tasks without leaving the editor. Its keyboard-driven workflow has a learning curve, but for Emacs users it is often described as indispensable [citation:10].  
**Best for:** Emacs users and keyboard-centric developers who want Git deeply integrated into their editing environment.

### TortoiseGit
**Stack:** C++ / Windows Shell Extension | **License:** GPL-2.0 | **Platforms:** Windows  
A Windows Explorer extension that brings Git operations directly into the right-click context menu. Icon overlays show file status at a glance. Features include commit, log viewer, revision graph, blame, rebase, stash, bisect, and submodule management. Not a standalone application — it integrates into Windows Explorer [citation:11].  
**Best for:** Windows users who prefer working directly from File Explorer without a separate application window.

### SourceGit
**Stack:** C# | **License:** MIT | **Platforms:** Windows, macOS, Linux  
A modern Git GUI client written in C#. Provides a visual branch graph, commit history, diff viewer, and essential Git operations. Actively maintained and packaged for Debian (RFP pending). A clean, cross-platform open-source alternative to heavier commercial clients [citation:12].  
**Best for:** Developers seeking a straightforward, MIT-licensed GUI that works across all three major platforms.

### GitButler
**Stack:** Tauri + Rust | **License:** FSL → MIT | **Platforms:** Windows, macOS, Linux  
A newer client that rethinks the branching model with **virtual branches**: work on multiple streams simultaneously in one working directory, then assign hunks to branches after the fact and push them as stacked PRs. Funded and actively developed. The trade-off is that it adds its own state alongside your repository [citation:13].  
**Best for:** Developers who frequently juggle multiple changes at once and want a novel workflow for managing concurrent work streams.

### GitWand
**Stack:** Tauri 2 + Rust | **License:** MIT | **Platforms:** Windows, macOS, Linux  
A classic-workflow Git client with a focus on **automatic merge conflict resolution**. Its deterministic engine auto-resolves approximately 95% of trivial conflict hunks with confidence scores and an auditable decision trace. Also includes full DAG history, in-app PR review across four forges (GitHub, GitLab, Bitbucket, Azure DevOps), interactive rebase, worktrees, and submodules. Keeps no state of its own — your repo remains vanilla Git [citation:13].  
**Best for:** Teams and developers who want a complete classic client that eliminates the pain of recurring merge conflicts.

### Lazygit
**Stack:** Go | **License:** MIT | **Platforms:** Everywhere (terminal)  
A terminal UI for Git. Lazygit provides a fast, keyboard-driven interface for staging, committing, branching, rebasing, and resolving conflicts without leaving the terminal. Lightweight, cross-platform, and beloved by developers who live in the command line [citation:13].  
**Best for:** Terminal-centric developers who want visual Git feedback without a GUI application.

### TortoiseHg
**Stack:** Python / Windows Shell Extension | **License:** GPL-2.0 | **Platforms:** Windows, Linux (with file manager extensions)  
A graphical frontend for **Mercurial**, the distributed version control system. Like TortoiseGit, it integrates into the file manager with icon overlays and context menus. Includes a commit dialog, revision history, and repository explorer. Available in Debian/Ubuntu repositories [citation:2][citation:14].  
**Best for:** Mercurial users, particularly on Windows, who want a native file-manager-integrated client.

---

## 📊 Comparison at a Glance

| Client | License | Platforms | Mercurial Support | Best For |
|--------|---------|-----------|-------------------|----------|
| **Sourcetree** | Free (proprietary) | Win, Mac | ✅ | Atlassian/Bitbucket users |
| **GitKraken** | Free tier / Paid | Win, Mac, Linux | ❌ | Full commercial suite + AI |
| **GitHub Desktop** | Free (proprietary) | Win, Mac | ❌ | Beginners on GitHub |
| **Tower** | Paid | Win, Mac | ❌ | Polish + team workflows |
| **Fork** | Paid (one-time) | Win, Mac | ❌ | Fast, calm daily driver |
| **SmartGit** | Free non-commercial | Win, Mac, Linux | ✅ | Git + Mercurial in one |
| **Sublime Merge** | Paid | Win, Mac, Linux | ❌ | Raw speed + transparency |
| **Magit** | GPL-3.0 | Emacs | ❌ | Keyboard-driven Emacs users |
| **TortoiseGit** | GPL-2.0 | Windows | ❌ | Explorer-integrated Windows |
| **SourceGit** | MIT | Win, Mac, Linux | ❌ | Modern cross-platform OSS |
| **GitButler** | FSL → MIT | Win, Mac, Linux | ❌ | Virtual branches / stacked PRs |
| **GitWand** | MIT | Win, Mac, Linux | ❌ | Merge conflict resolution |
| **Lazygit** | MIT | Terminal | ❌ | Terminal users |
| **TortoiseHg** | GPL-2.0 | Win, Linux | ✅ | Mercurial users |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Git or Mercurial desktop client that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
