# Usage

添加相应的repo文件如下(/etc/portage/repos.conf/zeroway.conf)

	[zeroway]
	priority = 50
	sync-uri = https://github.com/54shady/zeroway
	location = /var/db/repos/zeroway
	auto-sync = Yes
	sync-type = git

同步仓库

	emerge --sync zeroway

更新数据库

	eix-update

安装软件

	emerge x11-terms/st::zeroway
