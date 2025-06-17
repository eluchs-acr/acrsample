---
description: This page shows core features of GitBook.
---

# PoC Page

Below is a code block.

```java
for (int i = 0; i < arr.length; i++)
{
arr.quickSort();
}
```

<figure><img src="../.gitbook/assets/ACR-Logo-light-bkg.svg" alt=""><figcaption><p>ACR Logo</p></figcaption></figure>

{% file src="../.gitbook/assets/Gitbook Evaluation.docx" %}

The above text is a evaluation of GitBook.

```python
def find_duplicates(arr):
    # Initialize a list to hold duplicate numbers
    duplicates = []
    
    # Create an empty set to keep track of numbers we've seen
    seen = set()
    
    # Iterate over each number in the input array
    for num in arr:
        # Check if the number is already in the 'seen' set
        if num in seen:
            # If it is, add it to the duplicates list if it's not already there
            if num not in duplicates:
                duplicates.append(num)
        else:
            # If it's not in 'seen', add it for future reference
            seen.add(num)
    
    # Return the list of duplicate numbers found
    return duplicates

# Example array to find duplicates in
arr = [1, 2, 3, 4, 5, 2, 6, 1, 3, 7]

# Print the result with a descriptive message
print("Duplicate numbers:", find_duplicates(arr))
```

This code is more verbose, providing comments and additional explanations of each part of the process used to identify duplicates in the array.

To sync a GitBook with GitHub, first ensure you have a GitHub repository set up for your project. Then, in the GitBook editor, navigate to the integrations section and select GitHub. You will need to authorize GitBook to access your GitHub account. Choose the repository you want to sync with and specify the branch where you want the changes to be reflected. Once connected, changes made in GitBook will automatically update your GitHub repository, providing a seamless workflow for version control and collaboration.
