역할 이름
=========
demoweb

요구사항
=========
RedHat 계열 (예: CentOS)에서만 설치 가능.

dnf, firewalld, ansible.builtin.template 모듈 사용.

역할 변수
=========
pkg_web	= 웹 서버 패키지 (httpd)

pkg_web_https	= HTTPS 모듈 패키지 (mod_ssl)

pkg_fw = 방화벽 패키지 (firewalld)

svc_web	= 웹 서버 서비스 (httpd)

svc_fw = 방화벽 서비스 (firewalld)

fwrule_http	= 방화벽에서 열어야 할 HTTP 포트

fwrule_https = 방화벽에서 열어야 할 HTTPS 포트

의존성
=========
별도의 외부 의존성 없음.

firewalld, systemd, dnf 모듈이 설치되어 있어야 함.

라이센스
=========	
GPL-2.0-or-later 또는 MIT

작성자
=========
진성은
