## 👤 멘토 소개

 **최한동**

안녕하세요. 2년 차 보안 엔지니어로 스타트업에서 주로 보안 취약점 진단/분석을 담당하며, 필요에 따라 DevSecOps 업무를 맡고 있습니다. Chromium, Let's Encrypt, OWASP, uftrace 등 다양한 오픈소스에 기여했고, 기존의 불편함을 해결하는 새로운 아이디어 찾기를 좋아합니다.

## 🎯 멘토링 목표

- Git, GitHub에 익숙해지고 오픈소스 생태계의 개발 문화, 보안성 현황에 대해 알아본다.
- 원하는 오픈소스를 fork하고, 직접 기여하며 협업할 수 있는 다양한 방법에 대해 알아본다.
- 보안 관련 오픈소스에 PR, Issues, Discussions로 참여하거나, 취약점을 진단/분석하고 오픈소스 생태계에 기여할 수 있는 방향으로 스터디를 진행한다.

## 📆 기간 및 일정

- 9월 12일 ~ 12월 예정
- 13 ~ 14주

## 📜 커리큘럼

- [1주차] OT
    - 9월 12일 오후 12시 Google Meet 온라인 미팅
    - 멘토, 멘티 간단 소개
    - 멘토링, 스터디에 관한 의견 수렴 및 논의 (계획, 방향)
    - GitHub repository 초대 및 Pacu, Terrascan 오픈소스 공유
- [2주차] GitHub, 오픈소스 보안 기초
    - 9월 19일 오후 12시 Google Meet 온라인 미팅
    - git clone OWASP Juice Shop (로컬 세팅)
    - OWASP Top 10 2021 전달, GitHub Explore > Trending, GitHub Security 탭 설명
    - GitHub Actions (Workflow) 설명 (CodeQL 간단 맛보기 설명)
    - 과제
        
        bunkerized-nginx 리눅스 세팅
        
        [https://github.com/bunkerity/bunkerized-nginx#linux](https://github.com/bunkerity/bunkerized-nginx#linux)
        
        GitHub에서 관심있는 오픈소스 10개 스타, 좀 더 분석/진단해보고 싶은 오픈소스 3개 포크 & 로컬 세팅
        
        [https://github.com/topics](https://github.com/topics)
        
        [https://github.com/topics/webapp](https://github.com/topics/webapp)
        
        Udemy 온라인 강의 (ID: wschd770@gmail.com, PW: 1q2w3e4r)
        
        - 화이트해커가 되기 위한 8가지 웹 해킹 기술 (4시간)
        
        [https://www.udemy.com/course/everything-about-white-hat-hacker/](https://www.udemy.com/course/everything-about-white-hat-hacker/)
        
        - 화이트해커가 되기 위한 모의해킹 완전정복 (6시간)
        
        [https://www.udemy.com/course/penetration-testing-for-white-hat-hacker/](https://www.udemy.com/course/penetration-testing-for-white-hat-hacker/)
        
        (고급) Finding security vulnerabilities in JavaScript with CodeQL - GitHub Satellite 2020 (1시간 30분)
        
        [https://www.youtube.com/watch?v=pYzfGaLTqC0](https://www.youtube.com/watch?v=pYzfGaLTqC0)
        
- [3주차] 오픈소스 진단 준비
    - 10월 3일 오후 7시 Google Meet 온라인 미팅
    - bunkerized-nginx 관련 에러 해결 진행 (설치 에러 해결)
        - 권한, 사용 중인 포트 에러
        - Docker로 설치 및 실행
        - 도메인 발급 → Let's Encrypt 인증서 에러 제거 → 구동 테스트 필요
    - GitHub 내 오픈소스 활용, 진단 시 알아야할 사항 (기준) 정리
    - SAST, DAST 설명 

    - 과제
        
        1, 2주차 내용 정리 포스팅 완료하기 (+2주차 과제 마무리)
        
        도메인 발급하기 (가비아, 닷홈)
        
        Cloudflare 가입 및 계정 생성
        
        bunkerized-nginx 공식 문서
        [https://bunkerized-nginx.readthedocs.io/en/latest/index.html](https://bunkerized-nginx.readthedocs.io/en/latest/index.html)
        
- [4주차] 오픈소스 진단 준비
    - 10월 10일 오후 5시 Google Meet 온라인 미팅
    
    - Juice Shop 진행 방식 확정
        - CTF 형식이 아닌 모의해킹 형식 채택
        - 스코어보드 안내 → 찾은 취약점 현황 확인
        - juice shop walkthrough 검색 후 확인
            
            [https://github.com/juice-shop/juice-shop/blob/master/SOLUTIONS.md](https://github.com/juice-shop/juice-shop/blob/master/SOLUTIONS.md)
            
    - bunkerized-nginx certbot 인증서 발급 문제 해결 중
        
        Let's Encrypt에서 발행될 인증서에 필요한 도메인 요구사항? → 서버의 IP가 필요하지만, bunkerized-nginx를 실행시키는 로컬 환경, VM 환경에서 제대로 동작하지 않음 (라우팅 문제? 방화벽 문제?) → 클라우드 인스턴스에서 재시도하기
        
        [https://www.lesstif.com/lpt/sudo-echo-permission-denied-89556053.html](https://www.lesstif.com/lpt/sudo-echo-permission-denied-89556053.html)
        
        [https://rtfm.co.ua/en/lets-encrypt-ssl-and-the-servfail-looking-up-caa-for-domain-com-error/](https://rtfm.co.ua/en/lets-encrypt-ssl-and-the-servfail-looking-up-caa-for-domain-com-error/)
        
    - 참고 링크
        
        [https://saucelabs.com/blog/discovering-security-vulnerabilities-with-selenium](https://saucelabs.com/blog/discovering-security-vulnerabilities-with-selenium)
        
        [https://www.bunkerity.com/make-your-web-services-secure-by-default-with-bunkerized-nginx/](https://www.bunkerity.com/make-your-web-services-secure-by-default-with-bunkerized-nginx/)
        
        [https://ex0a.medium.com/tryhackme-owasp-juice-shop-53e87fb1af36](https://ex0a.medium.com/tryhackme-owasp-juice-shop-53e87fb1af36)
        
    - 과제
        - [Juice Shop 모의해킹] 취약점 3개 찾기
        [https://pwning.owasp-juice.shop/part1/rules.html](https://pwning.owasp-juice.shop/part1/rules.html)
        - opensource-security-sua에 진단할 repo 3개, Juice Shop, bunkerized-nginx 올리기
        - Cloudflare + Nginx
        [https://www.digitalocean.com/community/tutorials/how-to-host-a-website-using-cloudflare-and-nginx-on-ubuntu-20-04](https://www.digitalocean.com/community/tutorials/how-to-host-a-website-using-cloudflare-and-nginx-on-ubuntu-20-04)
        
- [5주차] 개별 스터디 진행
    - 10월 17일 오후 4시 Google Meet 온라인 미팅
    
    - Cloudflare + Nginx
        
        Nginx 구축은 로컬 VM에서 진행했으나 연결시킨 커스텀 도메인으로 외부에서 접속이 되지 않는 현상이 지속적으로 발생 (522 에러) → 클라우드로 마이그레이션 보류 (오프라인 스터디 때 진행)
        
    - CI/CD (GitHub Actions) 및 DevSecOps 파이프라인
        
        클라우드 마이그레이션 때 같이 공부할 예정
        
    - 과제
        - [Juice Shop 모의해킹] 취약점 3개 찾기
        [https://pwning.owasp-juice.shop/part1/rules.html](https://pwning.owasp-juice.shop/part1/rules.html)
        
- [6주차] 개별 스터디 진행
    - 10월 25일 오후 10시 Google Meet 온라인 미팅
    - Juice Shop 풀이 검토 → 모의해킹 취약점 3개씩 진행 유지 (생각보다 갑자기 풀리는 문제들이 많았음)
    - 취약한 코드, 안전한 코드 작성 시 형식
        
        xss_vuln.go, xss_safe.go
        
        [취약점 약어]_[vuln or safe].[확장자]
        
    
    - 참고 링크
        
        [http://golang.site/go/article/1-Go-프로그래밍-언어-소개](http://golang.site/go/article/1-Go-%ED%94%84%EB%A1%9C%EA%B7%B8%EB%9E%98%EB%B0%8D-%EC%96%B8%EC%96%B4-%EC%86%8C%EA%B0%9C)
        
        [https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git](https://docs.github.com/en/get-started/getting-started-with-git/caching-your-github-credentials-in-git)
        
        [https://stackoverflow.com/a/50700468](https://stackoverflow.com/a/50700468)
        
        [https://cli.github.com/manual/gh_auth_login](https://cli.github.com/manual/gh_auth_login)
        
    - 과제
        - [Juice Shop 모의해킹] 취약점 3개 찾기
        [https://pwning.owasp-juice.shop/part1/rules.html](https://pwning.owasp-juice.shop/part1/rules.html)
        - 블로그 글 업데이트 + 작성한 코드 GitHub에 올리기
        
        - Secure Coding Guidelines for Java SE
            
            [https://www.oracle.com/java/technologies/javase/seccodeguide.html](https://www.oracle.com/java/technologies/javase/seccodeguide.html)
            
            공부할 섹션: 0, 1
            
        - OWASP ZAP 공부
            
            [https://www.zaproxy.org/docs/desktop/start/](https://www.zaproxy.org/docs/desktop/start/) 페이지에서 Features에 있는 모든 기능 실습
            
            [https://www.zaproxy.org/getting-started/](https://www.zaproxy.org/getting-started/) 페이지에서 Automation 섹션 전까지 실습
            
- [7주차] 개별 스터디 진행
    - 10월 30일 오후 4시 Google Meet 온라인 미팅
    - Juice Shop 풀이 검토 → 모의해킹 취약점 3개씩 진행 유지
    - 취약한 코드, 안전한 코드 작성 후 파일 (코드) 실행까지 할 필요 없음 (모의해킹, 취약점 진단 분석할 때는 굳이 전체 프로그램이 아니어도 특정 코드에 어떤 취약점이 있는지 아는 게 더 중요하기 때문) → 다시 진행 필요 (코드를 파일에 작성'만' 하기)
    
    - 참고 링크
        
        [https://docs.github.com/en/actions/learn-github-actions](https://docs.github.com/en/actions/learn-github-actions)
        
        golang dynamic analysis
        
        [https://owasp.org/www-community/Free_for_Open_Source_Application_Security_Tools](https://owasp.org/www-community/Free_for_Open_Source_Application_Security_Tools)
        
        [https://blog.trailofbits.com/2019/11/07/attacking-go-vr-ttps/](https://blog.trailofbits.com/2019/11/07/attacking-go-vr-ttps/)
        
    - 과제
        - 이번 주차 블로그 글 업데이트
        - Juice Shop 모의해킹 취약점 3개 찾기
        - GitHub Actions 공부
            
            아래 링크나 구글링을 통해 GitHub Actions를 사용해보기 (GitHub Actions 사용을 위해 만드는 저장소 이름은 opensource-security-sua-ga 로 해주세요. 이 안에서 만드는 워크플로우 파일 이름은 기본 값으로 해도 됩니다)
            
            [https://velog.io/@ggong/Github-Action에-대한-소개와-사용법](https://velog.io/@ggong/Github-Action%EC%97%90-%EB%8C%80%ED%95%9C-%EC%86%8C%EA%B0%9C%EC%99%80-%EC%82%AC%EC%9A%A9%EB%B2%95)
            
            [https://zzsza.github.io/development/2020/06/06/github-action/](https://zzsza.github.io/development/2020/06/06/github-action/)
            
        - GitHub 저장소 업데이트 (opensource-security-sua)
            
            작성한 모든 취약한 코드, 안전한 코드를 자신의 디렉토리에 넣고, 자기 브랜치인 상태에서 원격으로 푸시


## 📘 참고자료

- 스터디 저장소 (GitHub)
    
    [henrychoi7/opensource-security-sua](https://github.com/henrychoi7/opensource-security-sua)
    
- Golang 진단 및 분석
    
    [https://codeql.github.com/docs/codeql-language-guides/codeql-for-go/](https://codeql.github.com/docs/codeql-language-guides/codeql-for-go/)
    
    [https://github.com/github/codeql-go](https://github.com/github/codeql-go)
    
    [https://github.com/OWASP/Go-SCP](https://github.com/OWASP/Go-SCP) (+PDF)
    
    [https://github.com/securego/gosec](https://github.com/securego/gosec)
    
    [https://github.com/praetorian-inc/gokart](https://github.com/praetorian-inc/gokart)
    
- Java 진단 및 분석
    
    [https://codeql.github.com/docs/codeql-language-guides/codeql-for-java/](https://codeql.github.com/docs/codeql-language-guides/codeql-for-java/)
    
    [https://github.com/guardrailsio/awesome-java-security](https://github.com/guardrailsio/awesome-java-security)
    
- 무료 오픈소스 애플리케이션 보안 도구 목록
    
    [https://owasp.org/www-community/Free_for_Open_Source_Application_Security_Tools](https://owasp.org/www-community/Free_for_Open_Source_Application_Security_Tools)
    
- SAST 도구 목록
    
    [https://owasp.org/www-community/Source_Code_Analysis_Tools](https://owasp.org/www-community/Source_Code_Analysis_Tools)
    
- 클라우드, 인프라 관련 취약점 진단 도구 (오픈소스)
    
    Pacu: [https://github.com/RhinoSecurityLabs/pacu](https://github.com/RhinoSecurityLabs/pacu)
    
    Terrascan: [https://github.com/accurics/terrascan](https://github.com/accurics/terrascan)
    
- 보안에 취약한 오픈소스 웹, 모바일, OS 프로젝트 목록 (2018)
[https://www.yeahhub.com/vulnerable-web-mobile-os-projects/](https://www.yeahhub.com/vulnerable-web-mobile-os-projects/)
- Awesome 목록
    
    [https://github.com/decalage2/awesome-security-hardening](https://github.com/decalage2/awesome-security-hardening)
    
    [https://github.com/enaqx/awesome-pentest](https://github.com/enaqx/awesome-pentest)
    
    Web
    
    [https://github.com/infoslack/awesome-web-hacking](https://github.com/infoslack/awesome-web-hacking)
    
    [https://awesomehacking.org/#web](https://awesomehacking.org/#web)
    
- GitHub Security Lab
    
    [https://github.com/github/securitylab](https://github.com/github/securitylab)
    
- 블로그 과제 양식 설명 (참고: [https://blog.naver.com/kim950210/222264901600](https://blog.naver.com/kim950210/222264901600))