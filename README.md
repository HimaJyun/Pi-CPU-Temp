# Description
Get Raspberry Pi CPU Temperature for Munin.

## Using
```
wget https://raw.githubusercontent.com/HimaJyun/Pi-CPU-Temp/master/pi_cpu_temp
sudo mv pi_cpu_temp /usr/share/munin/plugins/
sudo chown munin:munin /usr/share/munin/plugins/pi_cpu_temp
sudo chmod 755 /usr/share/munin/plugins/pi_cpu_temp
sudo ln -s /usr/share/munin/plugins/pi_cpu_temp /etc/munin/plugins
```
