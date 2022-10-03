## What is Grafana?
```
Grafana allows you to query, visualize, alert on and understand your metrics no matter where they are stored. Create, explore, and share beautiful dashboards with your team and foster a data driven culture.
```
- for more Learn about Grafana from official documentation Follow this link >> https://grafana.com/docs/grafana/
---
### Befour a Transaction  Grafana with Elastic we must Learn some Knowledge about ELK
- for learn about ELK Follow this link >> https://github.com/melgawad/ELK-transaction
---
### Install and Start Grafana
#### Download Grafana manual
```
wget https://dl.grafana.com/enterprise/release/grafana-enterprise-9.2.0~beta1-1.x86_64.rpm
```
#### Install Grafana
```
sudo rpm --install grafana-enterprise-9.2.0~beta1-1.x86_64.rpm
```
#### Start and enable Grafana using systemctl command
```
systemctl start grafana-server
systemctl enable grafana-server
```
---
#### Sign in to Grafana
- Open your web browser and go to http://localhost:3000/. The default HTTP port that Grafana listens to is 3000 unless you have configured a different port.
- On the signin page, enter admin for username and password.
- Click Sign in. If successful, you will see a prompt to change the password.
- Click OK on the prompt and change your password.
---
#### 
