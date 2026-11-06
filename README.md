# constructor.sol
//constructor

// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;


contract MyContract{
    string public name;

    constructor(string memory initalName) {
        name = initalName;
    }
function setName(string memory newName) public {
    name = newName;
}


}

