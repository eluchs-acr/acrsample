---
description: This shows how images will appear in GitBook.
---

# Image Sample

elow is a sample image to show how developers can insert screenshots, ect.

<figure><img src="../.gitbook/assets/ACR-Logo-light-bkg.svg" alt=""><figcaption><p>You can write captions, too</p></figcaption></figure>

{% embed url="https://www.acr.org/" %}
Here is how a URL displays
{% endembed %}

```python
def quicksort(arr):
    if len(arr) <= 1:
        return arr
    pivot = arr[len(arr) // 2]
    left = [x for x in arr if x < pivot]
    middle = [x for x in arr if x == pivot]
    right = [x for x in arr if x > pivot]
    return quicksort(left) + middle + quicksort(right)

# Example usage:
arr = [3, 6, 8, 10, 1, 2, 1]
print(quicksort(arr))
```

The American College of Radiology (ACR) is a distinguished professional organization dedicated to advancing the field of radiology. It provides a wide array of resources, including accreditation, advocacy, education, and research to support radiologists and related professionals. Through its initiatives, the ACR aims to improve the quality and safety of radiological care, while fostering an environment for knowledgeable professional practice and innovation in medical imaging and radiation oncology.

{% file src="../.gitbook/assets/Gitbook Evaluation.docx" %}
