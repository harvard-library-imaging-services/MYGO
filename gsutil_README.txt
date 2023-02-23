cp ~/pCloud\ Drive/WORK/NOTES/ImagingServices_FY23_keyObjectives_MYGOs_20230215.md .
cp imagingServices_MYGO23.html index.html
gsutil cp index.html gs://linked_content/mygo/
gsutil acl -r ch -u AllUsers:R gs://linked_content/mygo
# /mnt/p/WORK/MYGO


cp ~/pCloud\ Drive/WORK/NOTES/ImagingServices_FY23_keyObjectives_MYGOs_20230215.md ~/pCloud\ Drive/WORK/MYGO/ ; cp imagingServices_MYGO23.html index.html ; gsutil cp index.html gs://linked_content/mygo/ ; gsutil acl -r ch -u AllUsers:R gs://linked_content/mygo ; git add --all ; git commit -m  "updates"

pandoc ImagingServices_FY23_keyObjectives_MYGOs_20230215.md -f markdown -o IS_keyObjectivesMYOGs.docx
