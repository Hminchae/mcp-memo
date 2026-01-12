
- **루트는 버전/공통 규칙만** (의존성 거의 X)
- **서비스 모듈은 자기 필요한 의존성만** (label/timetable 각각)
- **common은 ‘표준/전송/유틸/클라이언트’만** (비즈니스/엔티티 금지)


## ✅ 루트에서 관리할 것
- 플러그인 버전(boot, dependency-management)만
- 공통 group/version/repositories
- 공통 Java 17 toolchain
- (선택) Lombok 공통 주입