# Changes in this fork

* Added s3.Bucket.SignedFullURL(): 
```
// SignedFullURL returns a signed URL for the requested HTTP method and accepts arbitrary HTTP headers and parameters to sign. The URL stays valid until expires.
// Original SignedURL calls now SignedFullURL.
// This is a DRY modification of forked github.com/mitchellh/goamz/s3/s3.go.
```
