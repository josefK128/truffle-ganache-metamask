truffle-ganache-metamask: contracts and dApp development    
  
required:    
truffle    
ganache  
metamask  
lite-server  
  
install:  
(1) git clone https://github.com/josefK128/truffle-ganache-metamask.git    
(2) cd into repo root    
(3) npm install    
  
// compile/test/migrate contract (optional - else jump to (8))  
(4) truffle compile  
(5) truffle test  
(6) launch ganache  
(7) truffle migrate --reset  
  
// simply run dApp   
(8) launch ganache (not needed if steps 4,5,6,7 were done)  
(9) click metamask in Chrome  
(10a) enter password  OR  
(10b) choose restore from seed - used seed phrase shown in ganache  
    then choose a password  
(11) make certain the network is private ganache!!! (localhost:7545)  
(12) npm run dev (runs lite-server) => dApp launches in browser window  
(13) choose dog - click adopt - should change to 'success' - may need to  
     refresh browser  
