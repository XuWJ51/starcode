#基本設定
#確認安裝
git --version
#用戶資料
git config --global user.name ""
git config --global user.email ""
#初始化
git init
#檢查狀態
git status
#將檔案變更為追蹤
git add *檔案名稱*
git add *.副檔名
git add .(所有變更都加入)
#檔案拍照
git commit -m "敘述"
#檢視紀錄
git log
git --oneline
#比較差異
git diff *id編號*
#還原檔案
git checkout *id編號*--*檔案名稱*
#還原檔案並刪除後續(不可逆)
git reset --hard *目標還原點id*
