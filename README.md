# axelar-kit

This is a toolkit from axelar transfer and query balance.

## functions

- query balance from axelar chain and transfer it

```
import {queryBalance,transfer} from 'axelar-kit';

const taskquery = async ()=>{
  const balance = await queryBalance(mnemonic,0,axl_rpc);
  console.log(balance);
}

const tasktransfer = async ()=>{
  const result = await transfer(mnemonic,from,to,amount,customgas,rpc);
  console.log(result);
}

```
