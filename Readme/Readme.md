![SpirngSecurity 필터 구조](https://gitlab.com/jongwons.choi/spring-boot-security-lecture/-/raw/master/images/fig-2-spring-big-picture.png)

- 중요한 점은 Config File 하나당 하나의 필터로서 조건을 걸어준다는 사실

    -> 여기서 @Order 를 걸어 걸리는 필터의 순서를 정해준다는 사실 명심하자!

