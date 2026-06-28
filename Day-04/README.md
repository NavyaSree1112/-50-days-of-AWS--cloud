Day 4 – Enable Versioning for an S3 Bucket
📌 Objective
Enable Versioning on an existing Amazon S3 bucket to protect data from accidental deletion or overwriting.
📖 What I Learned
Amazon S3 stores objects in buckets.
Versioning keeps multiple versions of an object.
It helps recover deleted or overwritten files.
Once enabled, versioning cannot be disabled (only suspended).
🛠️ Steps Performed
Logged into the AWS Console.
Opened the S3 service.
Selected the required bucket.
Opened the Properties tab.
Navigated to Bucket Versioning.
Clicked Edit.
Enabled Versioning.
Saved the changes.
💡 Key Concepts
S3 Bucket: A container for storing objects.
Versioning: Maintains multiple versions of the same object.
Benefits:
Protects against accidental deletion.
Enables easy recovery of previous versions.
Improves backup and disaster recovery.
⚠️ Challenge Faced
The lab environment did not contain the expected S3 bucket, so the task could not be completed. This appeared to be an issue with the lab provisioning rather than the AWS steps.
✅ Outcome
Learned how S3 Versioning works and the process to enable it on an existing bucket.
