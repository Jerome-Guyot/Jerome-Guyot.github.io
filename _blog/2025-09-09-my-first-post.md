---
layout: blog
title:  "Testing Blog posts"
date:   2025-09-09 21:30:00 +0200
---

Coming soon


Trying to understand how to write and include latex environments.


$$ E=mc^2 $$

<div class="display-box">
$E = mc^2$
</div>

test


{: .exercise}
> **Exercise 1.** Prove that if $n$ is even, then $n^2$ is even.
>
> [See Solution &rarr;](#solution1)

{: .block}
> **Definition.** Prove that if $n$ is even, then $n^2$ is even.

{: .example}
> **Example.** Prove that if $n$ is even, then $n^2$ is even.

{: .theorem}
> **Theorem.** Prove that if $n$ is even, then $n^2$ is even.




```python
def hello():
    print("Hello, Markdown!")
```


<div style="text-align: center; margin: 20px 0;">
  <img src="/files/blog/blog1/addressability.PNG" alt="Addressability" width="600" />
  <div style="color: black; font-weight: normal; font-size: 1em; margin-top: 5px;">
    Figure 1: Addressability
  </div>
</div>

{: .exercise #solution1}
> **Solution 1.** If $n$ is even, $n = 2k$ for some integer $k$, so $n^2 = (2k)^2 = 4k^2$, which is even.