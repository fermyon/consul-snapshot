## 0.2.5
* Upgrade to golang 1.19
* Update to use go mod

## 0.2.4 (Unreleased)

## 0.2.3 
* Add support for Google Cloud Storage
* Updated google cloud import
* Changed health check to not use connection pool

## 0.2.2
* Add hostname to backup file
* Add optional prefix configured via env var
* Add optional SSE for S3 backups

## 0.2.1
* Bug fix for restore path

## 0.2.0
* Clean up acceptance test logics by moving to config struct
* Back up ACLs
* Back up Prepared Queries
* Optionally encrypt data with a CRYPTO_PASSWORD environment variable passphrase
* Add metadata on backups
* Refactor backup layout and adjust restores
* Add additional unit and acceptance tests
* Add a default backup interval of 60 seconds

## 0.1.5
* Fix regression in temp file restore location

## 0.1.4
* Make aws credentials not required

## 0.1.3
* Add configurable tmp dir

## 0.1.2
* Fix regression in remote file naming

## 0.1.1
* Explicitly state that the backup completed successfully
* Add count of keys to log output
* Add travis.yml for testing
* Write to a better structured remote path in s3 bucket bucketname/backups/year/month/day/*
* Rebuild with latest hashicorp/go-cleanhttp
* Add updatedeps Makefile option

## 0.1.0

* Initial Release
