# AresLottery
Lottery game based on Blockchain

#using truffle env to do compile and testing 

#Doing Security analysis with ConsenSys/mythril 
steps:
1. Install mythril/myth with Docker
    #docker pull mythril/myth  

2. compile contracts
    #truffle compile 
    
3. Do security analysis in the project directory
    #docker run -v $(pwd):/test -w "/test/" mythril/myth --truffle

