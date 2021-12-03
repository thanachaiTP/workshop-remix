# Demo Samrt Contact Remix 
> https://remix.ethereum.org


## 1. เปิด Remix
![Remix-copy-code](pic/01-Remix-copy-code.png)

## 2. copy code จาก dome.sol
copy source code จากไฟล์ dome.sol ไปวางในกล่องข้อความที่ 5 ตามรูปตัวอย่าง

![dome-sol](pic/02-dome-sol.png)

## 3. Solidity compiler
เลือกเมนู Solidity compiler เลือก version compiler ใน source code ใช้ version 0.8.4

![compiler-dome-sol](pic/03-compiler-dome-sol.png)

## 4. Deploy & RUN
เลือกเมนู Deploy & run transactions จากนั้นเลือกที่ Environment เลือก Injected Web3 จะมีหน้าต่าง metamask ขึ้นมาให้เลือก account และที่จะ deploy
ต่อมาคือ Contract ให้เลือก Contract DOME - dome.sol และกด Deploy


![deploy-01-dome-sol](pic/04-deploy-env-inject-web3.png)
![deploy-02-dome-sol](pic/04.1-deploy-env-inject-web3.png)
![deploy-03-dome-sol](pic/04.2-deploy-env-inject-web3.png)

## 5. Blockscout
ไปที่หน้า blockscout ในตัวอย่าง http://139.59.126.43:4000/ กดเลือกที่ address ของ contact ที่ create ไปเมื่อสักครู่ กด เมนู code --> verify & Publish

![deploy-05-select-contact](pic/05-select-contact.png)

หน้า New Smart Contract Verification เลือก  Verification via Flattened source code และกด Next
![deploy-05.1-code](pic/05.1-code.png)
![deploy-05.2-new-smart-contact-verify](pic/05.2-new-smart-contact-verify.png)

> Contract Name : DEMO

> Include nightly builds : No

> Compiler : v0.8.4+commit.c7e474f2

> EVM Version : default

> Optimization : No

> Enter the Solidity Contract Code : copy code จากไฟล์ demo.sol มาวาง

> Try to fetch constructor arguments automatically : Yes

> กด Verify & publish
![deploy-05.3-verify](pic/05.3-verify.png)


ถ้า verify ผ่านจะมี เพิ่มมาอีก 2 เมนูคือ Read Contact กับ Write Contact
![deploy-05.4-verify-success](pic/05.4-verify-success.png)



## 6. Mint เหรียญ
เลือก เมนู Write Contact
![deploy-06-write-contact](pic/06-write-contact.png)

เลือกที่ข้อ 10 mint 
- receiver (address) คือกระเป๋าที่จะ mint เหรียญ DEMO ไปให้
- amount(uint256) คือ จำนวนเหรียญ ตัวอย่าง ต้องการ 1 เหรียญจะเท่ากับ 1000000000000000000 
กด Write
![deploy-06-write-contact](pic/06-write-contact.png)
![deploy-06.1-write-contact](pic/06.1-write-contact.png)
![deploy-06.2-write-contact](pic/06.2-write-contact.png)
![deploy-06.3-write-contact](pic/06.3-write-contact.png)
![deploy-06.4-write-contact](pic/06.4-write-contact.png)
![deploy-06.3-write-contact](pic/06.3-write-contact.png)



## 7 Add Token Metamask
copy address ของ DEMO ไปเพิ่มที่ Metamask
![deploy-06.5-token](pic/06.5-token.png)
![deploy-06.6-token](pic/06.6-token.png)
![deploy-06.7-token](pic/06.7-token.png)

