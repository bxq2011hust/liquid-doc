合约的所有方法需要被封装于一个由`liquid(methods)`属性标注的`impl`块中，且`impl`块的标识符需要与封装合约状态变量的`struct`的标识符相同（此合约中标识符都为"HelloWorld"）

，但不能被用户或外部合约调用