# Fedora13_repo
Replace tree files under “/etc/yum.repos.d/”
fedora.repo
fedora-updates.repo
fedora-updates-testing.repo

# 清除yum暫存
yum clean all

# 列出有更新的檔案
yum list

# 執行更新
yum update


# 補上 yum 指令

yum search [套件名稱/關鍵字]
yum install [套件名稱]
yum remove [套件名稱]
