This code needs to be run at https://github.com/Consensys/gnark-tests.git
1. Instructions for use
Replace main.go with the main.go function in the gnark-tests-main/solidity/contract folder
Place verify.py in the gnark-tests-main/solidity/contract folder
Run main.go first and then verify.py
2. If you want to replace it with another circuit - just modify the place with "(replacement)" in the comment
3. There are 4 functions in main.go: groth initialization, groth proof generation, plonk initialization, plonk proof generation
1、使用说明
将main.go替换gnark-tests-main/solidity/contract文件夹下的main.go函数
将verify.py放在gnark-tests-main/solidity/contract文件夹下
先运行main.go之后再运行verify.py
2、想要替换为其他电路——只需修改注释中带有“（替换处）的地方”
3、main.go内有4个函数：groth初始化、groth证明生成、plonk初始化、plonk证明生成
