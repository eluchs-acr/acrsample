---
description: This shows how images will appear in GitBook.
---

# Image Sample

Below is a sample image to show how developers can insert screenshots, ect.

<figure><img src="../.gitbook/assets/ACR-Logo-light-bkg.svg" alt=""><figcaption><p>You can write captions, too</p></figcaption></figure>

{% embed url="https://www.acr.org/" %}
Here is how a URL displays
{% endembed %}

Here is an example of a code block:

```java
int[] arr= new int[5];
for (int i = 0; i < arr.length; i++)
{
    arr.quickSort();
}
```

```java
public class QuickSort {
    public static void quickSort(int[] array, int low, int high) {
        if (low < high) {
            int pi = partition(array, low, high);
            quickSort(array, low, pi - 1);
            quickSort(array, pi + 1, high);
        }
    }

    private static int partition(int[] array, int low, int high) {
        int pivot = array[high];
        int i = low - 1;
        for (int j = low; j < high; j++) {
            if (array[j] <= pivot) {
                i++;
                int swapTemp = array[i];
                array[i] = array[j];
                array[j] = swapTemp;
            }
        }
        int swapTemp = array[i + 1];
        array[i + 1] = array[high];
        array[high] = swapTemp;
        return i + 1;
    }

    public static void main(String[] args) {
        int[] arr = {10, 7, 8, 9, 1, 5};
        quickSort(arr, 0, arr.length - 1);
        System.out.println("Sorted array: " + Arrays.toString(arr));
    }
}

```

{% hint style="warning" %}
the code above is an AI implementation of the quicksort sorting algorithm
{% endhint %}

{% embed url="https://github.com/eluchs-acr/acrsample/blob/main/SUMMARY.md" %}

{% file src="../.gitbook/assets/Gitbook Evaluation.docx" %}

