# OPK CLI: Cloudstitch for Google Sheets  
A commandline client for pushing data into Cloud Sheets via the Cloudstitch API. 

```
./push
  --account <account> Example: janesmith
  --project_id <project_id> Example: magic-form-7
  --stream Accept streaming piped data that delimits pushes by line breaks
  --verbose Use for debug output

Example: echo 42 | ./push --account=janesmith --project_id=magic-form-7
```

## Requirements
- Node.js

