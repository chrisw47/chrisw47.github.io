---
title: "Hello World"
date: 2026-03-15
description: "A first post to test the site — math rendering, code blocks, and formatting."
tags: ["meta"]
math: true
---

This is a sample project post. Replace this with a write-up of something you built.

## Math rendering

Inline math works with single dollar signs: the Euler identity is $e^{i\pi} + 1 = 0$.

Display math uses double dollar signs:

$$
\int_{-\infty}^{\infty} e^{-x^2} \, dx = \sqrt{\pi}
$$

You can also write block equations like:

$$
\nabla \cdot \mathbf{E} = \frac{\rho}{\varepsilon_0}
$$

## Code blocks

Code is syntax-highlighted automatically:

```python
import numpy as np

def softmax(x):
    e_x = np.exp(x - np.max(x))
    return e_x / e_x.sum()
```

## Writing new posts

To create a new post, add a `.md` file to `content/projects/` with this frontmatter:

```yaml
---
title: "Your Post Title"
date: 2026-01-01
description: "One sentence shown in the post list."
tags: ["tag1", "tag2"]
math: true   # only needed if the post contains LaTeX
---
```

Then write the body in Markdown below the `---`.
