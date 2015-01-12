# joomlasync
A Joomla backend component to synchronise database changes from a staging environment onto a live site.
It works by implementing database triggers on selected tables and storing the table name, key field names and key field values after the change has been made, i.e. after an INSERT, UPDATE or DELETE statement are executed.
