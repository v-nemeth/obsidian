Tags: [[Developer]] [[Fresh start on Ubuntu]]
Time: 08-12-2024-14:51

#### *Abstract*
___


___

# Install ruby on rails

## Installing asdf
### Official download
```
git clone https://github.com/asdf-vm/asdf.git ~/.asdf --branch v0.14.1
```

Add the following to bashrc
```bash
echo '$HOME/.asdf/asdf.sh' >> ~/.bashrc 
echo '$HOME/.asdf/completions/asdf.bash' >> ~/.bashrc 
```
## Installing Ruby using asdf package manager

### Install ruby dependencies
```bash
sudo apt-get install sqlite3 libsqlite3-dev mysql-server libmysqlclient-dev postgresql postgresql-client postgresql-contrib libpq-dev redis-server memcached imagemagick ffmpeg mupdf mupdf-tools libxml2-dev libvips42 poppler-utils libyaml-dev libffi-dev
```

### Add and install plugins
```bash
asdf plugin add ruby
```

```bash
asdf install ruby 3.3.0
asdf global ruby 3.3.0
```

### Install bundler and rails

```bash
gem install bundler
gem install rails
```


### Setup postgres
[[Setting up postgres in ruby on rails on ubuntu 24.04]]
___
