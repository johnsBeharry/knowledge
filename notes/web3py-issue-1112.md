# `#1112` Add type hints

### Components

- [ ] ens
- [ ] web3
  - [ ] admin
  - [ ] contract
  - [ ] datastructures
  - [ ] eth
  - [ ] filtering
  - [ ] contracts
  - [ ] providers
  - [ ] middleware
  - [ ] shh
  - [ ] **_utils**
    - [ ] abi
    - [ ] blocks
    - [ ] caching
    - [ ] contracts
    - [ ] datatypes
    - [ ] decorators
    - [ ] empty
    - [ ] encoding
    - [ ] ens
    - [ ] events
    - [ ] filters
    - [ ] formatters
    - [ ] function_identifiers
    - [ ] http
    - [ ] hypothesis
    - [ ] math
    - [ ] normalizers
    - [ ] request
    - [ ] rpc_abi
    - [ ] threads
    - [ ] transactions
    - [ ] validation
    - [ ] windows

### NOTES

1. Create more specific dictionary types using `mypy.TypedDict()`

```
Point2D = TypedDict('Point2D', {'x': int, 'y': int, 'label': str})
a: Point2D = {'x': 1, 'y': 2, 'label': 'good'}  # OK
b: Point2D = {'z': 3, 'label': 'bad'}           # Fails type check
```

2. Generic types instead of Callable [link](https://docs.python.org/3.5/library/typing.html#typing.Generic)

```
from typing import Generic
Generic()
```

3. Start small, select a small module in your codebase to start adding types to.

   Extra points to start with the most use module.

   Spend a day doing this – and create a pull request ASAP.

4. Annotate function signatures, arguments and returns
5. Annotate variables only if you have to
6. Overloads and Generics teaches the type checker more about the code
7. Be careful using `Any` because at runtime we might get errors in our tests 

## Questions

Are we going to be setting the typing for tests in the repo?

- `web3/_utils/_module_testing/*`
- `tests`

# TODO

- [ ] Enable discovery of packages' types when imported
  `add [py.typed] to setup.py`

- [ ] update docs

- https://web3py.readthedocs.io/en/stable/v4_migration.html?highlight=sha3
- https://web3py.readthedocs.io/en/stable/quickstart.html?highlight=sha3
- https://web3py.readthedocs.io/en/stable/releases.html?highlight=sha3
- https://web3py.readthedocs.io/en/stable/filters.html?highlight=sha3
- https://web3py.readthedocs.io/en/stable/examples.html?highlight=sha3
- https://web3py.readthedocs.io/en/stable/web3.eth.account.html?highlight=sha3
- https://web3py.readthedocs.io/en/stable/web3.eth.html?highlight=sha3

