# academia-guard documentation!

## Description

AcademiaGuard is an interpretable AI-powered early warning system for higher education institutions to proactively reduce student attrition by identifying at-risk individuals and the specific factors driving their risk.

## Commands

The Makefile contains the central entry points for common tasks related to this project.

### Syncing data to cloud storage

* `make sync_data_up` will use `aws s3 sync` to recursively sync files in `data/` up to `s3://academia-guard-datasets/data/`.
* `make sync_data_down` will use `aws s3 sync` to recursively sync files from `s3://academia-guard-datasets/data/` to `data/`.


