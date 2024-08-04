# Blossom File Organizer

_Under development_

Ever felt confused about where you stored your files or where to store them? Maybe you downloaded files you wanted to keep into the downloads folder and accidentally cleared it and lost the files you wanted to keep? That for sure has happened to me, and that is why I started working on this project.

# Blossom File Organizer - Base version

I have chosen to make the base version as minimal as possible to minimize on the things included that you don't want. I have used products like Obsidian.md and others which I believe are great but they include many features I don't like or need and therefore I don't want to do that to you. Use the base version together with whatever plugins you want to use based on the features you want and need.

## Features included in the base version

### File management

- **Basic sorting and organizing:**

  - Organize files by name and filetype.
  - Move, copy, delete, and rename files.

- **Folder structure:**
  - Create, delete, and rename folders.
  - Support for nested folders.

### Search functionality

- **Search:**
  - Basic search functionality to find files by name.

### Configuration

- **User Settings:**
  - Basic configuration options for user preferences like customized sort phrases, tags, or names.
  - Save and load user settings.

# Plugins (Not yet implemented)

## Features included with plugins

### [PowerRename](https://github.com/pontushenriksson/blossom-powerrename)

A plugin that helps you rename a file to a better suitable name based on my styleguide.

### [NeuroSort](https://github.com/pontushenriksson/blossom-neurosort)

A plugin helping you to sort files based on their connection to other files. This could for example utilize metadata.

### [LexiSort](https://github.com/pontushenriksson/blossom-lexisort)

A plugin helping you to sort files based on a lexicon or dictionary you created.

### [ArchiFile](https://github.com/pontushenriksson/blossom-archifile)

A plugin with comprehensive archiving functionality for archiving files. This could be used together with `FileSense` to automatically archive files that seem to not have been used in a long time.

> [!IMPORTANT]
> Requires FileSense

### [CogniPulse](https://github.com/pontushenriksson/blossom-cognipulse)

A plugin that organizes files dynamically based on usage. This could be set up to utilize a folder structure based on usage.

### [ChronoFile](https://github.com/pontushenriksson/blossom-chronofile)

A plugin that handles metadata related to time, for example when a file was created and last modified. This plugin is basic but not in the core app since some might not want to share that due to privacy reasons.

### [SizeInsight](https://github.com/pontushenriksson/blossom-sizeinsight)

A plugin that handles metadata related to data size and how it changed over the last modification.

### [UsageStats](https://github.com/pontushenriksson/blossom-usagestats)

A plugin that displays the size of files and folders and how it has changed over time. It also maps out the distribution of file types across directories, helping users understand their file composition.

> [!IMPORTANT]
> Requires SizeInsight

### [FileSense](https://github.com/pontushenriksson/blossom-filesense)

A plugin that determines whether a file is in use or it should be archived based on a specific algorithm and data gathered from `ChronoFile`.

> [!IMPORTANT]
> Requires ChronoFile

### [FileMinder](https://github.com/pontushenriksson/blossom-fileminder)

A plugin that could remind users of where a file is located.

### [Medula](https://github.com/pontushenriksson/blossom-medula)

A plugin that could create reminders and remind users about activities.

### [Activities](https://github.com/pontushenriksson/blossom-activities)

A plugin that could create to-dos. This plugin could work better with `Medula`.

> [!IMPORTANT]
> Requires Medula

### [StabiliFile](https://github.com/pontushenriksson/blossom-stabilifile)

Creates systematic backups of the whole structure so if something goes wrong, all or most of the content could be retrieved. This works as a backup system and could be great if you later want to switch to another device. This also stores your latest config file.

### [FileSync](https://github.com/pontushenriksson/blossom-filesync)

A plugin which helps synchronizing files across devices.

### [SecureVault](https://github.com/pontushenriksson/blossom-securevault)

A plugin which helps secure your folders and data. This will automatically password protect your information including your config file, backups and more.

### [AccessControl](https://github.com/pontushenriksson/blossom-accesscontrol)

A plugin that allows users to set access permissions for individual files and folders. Supports role-based access control to manage permissions for different user roles.

> [!IMPORTANT]
> Requires SecureVault

### [SecurityMonitoring](https://github.com/pontushenriksson/blossom-securitymonitoring)

A plugin that saves how many times the files/folders have been opened and what time to let users check if any unauthorized users have checked their files while they have been gone.

> [!IMPORTANT]
> Requires SecureVault

### [DupliCheck](https://github.com/pontushenriksson/blossom-duplicheck)

A plugin that helps users check for duplicate files.

> [!IMPORTANT]
> Requires ChronoFile, UsageStats, SizeInsight

### [GitLabMirroring](https://github.com/pontushenriksson/blossom-gitlabmirroring)

A plugin that lets you always have the latest version of a GitLab repository available locally. This will download the latest version of the repository but _NOT_ update the repository based on local changes.

### [GitHubMirroring](https://github.com/pontushenriksson/blossom-githubmirroring)

A plugin that lets you always have the latest version of a GitHub repository available locally. This will download the latest version of the repository but _NOT_ update the repository based on local changes.
