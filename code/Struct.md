# Solidity — Struct

In Solidity, as a C inspired language it has this feature built in — a struct is a way to group a list of variables so it is accessible using a single pointer.

This can be a useful way to struct-ure your code so it's a bit more clean.

```C
pragma solidity ^0.4.21
contract Salary {
  struct Employee {
    string name;
  	unit rate;
    unit hours;
  }
}
```



### Gas Impact

- Unknown