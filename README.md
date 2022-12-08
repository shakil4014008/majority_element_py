# majority_element_py
````py
def majority(nums) -> int: 
  dict  = {}
  for i in nums: 
    dict[i]  = dict.get(i, 0) + 1

  for x, y in dict.items(): 
    if y > len(nums) / 2: 
      return x 

lst = [2, 2, 2, 3, 3, 3, 3]
print(majority(lst))
  
````
