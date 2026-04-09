# MaxNumber.sol
This is a valuable reminder.
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.20;

contract MaxNumber {
    function max(uint a, uint b) public pure returns (uint) {
        return a >= b ? a : b;
    }
}
Initial commit
Add basic contract structure
Fix minor bug in function
Update logic for better performance
Refactor code for readability
