#100%Aid
# Blockchain-Smart-Contract
100%Aid（百分百援助）是一个基于区块链智能合约的慈善监督管理系统。一个不可被撤销/抹失走向的区块链项目可以更好地帮助到被捐助者
100%Aid is a charity group donation supervising system, utilizing the blockchain features of unremovable and trackable route. we aim to reduce the possibility for grand charity donation to be wasted or relocate off the record.

**Built with**
-[Atom](https://atom.io/)-Editor\
-[hashlib](https://docs.python.org/3/library/hashlib.html)-Hash and message digest module\
-[Flask](http://flask.pocoo.org/docs/1.0/api/)-Used to initiate the nodes

**Technical Details**
The essential file of 100%Aid is written in python. 
Blockchain class is comprised of\ 
a register_node for creating new nodes,a valid_chain fucntion to verify if the given block is valid, a hash function that 
produces a 160-bit encrypted text,a conflict-resolving fucntion that replaces the current chain with the longest, 
new_transaction method that returns a json.Response() object. The object includes both the chain itself and its length. After 
the conflict has been resolved, the consensus method returns a mutual agreement and sends out any change made.

**Contributing**
Please read CONTRIBUTING.md for details on our code of conduct, and the process for submitting pull requests to us.

**Authors**
Xinyi X.
06/12/19



