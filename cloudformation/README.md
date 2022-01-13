# Deploy

```bash
export AWS_PROFILE=alaya-sphinx-live
aws cloudformation deploy \
    --template bucket.yaml \
    --region ca-central-1 \
    --stack-name rosetta-config \
    --capabilities CAPABILITY_IAM
```