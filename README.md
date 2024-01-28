## Stock Nominee ##

This smart contract, written in the Solidity programming language, facilitates the nomination and distribution of shares to nominees in a stock ownership scenario. Below is a simple explanation of its functionality:

## Contract Overview:##

  **Owner:** The owner of the contract, who has the authority to nominate and distribute shares to nominees.
  **Nominees:** Individuals nominated to receive shares. The contract allows up to two nominees at a time.
  **Total Nominees:** Keeps track of the total number of nominees currently added.

## Adding Nominees:**
 **Function:** `eligibilityForNominee`
 **Description:** This function checks eligibility criteria and adds a nominee if they meet the requirements.
 **Eligibility Criteria:** Nominee must be at least 18 years old.
   Nominee should have invested in fewer than 5 companies.
 **Ownership Requirement:** Only the contract owner can add nominees.

## Share Distribution: ##

 **Function:** shareDistribution
 **Description:** Distributes shares to the nominated individuals.
 **Input:** Nominee number as a string.
 **Share Distribution Logic:** This part of the contract is left to be implemented based on specific business rules. For illustration purposes, it's assumed to 
  happen within this function.
 **Revert Condition:** If the provided nominee number matches a registered nominee, the function reverts with a custom message indicating the nominee's eligibility 
  for shares.
 **Reset Nominee Count:** After distributing shares, the total nominee count is reset to allow for adding more nominees in the future.

## License:

 This contract is released under the MIT License, allowing for open usage and modification.

## Author 

Chethan 

kumarljchethan@gmail.com
