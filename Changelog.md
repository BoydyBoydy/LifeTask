# Changelog

## 0.7.0
New Features:
- Goals View
  - Goal Summary / Objective
  - Key Results
  - Child Releases
  - Child Tasks
- Releases View:
  - Added Tasks Counts (Tasks Total (Blue) and Tasks Left (Yellow))
  - Release Percentages (Total Current Release / Total Child Release)

## 0.6.1
New Features:

- Releases View 
  - Can move a task from one release to another
  - Can now have Child Releases
  - 'Remove Child Release' option won't appear unless there are actually children available
  - Ensured that Releases were sorted by oldest to newest
- Task Management
  - Ensured that Tasks were sorted by oldest to newest
- Scheduled View
  - Ensured that Tasks were sorted by oldest to newest
  - When updating scheduled tasks, view is refreshed in order to show that the change has been made properly
- Due Dates
  - Can now remove a due date to empty

## 0.6.0
New Features:

- Added an Extra Feedback Option in Application -- Public GitHub Repository
- Removed unneeded Navigation
- Releases can be linked
- Can now add new Tasks directly into Releases
  - Brainstorming work, and/or keeping everything in the same release
- Simple Dependency Graph for Releases
- Combined Graph View
  - Picker for which type of Graph you want (Task, Release)
- Breaking Change: Updated data to make it more generic for newer data types
  - This means I had to manually change my data, replace words for uniqueIDs
- Simple Recurring Tasks, daily only - 'every 1 days', etc.

## 0.5.0
New Features:

- Percentage Completed for Releases
- DONE Tasks will now be displayed in an expandable section
- Checkboxes added to Tasks and Releases in order to automatically move task status to DONE

## 0.4.0
New Features:

- Task Management View (Combined View)
- Releases View
  - % Complete - Partially Implemented
- Due Dates
  - Included for Tasks and Releases
- Scheduled View
  - For viewing issues with due dates
  - Basic Sorting
    - Overdue
    - Today
    - Next

## 0.3.0
New Features:

- WSJF Planning View - for prioritising Tasks
- Simple Releases - for grouping work (as-is, or within a time period)
  - You can add Tasks to Releases - such as different projects, groups of work, etc.
  - Releases View - to view all releases
- Tasks
  - Default Statuses are now available to use - to update the task status and so that a visual of the task status is available

Saved Files are still unstable between versions, but the application can still be used for the moment.
This will be tested and improved in future releases.

## 0.2.0
New Features:

- Autosave after actions
- Task Linking - Able to link Parent to Child Tasks
- Task Graph View - Display Simple Visualisation of the Task Links Hierarchy, rather than arrows/lines (which is future intended)
- Simple Logo Icon


## 0.1.0
I have created a usable initial release, with:

- light task management
- basic UI Components

This is basically to get the first edition out with something usable.