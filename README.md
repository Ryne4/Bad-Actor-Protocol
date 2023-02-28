# PRDAO Transaction Smart Contract

This PyTeal smart contract calculates the rewards for a marketer and three reviewers for their participation in a project. The contract also includes a fee for the PRDAO organization.

## Prerequisites

This smart contract is written in PyTeal, so you'll need to have PyTeal and Python installed to execute it.

## Getting Started

To use this smart contract, you'll need to define the following transaction parameters:

- `client_address`: the address of the client who initiated the project
- `marketeer_address`: the address of the marketer who promoted the project
- `freelancer1_address`, `freelancer2_address`, and `freelancer3_address`: the addresses of the three reviewers who evaluated the project
- `prdao_address`: the address of the PRDAO organization
- `base_value`: the base value of the transaction
- `prdao_fee`: the fee for the PRDAO organization

Once you've defined these parameters, you can execute the `prdao_transaction()` function to calculate the rewards for the marketer and reviewers and the total amount of the transaction.

## Usage

To use this smart contract, simply run the `prdao_transaction()` function with the defined transaction parameters.
