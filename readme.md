# Ansible
> 建立一些使用上的範例

- .gitignore
    - host
    - all

- group_var
    - 建立group的定義參數all
    
- host
    - inventory
    - 記錄主機資訊

- site.yaml
    - ansible啟動任務規劃

## 啟動指令

```
ansible-playbook -i host site.yaml
```


## roles
- Create_Delete_Directory
        > 新增刪除修改目錄   
       
    1. 新增修改目錄
    2. block分組運用
    3. copy檔案

- OS_ansible
        > 放一些os常用動作   
    1. 新增使用者
    2. 新增群組
    3. 修改密碼
    4. 查找pid

- CA_update
        > 預定針對jdk進行憑證更新
    1. 檢查憑證
