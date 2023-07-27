# rust_shuttle_my_project


# Rocky Linux 9 설치 에러에서 해결한 명령어(해결은 아님--)

```
cargo install cargo-shuttle --features vendored-openssl
```

https://github.com/shuttle-hq/shuttle/issues/720

- 결국 버그남 버그 보고했음 ㅠㅠ
  - https://github.com/shuttle-hq/shuttle/issues


# FullStack Rust

- Full Stack Rust Workshop: Shuttle, Actix Web, SQLx & Diouxus
  - https://bcnrust.github.io/devbcn-workshop/
 
- Rust Axum Full Course - Web Development | Jeremy Chone 👍❤️
  - https://youtu.be/XZtlD_m59sM

- Frontend

  - Learn Tailwind CSS – Course for Beginners | freeCodeCamp.org
    - https://youtu.be/ft30zcMlFao


## Deploy(Rust)

- https://www.shuttle.rs/
  - Doc
    - https://docs.shuttle.rs/introduction/welcome
  - ```cargo shuttle``` 활용법
    - https://github.com/shuttle-hq/shuttle/tree/main/cargo-shuttle
      - 해외 유튜버의 Tutorial영상 Live coding a full stack webapp with Rust, Actix, SQLx, Dioxus, and Shuttle
      - https://www.youtube.com/live/DCpILwGas-M?feature=share
      - github https://github.com/BcnRust/devbcn-workshop-dryrun
      - eBook https://bcnrust.github.io/devbcn-workshop/

- Deploy your Rust project in 20 minutes | Let's Get Rusty
  - https://youtu.be/_gMzg77Qjm0

<hr>

# Docker

- 도커 설명서 https://github.com/docker/awesome-compose

<hr>


# The Truth about Rust/WebAssembly Performance

https://youtu.be/4KtotxNAwME

<hr>

# Test

```
curl -v localhost:8000                                                                                                       ─╯

*   Trying ::1:8000...
* connect to ::1 port 8000 failed: Connection refused
*   Trying 127.0.0.1:8000...
* Connected to localhost (127.0.0.1) port 8000 (#0)
> GET / HTTP/1.1
> Host: localhost:8000
> User-Agent: curl/7.76.1
> Accept: */*
>
* Mark bundle as not supporting multiuse
< HTTP/1.1 200 OK
< content-length: 12
< content-type: text/plain; charset=utf-8
< date: Sat, 22 Jul 2023 14:02:45 GMT
<
* Connection #0 to host localhost left intact
Hello World!#
```

# DB
- PostgreSQL
  - PostgreSQL 14 Internal 최종본 (postgrespro.com) https://news.hada.io/topic?id=9864&utm_source=weekly&utm_medium=email&utm_campaign=202330
    - https://postgrespro.com/blog/pgsql/5969985
      - Learn PostgreSQL Tutorial - Full Course for Beginners | freeCodeCamp.org
        - https://youtu.be/qw--VYLpxG4

- SurrealDB
  - 소개 https://djlee118.tistory.com/609
  - Rust Powered Database SurrealDB (It's Pretty Ambitious) https://youtu.be/DPQbuW9dQ7w
