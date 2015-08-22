# OPK CLI: Cloudstitch for Google Sheets  
A commandline client for pushing data into Cloud Sheets via the Cloudstitch API. You can pipe a single value to this CLI or JSON. Make sure to set "Auto-Add Columns" to `true` in your Cloudstitch project. You can also pipe a stream of data to this CLI where each new line is a new value. The CLI will exit when it hears an exit code from the left side of the pipe. 

```
./push
  --account <account> Example: janesmith
  --project_id <project_id> Example: magic-form-7
  --stream Accept streaming piped data that delimits pushes by line breaks
  --verbose Use for debug output

Usage: echo 42 | ./push --account=janesmith --project_id=magic-form-7
Usage: echo '{"foo":"bar"}' | ./push --account=janesmith --project_id=magic-form-7
```

## Requirements
- Node.js

