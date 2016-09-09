# breeze

cd /root/
wget http://evtikhov.ru/breeze.sh -r -N -nd
cat >> /root/.bashrc <<END
alias breeze='cd /root/
sh breeze.sh'
END
exit
