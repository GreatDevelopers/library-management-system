```sh
mosh hsrai@erp.gndec.ac.in
sudo ufw allow 60000:61000/udp
sudo ufw disable
sudo ufw enabled
sudo ufw enable
sudo ufw status numbered
sudo ufw status numbered | grep 465
sudo ufw allow 465/tcp
sudo apt install mlocate
sudo chown hsrai -R /home/hsrai
cd
git clone https://github.com/frappe/bench /home/sammy/.bench --depth 1 --branch master
git clone https://github.com/frappe/bench ~/.bench --depth 1 --branch master
sudo pip3 install -e ~/.bench
bench init ~/frappe-bench --frappe-path https://github.com/GreatDevelopers/erpnext --frappe-branch version-13 --python python3
bench init ~/frappe-bench --frappe-path https://github.com/frappe/frappe --frappe-branch version-13 --python python3
cd frappe-bench/
bench get-app ERPNext https://github.com/GreatDevelopers/erpnext --branch version-13
bench setup requirements
bench new-site erp.ukiericoncretecongress.com --admin-password 'erpUCC' --mariadb-root-username hsrai --mariadb-root-password 'hsraiDB' 
bench drop-site erp.ukiericoncretecongress.com
bench drop-site erp.ukiericoncretecongress.com --force 
bench   --mariadb-root-username hsrai drop-site  erp.ukiericoncretecongress.com --force 
sudo mysql -u root -p
sudo bench  drop-site  erp.ukiericoncretecongress.com --force 
sudo mysql_secure_installation
mysql -uroot -p
mysql -u hsrai -p
sudo mysql_secure_installation
mysql -uroot -p
sudo service mysql restart
sudo bench  drop-site  erp.ukiericoncretecongress.com --force 
bench new-site erp.ukiericoncretecongress.com --admin-password 'erpUCC' --mariadb-root-username hsrai --mariadb-root-password 'hsraiDB' 
bench start
cd sites/
joe common_site_config.json 
cd -
bench start
tmux new -s hsr
tmux ls
tmux a -t hsr
sudo snap install certbot --classic
sudo certbot --nginx

bench init rai-bench
cd rai-bench/
sudo snap install tree
tree .
tree -d .
tree -d -L 1 . | more
bench find .
bench new-app library_management
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.11/install.sh | bash
nvm install 14
export NVM_DIR="$HOME/.nvm"
[ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"
[ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion" 
nvm install 14
node -v
npm install -g yarn
pip3 install frappe-bench
which bench
echo $PATH
joe .bashrc 
source ~/.bashrc
bench --version
bench init rai-bench
cd rai-bench/
bench start
bench find .
bench new-app library_management
bench start
/etc/init.d/redis-server status
/etc/init.d/redis-server stop
bench start
sudo service nginx stop
sudo service nginx start
bench start
bench start
sudo service supervisor stop
w3m http://erp.gndec.ac.in:8001/
cd rai-bench/
cd sites/
cp ../../frappe-bench/sites/REMcurrentsite.txt .
mv REMcurrentsite.txt currentsite.txt 
w3m http://erp.gndec.ac.in:8001/
w3m http://103.66.206.232:8001/
cd library_rai/
cd .git/
cat config 
cd ..
git status
git branch
git add . 
git status
git add -A
sudo apt  install gitsome
gh repo create
sudo pip install pyOpenSSL --upgrade
gh configure
joe ~/.gitsomeconfig 
cd library_rai
cd
cd tmp/
mkdir Test
cd Test/
mkdir A
touch a.text b.text A/c.csv
git init
git add . 
git status
git branch
git commit -m "initial commit"
git config --global user.email "hardeep.rai@gmail.com"
git config --global user.name "hsrai"
git commit -m "initial commit"
git status
joe .git/config 
git push --set-upstream origin master
git fetch
git status

echo "# Test1" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/hsrai/Test1.git
git push -u origin main

git remote add origin https://github.com/hsrai/Test1.git
git branch -M main
git push -u origin main
```