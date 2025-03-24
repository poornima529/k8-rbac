REGION_CODE=us-east-1
CLUSTER_NAME=expense
ACC_ID=340752838251

### Permissions

* OIDC provider
```
eksctl utils associate-iam-oidc-provider \
    --region $REGION_CODE \
    --cluster $CLUSTER_NAME \
    --approve
```