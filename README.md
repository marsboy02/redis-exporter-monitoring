# redis-exporter-monitoring

- redis-exporter를 사용해서 모니터링하는 소스 코드의 예제입니다.
- redis <-> redis-exporter <-> prometheus <-> grafana를 사용합니다.

## quick start

### docker-compose

```bash
docker-compose up
```

### python

```bash
# 가상 환경 생성
python3 venv .venv
```

```bash
# 가상 환경 실행
source venv/bin/activate
```

```bash
# redis 설치
pip3 install redis
```

```bash
# 스크립트 실행
python3 annoying-redis.py
```

```bash
# 가상 환경 종료
deactivate
```
