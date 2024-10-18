# Solidity API

## SafeMath

_Math operations with safety checks that throw on error_

### 

```solidity
undefined(uint256 a, uint256 b) internal pure returns (uint256)
```

### 

```solidity
undefined(uint256 a, uint256 b) internal pure returns (uint256)
```

### 

```solidity
undefined(uint256 a, uint256 b) internal pure returns (uint256)
```

### 

```solidity
undefined(uint256 a, uint256 b) internal pure returns (uint256)
```

## Ownable

_The Ownable contract has an owner address, and provides basic authorization control
functions, this simplifies the implementation of "user permissions"._

### owner

```solidity
address owner
```

### 

```solidity
undefined() public
```

### onlyOwner

```solidity
modifier onlyOwner()
```

### 

```solidity
undefined(address newOwner) public
```

## ERC20Basic

_Simpler version of ERC20 interface
see https://github.com/ethereum/EIPs/issues/20_

### _totalSupply

```solidity
uint256 _totalSupply
```

### 

```solidity
undefined() public view returns (uint256)
```

### 

```solidity
undefined(address who) public view returns (uint256)
```

### 

```solidity
undefined(address to, uint256 value) public
```

### Transfer

```solidity
event Transfer(address from, address to, uint256 value)
```

## ERC20

_see https://github.com/ethereum/EIPs/issues/20_

### 

```solidity
undefined(address owner, address spender) public view returns (uint256)
```

### 

```solidity
undefined(address from, address to, uint256 value) public
```

### 

```solidity
undefined(address spender, uint256 value) public
```

### Approval

```solidity
event Approval(address owner, address spender, uint256 value)
```

## BasicToken

_Basic version of StandardToken, with no allowances._

### balances

```solidity
mapping(address => uint256) balances
```

### basisPointsRate

```solidity
uint256 basisPointsRate
```

### maximumFee

```solidity
uint256 maximumFee
```

### onlyPayloadSize

```solidity
modifier onlyPayloadSize(uint256 size)
```

### 

```solidity
undefined(address _to, uint256 _value) public
```

### 

```solidity
undefined(address _owner) public view returns (uint256 balance)
```

## StandardToken

_https://github.com/ethereum/EIPs/issues/20
Based oncode by FirstBlood: https://github.com/Firstbloodio/token/blob/master/smart_contract/FirstBloodToken.sol_

### allowed

```solidity
mapping(address => mapping(address => uint256)) allowed
```

### MAX_UINT

```solidity
uint256 MAX_UINT
```

### 

```solidity
undefined(address _from, address _to, uint256 _value) public
```

### 

```solidity
undefined(address _spender, uint256 _value) public
```

### 

```solidity
undefined(address _owner, address _spender) public view returns (uint256 remaining)
```

## Pausable

_Base contract which allows children to implement an emergency stop mechanism._

### Pause

```solidity
event Pause()
```

### Unpause

```solidity
event Unpause()
```

### paused

```solidity
bool paused
```

### whenNotPaused

```solidity
modifier whenNotPaused()
```

### whenPaused

```solidity
modifier whenPaused()
```

### 

```solidity
undefined() public
```

### 

```solidity
undefined() public
```

## BlackList

### 

```solidity
undefined(address _maker) external view returns (bool)
```

### 

```solidity
undefined() external view returns (address)
```

### isBlackListed

```solidity
mapping(address => bool) isBlackListed
```

### 

```solidity
undefined(address _evilUser) public
```

### 

```solidity
undefined(address _clearedUser) public
```

### 

```solidity
undefined(address _blackListedUser) public
```

### DestroyedBlackFunds

```solidity
event DestroyedBlackFunds(address _blackListedUser, uint256 _balance)
```

### AddedBlackList

```solidity
event AddedBlackList(address _user)
```

### RemovedBlackList

```solidity
event RemovedBlackList(address _user)
```

## UpgradedStandardToken

### 

```solidity
undefined(address from, address to, uint256 value) public
```

### 

```solidity
undefined(address sender, address from, address spender, uint256 value) public
```

### 

```solidity
undefined(address from, address spender, uint256 value) public
```

## TetherToken

### name

```solidity
string storage pointer name
```

### symbol

```solidity
string storage pointer symbol
```

### decimals

```solidity
uint256 decimals
```

### upgradedAddress

```solidity
address upgradedAddress
```

### deprecated

```solidity
bool deprecated
```

### 

```solidity
undefined(uint256 _initialSupply, string storage pointer _name, string storage pointer _symbol, uint256 _decimals) public
```

### 

```solidity
undefined(address _to, uint256 _value) public
```

### 

```solidity
undefined(address _from, address _to, uint256 _value) public
```

### 

```solidity
undefined(address who) public view returns (uint256)
```

### 

```solidity
undefined(address _spender, uint256 _value) public
```

### 

```solidity
undefined(address _owner, address _spender) public view returns (uint256 remaining)
```

### 

```solidity
undefined(address _upgradedAddress) public
```

### 

```solidity
undefined() public view returns (uint256)
```

### 

```solidity
undefined(uint256 amount) public
```

### 

```solidity
undefined(uint256 amount) public
```

### 

```solidity
undefined(uint256 newBasisPoints, uint256 newMaxFee) public
```

### Issue

```solidity
event Issue(uint256 amount)
```

### Redeem

```solidity
event Redeem(uint256 amount)
```

### Deprecate

```solidity
event Deprecate(address newAddress)
```

### Params

```solidity
event Params(uint256 feeBasisPoints, uint256 maxFee)
```

