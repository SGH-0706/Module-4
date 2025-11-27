## 4B Dictionary Operations in Python: Merging Two Dictionaries
## Developed by : Srinithi Muthukumar
## Register No. : 212224240161
## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program : 
```
dict1={'Ten': 10,'Twenty': 20,'Thirty': 30} 
dict2={'Thirty': 30,'Fourty': 40,'Fifty': 50} def 
merge (dict1,dict2): 
res={**dict1 , **dict2} return 
res 
dict3=merge(dict1,dict2) 
print(dict3)
```

## Output :

<img width="805" height="165" alt="image" src="https://github.com/user-attachments/assets/e5b8ddd4-c67e-4184-a31b-3d1b5bb755e8" />

## Result :
The program successfully merges two dictionaries, combining their key-value pairs. If a key exists in both dictionaries, the value from the second dictionary overwrites the first.
