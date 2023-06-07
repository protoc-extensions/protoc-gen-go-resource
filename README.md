# protoc-gen-go-resource

This is a fork of [protoc-gen-go-resource](ucarion/protoc-gen-go-resource).

## Usage

```
# buf.gen.yaml
version: v1

managed:
  enabled: true

plugins:
  - name: go-resource
    out: internal/proto
```
