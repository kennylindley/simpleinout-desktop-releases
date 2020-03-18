[Simple In/Out](https://www.simpleinout.com)

GitHub Action Setup
-------------------

The workflow actions script relies on a few API keys that we should store in GitHub secrets. These allow access to AWS.

These are the secrets that need to be setup for this action to work:

* AWS_ACCESS_KEY_ID
* AWS_SECRET_ACCESS_KEY
* AWS_REGION
* AWS_S3_BUCKET

Github secrets will store these, and hide them in log files.
