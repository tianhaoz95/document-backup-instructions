# Document Backup Instructions

```bash
zip -r "${BACKUP_ID}_intermediate.zip" "${BACKUP_ID}"
zip "${BACKUP_ID}_intermediate.zip" --out "${BACKUP_ID}_split.zip" -s 50m
```
