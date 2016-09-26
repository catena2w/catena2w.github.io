# Transaction structure in cryptocurrencies

In this article I'm going to provide a brief review of block structure in cryptocurrencies.

## Introduction

A variety of cryptocurrencies, starting with [bitcoin](https://bitcoin.org/bitcoin.pdf) are based on *blockchain* structure.
In *blockchain* multiple transactions modifying cryptocurrency state are grouped into blocks generated according *consensus protocol*.
Blocks are ordered by linking to previous block so *blockchain* arises. 
As later blocks are chained, the work to change the block would include redoing all the blocks after it. 
So *block* should contain at least *transactional data* modifying current state, *consensus data* approving the right to generate a block and a link to previous block.

## Examples

