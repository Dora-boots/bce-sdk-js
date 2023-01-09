# CHANGELOG
## 1.0.0-rc.37(2023-01-09)

- BosClient: support 'x-bce-server-side-encryption', 'x-bce-restore-days', 'x-bce-restore-tier' headers;

## 1.0.0-rc.36(2022-05-06)

- BOSClient: fix getObject stream.store

## 1.0.0-rc.35(2022-05-05)

- BOSClient: Just keep an array of all of buffers and concat at the end.

## 1.0.0-rc.34(2021-12-15)

- BOSClient: Provide cname_enabled field when using a custom domain name to delete bucketName path.

## 1.0.0-rc.33(2021-11-26)

- TsdbDataClient: support database parameter.

### Fix

- BOSClient: fix the browser environment reference entry.

## 1.0.0-rc.32(2021-10-22)

### Fix

- BOSClient: fix the browser environment reference entry.

## 1.0.0-rc.31(2021-08-13)

### Fix

- BOSClient: add key valiation in getObject() & getObjectToFile() method;
  - empty key is not allowed
  - consecutive forward slashes (/) are not allowed in key
  - forward slash (/) and a backslash (\\) are not allowed at head or tail
  - consecutive periods (..) are not allowed in sub-path

## 1.0.0-rc.30(2021-08-03)

### Fix

- BOSClient: fix issue of lack of '/' prefix of object url;

## 1.0.0-rc.29(2021-08-03)

### Feature

- BOSClient: support "config.removeVersionPrefix"(boolean) parameter to dynamic control 'v1' prefix of resource in generatePresignedUrl, generateUrl;

## 1.0.0-rc.28(2021-03-26)

### Fix

- Fix entry file path for browser environment

## 1.0.0-rc.27(2021-03-03)

### Features

- CFCClient supports trigger API

## 1.0.0-rc.26(2020-12-23)

### Features

- BOSClient supports putBucketStorageclass API
- BOSClient supports putBucketAcl API

## 1.0.0-rc.25(2020-09-01)

### Features

- BOSClient supports `x-bce-storage-class` header
