# Monday February 19th

Hi I'm Chris (@nomad3k)

# Objectives

* [X] Update the README to include build/deployment instructions.
* [X] S3 bucket added
* [X] Ensure build process is linked to plan/apply
* [X] DNS pointing to bucket

# What I learned

* make is touchy about filenames "./" is important.
* s3 bucket needs:
  * public access block turned off
  * a read policy adding
  * upload the files using `aws_s3_object`
  * to configure the `content_type` using a lookup.
  * to be named as per the web address.  e.g. `dev.letsseethecode.com