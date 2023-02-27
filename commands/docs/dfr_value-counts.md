---
title: dfr value-counts
categories: |
  dataframe
version: 0.76.0
dataframe: |
  Returns a dataframe with the counts for unique values in series
usage: |
  Returns a dataframe with the counts for unique values in series
---

# <code>{{ $frontmatter.title }}</code> for dataframe

<div class='command-title'>{{ $frontmatter.dataframe }}</div>

## Signature

```> dfr value-counts ```

## Examples

Calculates value counts
```shell
> [5 5 5 5 6 6] | dfr into-df | dfr value-counts
```