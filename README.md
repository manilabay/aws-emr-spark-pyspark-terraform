# aws-emr-spark-pyspark-terraform

## Provision

I do the AWS provisioning using Terraform

You just need run this to provision the AWS Schema need for this process
Firt, before to run you should change all your aws variables in terraform/variables.tf to use all your AWS objects

```console
$ terraform plan
$ terraform apply
```
## Loading Datasets into S3


## Deploying a PySpark App


## Run the Spark jobs


## Dependencies

* [Terraform](https://terraform.io)

## References

* [PySpark CheatSheet](https://s3.amazonaws.com/assets.datacamp.com/blog_assets/PySpark_Cheat_Sheet_Python.pdf)

* [Spark Perf tests](https://github.com/databricks/spark-perf)
