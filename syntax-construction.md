# Syntax Construction

All instances in this manual are used with two types of templates.

* user: Form template displaying staff information with namespace of supos\_employ. Its attributes are as follows.

```
uid：string type, staff ID
name: string type, staff name
dep: string type, staff department
age: integer type, staff age
employ_time: date type, entry time
```

* absence: Form template of note for leave with namespace of supos\_employ. Its attributes are as follows:

```
code: string type, code of note for leave.
user: object type, pointing to user template and using uid as the external link.
reason: string type,reason for leave
absence_days: float type, days of leave
```

##

##
