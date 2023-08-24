# vul-plugin-attest
Publish SBOM attestation

## Install

```
$ vul plugin install github.com/khulnasoft-lab/vul-plugin-attest
```

## Usage

```
A Vul plugin that publish SBOM attestation

Usage:
  attest [flags]

Examples:
  vul attest --type PREDICATE_TYPE --predicate PREDICATE_PATH BLOB_PATH
  # Publish SBOM attestation
  vul attest --type cyclonedx --predicate ./sbom.cdx.json ./my-executable

Flags:
  -h, --help               help for attest
      --predicate string   specify the predicate file path
      --type string        specify the predicate type(cyclonedx)
```
