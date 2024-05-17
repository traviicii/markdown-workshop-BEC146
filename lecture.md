# Introduction to Markdown Workshop {#top}
---
## Basic Markdown Syntax

## 1. Headers

**There are 6 sizes of header**

**Example**
> # Header Size 1
> ## Header Size 2
> ### header Size 3
> #### Header size 4
> ##### Header Size 5
> ###### Header Size 6

**Syntax**

```md
# Header Size 1
## Header Size 2
### header Size 3
#### Header size 4
##### Header Size 5
###### Header Size 6
```


## 2. Emphasis

We can create emphasis in 3 specific ways

We can make things **bold**

```md
**bold**
```


We can make things *italic*
```md
*italic*
```

We can ~~strikethrough~~ text

```md
~~strikethrough~~
```


We can ***~~also do this~~***!

```md
***~~also do this~~***
```

We can also make things ***bold and italic***

```md
***bold and italic***
```


## 3. Lists

### Ordered

1. First thing
    - look here
    - this is nested
        - I can even nest further
1. Sedond thing
1. Third thing

### Unordered

- This thing
- That thing
- The other thing

## 4. Links and Images

### Links

[Back to the Top](#top "This takes you to the top of the page!")

[Poke API](https://pokeapi.co/ "This takes you to the Poke API Documentation")

### Images

![Ditto](https://raw.githubusercontent.com/PokeAPI/sprites/master/sprites/pokemon/other/dream-world/132.svg "Ditto")


---

## Advanced Features

### Tables

**Syntax**

```md
| Parameter | Type | Description | Extra info |
|-----|----|---|---|
| `first_name` | `string` | Required |
| `email` | `string` | Required |
```

**Result**

```http
POST /api/user
```

| Parameter | Type | Description | Extra info |
|------|---|---|---|
| `first_name` | `string` | Required |
| `email` | `string` | Required |


### Code `Blocks`!

```
simple code block
pip install flask
```

```python
def solution():
    this = 'that'
    for i in range(0, 20, 2):
        print(i)
    return this
```

```bash
pip install flask
```

### Block Quotes

> A block quote could be a side note, further info about a certain step, perhaps a definition for something.


### Definitions

What is an ORM?
: An ORM is an Object Relational Mapper that helps us relate a coding language like Python into SQL queries

**What is an ORM?**
> An ORM is an Object Relational Mapper that helps us relate a coding language like Python into SQL queries.

---