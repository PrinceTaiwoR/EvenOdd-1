// SPDX-License-Identifier: MIT
pragma solidity ^0.8.0;

contract EvenOddChecker {
    
    // Function to check if a number is even or odd
    // Returns true if the number is even, false if odd
    function isEven(uint256 number) public pure returns (bool) {
        // The modulus operator (%) returns the remainder of the division of number by 2.
        // If the remainder is 0, the number is even; otherwise, it is odd.
        return number % 2 == 0;
    }
}
