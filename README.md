gsutil rsync -d -r ./index.html gs://linked_content/mygo/ ; gsutil acl -r ch -u AllUsers:R gs://linked_content/mygo/
