## About

Buzzvil에서 서버 엔지니어로 일하고 있습니다. 분산 시스템과 데이터 정합성 문제를 공부하고, 이해한 내용을 글로 정리합니다.

## Featured writing

### [Redis 분산 락은 정말 안전한가](https://medium.com/@chotnt741/redis-%EB%B6%84%EC%82%B0-%EB%9D%BD%EC%9D%80-%EC%A0%95%EB%A7%90-%EC%95%88%EC%A0%84%ED%95%9C%EA%B0%80-d914c256511f)

Redis 락은 항상 안전한가를 살펴본 글입니다. 단일 Redis 인스턴스의 비동기 복제 문제와 Redlock의 시간 가정을 정리하고, 클라이언트가 멈췄다가 깨어날 때 발생할 수 있는 오래된 쓰기를 펜싱 토큰으로 막는 방법을 다룹니다.

정합성이 중요한 작업은 분산 락부터 선택하기보다 DB 제약이나 조건부 UPDATE를 먼저 검토하고, Redis 락은 중복이 치명적이지 않은 작업에 사용하는 것이 더 단순할 수 있다는 관점을 담았습니다.

## Experience

**[Buzzvil](https://www.buzzvil.com/)** · Server Engineer  
Apr 2025 - Present

## Recent writing

<!-- BLOG-POST-LIST:START -->
- [Istio Ingress와 ClusterIP의 역할과 요청 흐름](https://junghwancho.tistory.com/19)
- [DNS Search Domain이란 무엇일까 (feat. Kubernetes)](https://junghwancho.tistory.com/16)
- [Python의 datetime은 타임존을 어떻게 다룰까 - aware과 naive 이해하기](https://junghwancho.tistory.com/15)
<!-- BLOG-POST-LIST:END -->

[All posts on Tistory](https://junghwancho.tistory.com/)
