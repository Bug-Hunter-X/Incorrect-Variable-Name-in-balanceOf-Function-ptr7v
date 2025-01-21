# Solidity Bug: Incorrect Variable Name in balanceOf Function

This repository demonstrates a common error in Solidity: using the wrong variable name in a function.

The `bug.sol` file contains a contract with a `balanceOf` function that incorrectly accesses the balance using `balances` instead of `balanceOf`. This leads to incorrect balance retrievals.

The `bugSolution.sol` file provides the corrected version, which uses the correct `balanceOf` variable.