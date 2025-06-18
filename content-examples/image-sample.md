---
description: This shows how images will appear in GitBook.
---

# Image Sample

Below is a sample image to show how developers can insert screenshots, ect.

<figure><img src="../.gitbook/assets/ACR-Logo-light-bkg.svg" alt=""><figcaption><p>You can write captions, too</p></figcaption></figure>

{% embed url="https://www.acr.org/" %}
Here is how a URL displays
{% endembed %}

{% file src="../.gitbook/assets/Gitbook Evaluation.docx" %}

```python
def quicksort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr) // 2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quicksort(left) + middle + quicksort(right)

# Example usage
arr = [3, 6, 8, 10, 1, 2, 1]
print(quicksort(arr))
```
