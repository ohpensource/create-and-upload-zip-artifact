# create-and-upload-zip-artifact

```yaml
      - uses: ohpensource/create-and-upload-zip-artifact@main
        id: create-and-upload-zip-artifact
        with:
          region: $AWS_REGION
          access-key: ${{ secrets.AWS_ACCESS_KEY_ID }}
          secret-key: ${{ secrets.AWS_SECRET_ACCESS_KEY }}
          destination-account: $ARTIFACTS_AWS_ACCOUNT_ID
          role-name: $AWS_ROLE_NAME
          version: "v0.0.1"
          service-name: $SERVICE_NAME
          bucket-name: $ARTIFACTS_BUCKET_NAME
```

