# Nuclei GUI
自用nuclei图形化界面工具。
## 工具介绍
采用python编写，包含了nuclei扫描器的基本常用功能。整体界面简洁，可以中文显示漏洞名称。只支持Windows系统。
## 工作目录
│ ─ nuclei.exe

│ ─ Nuclei_GUI-v1.0.exe

│ ─ url.txt

│ ─ poc

│    | ─ poc_20240326212835.yaml

│    | ─ poc_20240408172441.yaml

│    | ─ ……

│ ─ work

│    | ─ config.ini

│    | ─ poc_list.xlsx

│    | ─ random_UA.txt

│    | ─ result.txt

│    | ─ result_new.txt

│    | ─ result_zh.txt

│    | ─ validate_API_Key.vbs

## 使用指南
1、首先需要下载nuclei.exe本体程序，将其与本工具置于同一目录下。下载链接[https://github.com/projectdiscovery/nuclei/releases](https://github.com/projectdiscovery/nuclei/releases)

2、将yaml格式的poc文件存储到poc文件夹内

3、扫描结果中显示的漏洞名称为yaml文件中的name字段，如想显示id字段，可将id字段值复制到name字段

4、选择POC功能和扫描结果表格中的内容，可通过ctrl或shift进行多选

5、使用过程中如遇bug或有宝贵建议，请提交Issues

## 待改进
1、如果扫描结果数量较大，工具可能会有略微卡顿

2、选择POC功能，计划增加poc搜索、筛选等功能，更加方便查找选择poc

3、新建、编辑POC功能，目前采用的是直接编辑yaml文件，计划增加编辑poc窗口，更加方便编写poc

4、联动数据库存储poc、扫描结果等，进一步优化

……
## 工具截图

## 免责声明
本工具截图所进行的演示poc为虚假poc，不具有真实攻击性，且本工具不包含任何漏洞利用poc，仅作为个人使用nuclei图形化工具。在使用本工具时，您应确保该行为符合当地的法律法规，并且已经取得了足够的授权，请勿对非授权目标进行访问。如您在使用本工具的过程中存在任何非法行为，您需自行承担相应后果，本人将不承担任何法律及连带责任。请勿将本项目技术或代码应用在恶意软件制作、软件著作权/知识产权盗取或不当牟利等非法用途中。
