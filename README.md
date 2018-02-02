<h3 style="text-align:center;font-weight: 300;" align="center">
  <img src="http://yuzhoujr.com/logo/blockMaster.png" width="160px">
</h3>

<p align="center">
  <img src="https://img.shields.io/badge/license-MIT-yellow.svg?style=flat-square">
  <img src="https://img.shields.io/badge/downloads-0k-yellow.svg?style=flat-square">
  <img src="https://img.shields.io/badge/build-passing-yellow.svg?style=flat-square">
</p>


>

<!-- ## Features -->

 ## External Libraries

Third Party library are used in this project

Package    |      Description
---------- | :--------------------:
`hashlib`  | SHA-256 Algorithm Core
`datetime` | Access real-time date

## Getting Started

### Run

````bash
```

### Code Walkthrough
In `class Blockchain`:

```python
class Blockchain(object):
    def __init__(self):
        self.chain = []
        self.current_transactions = []

    def new_block(self):
        # Creates a new Block and adds it to the chain
        pass

    def new_transaction(self):
        # Adds a new transaction to the list of transactions
        pass

    @staticmethod
    def hash(block):
        # Hashes a Block
        pass

    @property
    def last_block(self):
        # Returns the last Block in the chain
        pass
````

### Lessons learned

🐌 **@staticmethod** is a method that belongs to a class but behaves exactly like a regular function, which doesn't take any first `arg` such as `self` or `class`.

```python
@staticmethod
def hash(block):
    #Hashes a Block
    pass
```

--------------------------------------------------------------------------------

🍜 **@property** is a shortcut for creating read-only properties. which, in turn, is the simplified syntax for creating a `property` with just a getter.

```python
@property
def x(self):
    return self._x
```

is equivalent to

```python
def getx(self):
    return self._x
x = property(getx)
```

## Demo

## License

🌱 MIT 🌱

--------------------------------------------------------------------------------

> ![home](http://yuzhoujr.com/emoji/home.svg) [yuzhoujr.com](http://www.yuzhoujr.com) · ![github](http://yuzhoujr.com/emoji/github.svg) [@yuzhoujr](https://github.com/yuzhoujr) · ![linkedin](http://yuzhoujr.com/emoji/linkedin.svg) [@yuzhoujr](https://linkedin.com/in/yuzhoujr)
