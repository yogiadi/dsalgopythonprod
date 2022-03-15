## Binary Search

<details>
  <summary>Binary Search</summary>
	
* Define binarysearch func
* Run till high >= low.
* if element is present at mid.
* if arr[mid] > x then call binary search func (arr,low, mid -1, x)
* else call binary search func (arr, mid+1, high,x)
  
</details>

```python

def binary_search(arr, low, high, x):
	if high >= low:# Check base case
		mid = (high + low) // 2
		if arr[mid] == x:# If element is present at the middle itself
			return mid
		elif arr[mid] > x:# If element is smaller than mid, then it can only, be present in left subarray
			return binary_search(arr, low, mid - 1, x)
		else:# Else the element can only be present in right subarray
			return binary_search(arr, mid + 1, high, x)
	else:# Element is not present in the array
		return -1

```


