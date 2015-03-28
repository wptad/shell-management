#sed

* replacement

```     
sed -i '/etc\/systemd\/network/,$d' /var/lib/coreos-install/user_data 
sed -i 's/114\.114\.114\.114/10\.11\.1\.1/g' /etc/systemd/network/10-enp0.network

```