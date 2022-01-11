# 베이스 이미지
FROM debian:9.5-slim 

# 이 이름의 스크립트를 만드는듯?
ADD entrypoint.sh /entrypoint.sh  

# 실행권한부여
RUN chmod +x /entrypoint.sh

# 이미지는 아래 스크립트를 실행
ENTRYPOINT ["/entrypoint.sh"]
