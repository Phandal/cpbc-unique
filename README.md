# cpbc-unique
Used to get all the unique values out the extracted-data. This is very useful when creating the a
template with mappings for the first time.

## Requirements
- [jq](https://jqlang.org/)

## Usage
```shell
# -f means treat as financial feed; -b means treat as benefit feed;
cpbc-unique [-fb] <input-file>
```
