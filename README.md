# hiveos-virus
sd.sh适用于hiveos系统的杀毒使用  运行命令 curl -v https://raw.fastgit.org/Jealousy1314/hiveos-virus/main/sd.sh | bash
该杀毒文件是星火时代官方杀毒文件，现在转移到这里
Palit国内raw无法下载请查看使用该链接 https://raw.fastgit.org/Jealousy1314/hiveos-virus/main/Palit_GTX1660SUPER-6G-90.16.59.00.28.rom
Msi https://raw.fastgit.org/Jealousy1314/hiveos-virus/main/Msi_GTX1660SUPER-6G-90.16.4F.40.A9.rom
hiveos更新1660s海力士bios 
开启维护模式不加载显卡驱动，重启然后ssh远程登陆，定位到hine/sbin目录 命令 cd hive/sbin 然后使用wget下载 命令 wget https://raw.fastgit.org/Jealousy1314/hiveos-virus/main/Msi_GTX1660SUPER-6G-90.16.4F.40.A9.rom或者wget https://raw.fastgit.org/Jealousy1314/hiveos-virus/main/Palit_GTX1660SUPER-6G-90.16.59.00.28.rom
下载完成以后使用nvflash_linux -i0 -6 Msi_GTX1660SUPER-6G-90.16.4F.40.A9.rom或者nvflash_linux -i0 -6 Palit_GTX1660SUPER-6G-90.16.59.00.28.rom更新需要y确认两遍才能写入成功
