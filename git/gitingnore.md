## gitingnore

> git으로 추척하지 않을 파일 또는 폴더를 정의

git으로 관리되고 있는 로컬 저장소에 `.gitignore`파일을 만든다.

```bash
*.xlxs  	# 특정 확장자 제외
secret.csv 	# 특정 파일
tests/ 		# 특정 폴더
!tests/setting.txt 		# setting.txt 빼고 (NOT OPTION)
```

* 일반적으로 운영체제와 관련된 파일, 개발 환경(IDE, text editor), 특정 프레임워크 혹은 언어에서 메인 소스코드가 아닌 경우
  * http://gitignore.io/ 에서 참고할 수도 있다.
    * ex) `windows`, `java-web`, `eclipse`

