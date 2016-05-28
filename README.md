#Git Tutor#

### ng-clone ###
ng clone dulu dari repository yang udah team leader buat di htdoc
copas dari clone

	git clone https://[Username@]bitbucket.org/papperplanstudio/tes_crud.git

pindah pathnya ke folder yang baru di clone

	git init 	

	git remote add [namarepositori] [url repositori]
leader yang kirim url repositorinya

------------------------------------------------------------------------------
### Update cloud repository ke lokal repositori  ###

Aktifitas ini harus dilakuin kalo ada kontributor yang baru nge-push atau sebelum mau commit

	git pull [nama remote repositori] master

------------------------------------------------------------------------------
### Update local repository ke cloud repository (update local to cloud) ### 

	git add *

	git commit -m "[komentar Wajib abis ngapain]"

	git push [namarepositori] master

-------------------------------------------------------------------------------

### Tambah file ### 
Bikin file baru bisa dilakuin di explorer

	git add *

	git commit -m "[komentar Wajib abis ngapain]"

	git push [namarepositori] master
-------------------------------------------------------------------------------

### Hapus file ###

Ngehapus file harus dilakuin pake git bash / git gui

	git rm [nama file]

	git commit -m "[komentar Wajib abis ngapain]"

	git push [namarepositori] master
-------------------------------------------------------------------------------

### rename file ###

Ngehapus file harus dilakuin pake git bash / git gui

	git mv [nama file lama] [nama file baru]

	git commit -m "[komentar Wajib abis ngapain]"

	git push [namarepositori] master

-------------------------------------------------------------------------------

### store password in cache ###

	git config credential.helper store
	git push http://example.com/repo.git
	Username: <type your username>
	Password: <type your password>

	[several days later]
	git push http://example.com/repo.git
	[your credentials are used automatically]

-------------------------------------------------------------------------------

### Pindah file ke folder ###

-------------------------------------------------------------------------------

### Nambah folder ###

-------------------------------------------------------------------------------

### Hapus folder ###

-------------------------------------------------------------------------------

### Pindah folder ### 

-------------------------------------------------------------------------------

# README #

This README would normally document whatever steps are necessary to get your application up and running.

### What is this repository for? ###

* Quick summary
* Version
* [Learn Markdown](https://bitbucket.org/tutorials/markdowndemo)

### How do I get set up? ###

* Summary of set up
* Configuration
* Dependencies
* Database configuration
* How to run tests
* Deployment instructions

### Contribution guidelines ###

* Writing tests
* Code review
* Other guidelines

### Who do I talk to? ###

* Repo owner or admin
* Other community or team contact

dendi was here