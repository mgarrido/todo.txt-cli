# Note add-on for todotxt

This add-on allows to attach a note (just one) to a task.

## Adding, viewing and editing notes

* `note add|a ITEM#`. Adds a note to task ITEM#.
* `note edit|e ITEM#`. Opens the note related with task ITEM# in editor.
* `note show|s ITEM#`. Shows the note related with task ITEM#.

## The notes' archive

When a done task is archived, the content of its note (if any) is appended to an archive file. This archive can be viewed or edited with the `show` and `edit` operations:

* `note edit|e archive|a`. Opens in editor the notes' archive.
* `note show|s archive|a`. Shows the notes' archive.

The archive file is the only way to acces an archived task's note.

## Deleted tasks

When a task is deleted, its note (if any) is also also deleted.