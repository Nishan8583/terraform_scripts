1. build the program into main.zip
2. push to s3 bucket aws s3 cp ./main.zip s3://<bucket_name>/main.zip
3. terraform init
4. terraform valdiate
5. terraform apply (--auto-approve)