# Document Backup Instructions

```bash
zip -r "${BACKUP_ID}_intermediate.zip" "${BACKUP_DIR}"
```

```bash
zip "${BACKUP_ID}_intermediate.zip" --out "${BACKUP_ID}_split.zip" -s 23800m
```

See https://superuser.com/questions/336219/how-do-i-split-a-zip-file-into-multiple-segments for source information.
