
pg_bulkload 3.1.16 bug report contents
--------------------------------------

Files for https://github.com/ossc-db/pg_bulkload/issues/84

### reproduce_steps.txt

Reproduce steps and gdb outputs.

### pg_bulkload-3.1.16.always_reindex.patch

A patch to add ALWAYS_REINDEX option.

### pg_bulkload-3.1.16.lib_pg_btree.c.diff

Another patch to have reindex rather than merge index if the disk sort is used.

