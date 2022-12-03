# Me resumé

This repo stores my resume in [JSON Resume Schema](https://jsonresume.org/schema/), written in YAML.

For ease of editing - namely collapsing multi-line strings, I am using YAML instead. Here's a note on converting back and forth from YAML and JSON, with [`yq`](https://mikefarah.gitbook.io/yq/) ([`jq`](https://stedolan.github.io/jq/)):

- Converting YAML to JSON:
  ```shell
  yq . resume.yaml > resume.json
  ```
  and this is included in the autosave extension - check `.vscode/`.


- Converting JSON to YAML (`-y` flag):
  ```shell
  yq . resume.json -y > resume.yaml
  ```

