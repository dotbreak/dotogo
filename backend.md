# taskwarrior

## how
do not parse the ~/.task d=.data files but rather use taskwarrior import/export http://taskwarrior.org/docs/commands/export.html functions which use json.

source : http://taskwarrior.org/docs/3rd-party.html

see also https://github.com/theunraveler/taskwarrior-web or inspiration

## taskwarrior tasks' properties

20 core properties (called attributes). see https://taskwarrior.org/docs/commands/columns.html and http://taskwarrior.org/docs/design/task.html

*In bold what's need to be visible in UI.*


- component (color ?)
- **depends**
- **description**
- **due** (due date)
- end (date, when work on task has ended) *could be visible in calendar view ?*
- entry (creation date https://taskwarrior.org/docs/terminology.html#entry)
- **estimate** (numeric, estimated time to complete the task)
- id (number assigned to a task, from 1 and so on https://taskwarrior.org/docs/ids.html)
//imask ()
//mask (?)
- modified
- **parent** (for subtasks) *visible in calendar view (in list view not needed, we see parent on top)*
- **priority**
- **project**
- **recur** (if tasks is repeated, ex each week)
- **scheduled** (scheduled date)
- start (date, when work on task has started) *could be visible in calendar view ?*
- status (pending, completed, deleted and recurring https://taskwarrior.org/docs/terminology.html#waiting)
- **tags**
- tracnumber (connection to trac bug tracker)
- tracsummary (connection to trac bug tracker)
- tracurl (connection to trac bug tracker)
- until (date, show task until that date, after it is automatically deleted.https://taskwarrior.org/docs/terminology.html#until)
- urgency (Urgency is a numeric score Taskwarrior assigns to each task. https://taskwarrior.org/docs/urgency.html)
- uuid (permanent unique identifier, not normally visible)
- wait (date, don't show task until this date)




can use user defined attributes (UDA) : https://taskwarrior.org/docs/udas.html

# trello

Could also be a trello GUI (trello as backend)
