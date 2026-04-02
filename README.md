# 4640-in-class-wk13
### Allison Chen and Joanne Xie


## Screenshots
1. AWS S3 web console that shows the state file only.
![state](/state-file.png)

2. AWS S3 web console that shows the lock file and the state file.
![both](/lock-file.png)

## Lab Questions
1. When is the state file created?
- after terraform apply is successful
- when terraform writes the infrastructure state to the S3 backend

2. When is the lock file present?
- when terraform apply is actively running

3. Is the lock file always in the bucket after it is created?
- no
- lock file is temporary
- removed after the terraform operation is complete
