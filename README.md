### GitHub

git init (inicializar)

git branch -M "main" (alterar nome da branch principal)

git add . (Adicionar arquivos a ser feito o commit)

git status (ver status, arquivos q vão ser commitados)

git commit -m "nome do commit" (fazer o commit)

git remote add origin https://github.com/dnsrodrigues/nome-repositorio.git (criar link remoto com repositorio Github))

git push -u origin main (efetuar o push "upload" dos arquivos commitados)
git push origin main (alterações não precisa do "-u")

git checkout -b "nova-branch" (criando uma branch nova)
git checkout "main" (alterar entre branch)

git merge nova-branch (juntar branch com a principal)

git clone https://github.com/dnsrodrigues/laravel-vuejs.git (clonar repositorio)

git pull (atualizar projeto local com os arquivos do repositorio)


### Laravel

composer create-project laravel/laravel API_LARAVEL --prefer-dist

php artisan serve

php artisan make:Controller UsuarioController --resource

php artisan make:model Usuario -m

php artisan migrate

=============Clonar Projeto=============

composer install

npm install

cp .env.exemple .env

php artisan serve


### Vuejs.

=============VUE 2===============

npm install -g @vue/cli

Create a project:

vue create my-project 

OU 

vue ui

=============VUE 2===============

=============VUE 3===============

npm init vue@latest (VUE 3)

=============VUE 3===============

	cd nome-projeto
	npm install
	npm run dev

npm run serve
