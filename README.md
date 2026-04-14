# OddCheck.sol
OddCheck.sol
pragma solidity ^0.8.20;
contract OddCheck {
    function isOdd(uint x) public pure returns(bool) {
        return x % 2 != 0;
    }
}
