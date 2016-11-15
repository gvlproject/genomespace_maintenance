# GS AU
Maintenance page for GenomeSpace Australia.

### Launch instructions

1. Install dependencies:
  ```
  sudo apt-get update
  sudo apt-get -y install nginx
  sudo apt-get install git
  sudo service nginx start
  ```

2. Clone repo, place contents into `/usr/share/nginx/html/`

3. Then, reload nginx

  ```
  sudo service nginx restart
  ```
