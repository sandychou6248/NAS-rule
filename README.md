# NAS規範 
Aimmlab NAS 規範

## NAS 使用說明  
1. 本實驗室 nas 主要用來存放datasets
2. nas是mount在server下的一顆硬碟 (18T HD)  
3. nas 分為兩個大的資料夾，分別是Queue & datasets
4. Queue 是暫存用戶的datasets 申請，若此次申請經管理員核准，即可移至datasets,作為本實驗室之共用datasets 

## NAS 使用流程 
1. 將現有 datasets 填寫表單(問卷形式)，管理員根據申請項目填寫至Queue，表單連結為 
https://docs.google.com/spreadsheets/d/1YrVrQSeD-RFwq54jbCF6XOtoYC_dBs6TPGXBJXFIXdA/edit?pli=1#gid=653022741
3. 待申請通過,用戶可至/nas/datasets/xx 自行cp  

## NAS 所在位置
* 使用者在server上的帳號皆位於 /mnt/data0/usernamexxx，而NAS資料夾位於和前述的mnt資料夾同一層級的位置
* 因次使用者切換路徑用以下指令: ../../../nas ， 即可找到nas資料夾

## Note 
1. Server一個帳號不得超過 100 G ( master ac可到 300G)，指的是SSD ; 換言之帳號未超過容量, 可以不用放NAS。  
2. 欲上傳之dataset 請以 zip format  

## NAS Rules  
1.由於Queue 為公用資料夾請勿更改他人資料  
2.請申請再將datasets 放置Queue，若申請單上沒有該筆對應資料，則由管理員直接移除



 
