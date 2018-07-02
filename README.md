truffle-ganache-metamask contracts and dApp development

required:
truffle
ganache
metamask
lite-server

install:
(1) git clone https://github.com/josefK128/truffle-ganache-metamask.git
(2) cd into repo root
(3) npm install
(4) truffle compile
(5) launch ganache
(6) truffle migrate
(7) truffle test

(8) click metamask in Chrome
(9) choose restore from seed - used seed phrase shown in ganache
    then choose a password
(10) make certain the network is private ganache!!! (localhost:7545)
(11) npm run dev (runs lite-server)
(12) choose dog - click adopt - should change to 'success' - may need to
     refresh browser
