# AresLottery
Lottery game based on Blockchain

- Using truffle env to do compile and testing
1. Install truffle golablly

    #npm install -g truffle

2. Init your project with truffle init

   #truffle init 

- Doing Security analysis with ConsenSys/mythril 
1. Install mythril/myth with Docker

    #docker pull mythril/myth  

2. compile contracts

    #truffle compile 
    
3. Do security analysis in the project directory

    #docker run -v $(pwd):/test -w "/test/" mythril/myth --truffle

