# coraza-spoa-ipv6-test

```bash
docker compose up
```

```
coraza-spoa-ipv6-test-coraza-1   | Loading 1 applications
coraza-spoa-ipv6-test-haproxy-1  | [NOTICE]   (1) : New worker (8) forked
coraza-spoa-ipv6-test-haproxy-1  | [NOTICE]   (1) : Loading success.
coraza-spoa-ipv6-test-coraza-1   | time="2024-07-23T14:02:47Z" level=info msg="spoe: listening on [::]:9000"
coraza-spoa-ipv6-test-coraza-1   | time="2024-07-23T14:02:47Z" level=error msg="spoe error during first notify handle: handle notify: Argument 'src-port' not found"
coraza-spoa-ipv6-test-haproxy-1  | SPOE: [coraza-agent] <EVENT:on-frontend-http-request> sid=0 st=1 0/4/-1/-1/503 1/1 0/0 1/1
coraza-spoa-ipv6-test-haproxy-1  | 2001:3200:3200::4:37036 [23/Jul/2024:14:02:47.463] frontend frontend/<NOSRV> 0/0/503/503/-1/-1/-1/503 200 73 - - LR-- 1/1/0/0/0 0/0 "GET / HTTP/1.1" - coraza-error:1 coraza-action:-
```
