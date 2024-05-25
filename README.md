# README

### Setup

Install Ruby & Node

```bash
bundle install
npm install
rails db:create db:migrate

bin/dev # to run the rails server & vite
```

### Docker

```bash
docker build -t my-app .
docker run --rm -p 8080:3000 --name my-app -e RAILS_MASTER_KEY=$(cat config/master.key) my-app bin/rails s
```
