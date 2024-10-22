

# Phoenix_gerlessver

<img src="https://blixtdev.com/content/images/size/w2000/2023/02/1WvDl2WlPs7cR8TTBvrjpyw.png" alt="Phoenix Logo" width="600"/>




https://github.com/juniormesquitadandao/gerlessver

```bash
git clone https://github.com/edinaldorodriguesceara/phoenix_gerlessver
cd phoenix_gerlessver

  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose config
  ARG_USER_UID=$(id -u) ARG_USER_GID=$(id -g) docker compose build
  docker compose up -d
  docker compose exec app bash
    cat /etc/hosts | grep dockerhost
    echo > /dev/tcp/dockerhost/5432 && echo "Postgresql is running"

    mix deps.get
    mix deps.compile
    mix ecto.create
    npm install
    mix test
    iex -S mix
    mix phx.server
    # Brower: http://localhost:4000
    # Press: CTRL+C
    git status
    git add .
    git commit -m 'update'
    git push
    exit
  docker compose down
