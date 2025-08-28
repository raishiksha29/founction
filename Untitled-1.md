#
 Q4. Describe how dictionaries store data.

- A **dictionary** stores data as **key-value pairs**.
- Each **key** is unique and is used to access its corresponding **value**.
- Dictionaries are **mutable**, so you can add, update, or remove items.
- Internally, dictionaries use a **hash table** for fast lookups.

### Example:

```python
# Creating a dictionary
student = {
    "name": "Ritesh",
    "age": 21,
    "course": "Engineering"
}

# Accessing data
print(student["name"])  # Output: Ritesh

# Adding new key-value pair
student["grade"] = "A"

# Updating value
student["age"] = 22
