---
{"dg-publish":true,"permalink":"/work/komodo-mobile-v2-deployment-checklist/","noteIcon":""}
---

- [ ] Add whitelisted_apps​ migration
- [ ] Add SSM values for AWS S3 Kredivo
- [ ] Request permission to Kredivo S3 bucket to komodo-v2-web-production​


List of release branches:
1. ​feat/SCOL-3852-3929-3920/debtor-details​
2. ​feat/SCOL-3920/add-app-list​

List of SSM Values:

```env
AWS_KREDIVO_S3_BUCKET=
AWS_KREDIVO_S3_REGION=
AWS_KREDIVO_S3_UPLOAD_PATH=
AWS_KREDIVO_S3_ENDPOINT_URL=
AWS_B2B_USER_S3_BUCKET=
AWS_B2B_USER_S3_REGION=
```