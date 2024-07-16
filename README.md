# Blossom file organizer

Ever felt confused about where you stored your files or where to store them? Maybe you downloaded files you wanted to keep into the downloads folder and accidentally cleared it and lost the files you wanted to keep? That for sure has happened to me, and that is why I started working on this project.

# Blossom File Organizer - Base version

## Features included in the base version

### File Management

- **Basic Sorting and Organizing:**

  - Organize files by name and filetype.
  - Move, copy, delete, and rename files.

- **Folder Structure:**
  - Create, delete, and rename folders.
  - Support for nested folders.

### Search Functionality

- **Search:**
  - Basic search functionality to find files by name.

### Configuration

- **User Settings:**
  - Basic configuration options for user preferences like customized sort phrases, tags or names.
  - Save and load user settings.

# Plugins (not yet implemented)

## Features included with plugins

### NeuroSort

- A plugin helping you to sort files based on their connection to other files. This could, for example, utilize metadata.

> _Dependencies:_
>
> - None

### LexiSort

- A plugin helping you to sort files based on a lexicon or dictionary you created.

> _Dependencies:_
>
> - None

### ArchiFile

- A plugin with comprehensive archiving functionality for archiving files. This could be used together with `FileSense` to automatically archive files that seem to not have been used in a long time.

> _Dependencies:_
>
> - `FileSense`

### CogniPulse

- A plugin that organizes files dynamically based on usage. This could be set up to utilize a folder structure based on usage.

> _Dependencies:_
>
> - None

### ChronoFile

- A plugin that handles metadata related to time, for example when a file was created and last modified. This plugin is basic but not in the core app since some might not want to share that due to privacy reasons.

> _Dependencies:_
>
> - None

### SizeInsight

- A plugin that handles metadata related to data size and how it changed over the last modification.

> _Dependencies:_
>
> - None

### UsageStats

- A plugin that displays the size of files and folders and how it has changed over time. It also maps out the distribution of file types across directories, helping users understand their file composition.

> _Dependencies:_
>
> - `SizeInsight`

### FileSense

- A plugin that determines whether a file is in use or it should be archived based on a specific algorithm and data gathered from `ChronoFile`.

> _Dependencies:_
>
> - `ChronoFile`

### FileMinder

- A plugin that could remind users of where a file is located.

> _Dependencies:_
>
> - None

### Medula

- A plugin that could create reminders and remind users about activities.

> _Dependencies:_
>
> - None

### Activities

- A plugin that could create to-dos. This plugin could work better with `Medula`.

> _Dependencies:_
>
> - `Medula`

### StabiliFile

- Creates systematic backups of the whole structure so if something goes wrong, all or most of the content could be retrieved. This works as a backup system and could be great if you later want to switch to another device. This also stores your latest config file.

> _Dependencies:_
>
> - None

### FileSync

- A plugin which helps synchronizing files across devices.

> _Dependencies:_
>
> - None

### SecureVault

- A plugin which helps secure your folders and data. This will automatically password protect your information including your config file, backups and more.

> _Dependencies:_
>
> - None

### SecureVault

- A plugin which helps secure your folders and data. This will automatically password protect your information including your config file, backups and more.

> _Dependencies:_
>
> - None

### AccessControl

- A plugin that allows users to set access permissions for individual files and folders. Supports role-based access control to manage permissions for different user roles.

> _Dependencies:_
>
> - `SecureVault`

### SecurityMonitoring

- A plugin that saves how many times the files/folders have been opened and what time to let users check if any unauthorized users have checked their files while they have been gone.

> _Dependencies:_
>
> - `SecureVault`

### DupliCheck

- A plugin that helps users check for duplicate files.

> _Dependencies:_
>
> - `ChronoFile`
> - `UsageStats`
> - `SizeInsight`
