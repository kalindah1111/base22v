# base22v
Counting Transactions Per Block
Python
block = w3.eth.get_block("latest")
print(len(block.transactions))

Java
EthBlock block = web3.ethGetBlockByNumber(DefaultBlockParameterName.LATEST, true).send();
System.out.println(block.getBlock().getTransactions().size());
