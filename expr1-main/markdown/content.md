---
title:  'Markdown to \LaTeX: A Tool'
author:
- Jingyi Chen
- Another Author
complex-author-mode: false
abstract: |
  This is the abstract.

  It consists of two paragraphs.
---

# Test Section

## Test Subsection

### Test Subsubsection

Hello, world!

Test **bold words**. Test *italic words*. Test ***bold and italic words***. 

Test inline math: $\forall g \in G$.

Test block math:

$$
y = \sum_{i=1}^{N} a_i x^i
$$

Test inline latex things: hi \LaTeX

Test number list:

1. Number One
2. Number Two
    1. Subnumber 1
    2. Subnumber 2
    3. Subnumber 3
3. Number Three

Test unordered list:

* Item A
* Item B
    * Subnumber X
    * Subnumber Y
    * Subnumber Z
* Item C

// TODO have some problem
Test label and immediate reference: \label{hello} and \ref{hello}

Test inline code: `print` is a function of `Python`.

Test code section:

```python
print('Hi')
```

Test citation: \cite{citation1}

// TODO image label & ref
Test image:

![some text for the image](../images/hello_image.png)

Test table: TODO not supported yet.

<!-- | Key | Value |
| ----------- | ----------- |
| Tom | Chen |
| Hello | World | -->

End of test.