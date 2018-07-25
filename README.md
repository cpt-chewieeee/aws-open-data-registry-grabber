to view s3 directories
```
  aws s3 ls [NAME]

  ex: $ aws s3 ls s3://gdelt-open-data
```


to download s3 content
```
  aws s3 cp --request-payer=requester --recursive   [S3_BUCKET_DIR]  [DESTINATION_DIR]
  ex: $ aws s3 cp --request-payer=requester --recursive   s3://gcgrid/GEOS_4x5/GEOS_FP/2013/08/   ./
```