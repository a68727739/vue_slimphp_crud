    step01 根目錄 composer install
    step02 建立資料庫並匯入資料  sql檔案在 _sql 資料夾下 slimapp.sql
    step03 修改 資料庫參數  src\config\db.php
    step04 如本地端測試 要加入並修改 host 域名 (對應到vcustomers資料夾下src->components各vue參數 例如 http://slimapp/api/customer/add )
    step05 進入 vcustomers 下 npm install
    step06 npm run dev
