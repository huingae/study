# github 만들기

---

## git 만들기

1. 정해진 위치에 저장소를 만든다 
```shell
$git clone [저장소 주소]
$cd [저장소이름/] && start .
```

2. 필요한 데이터 작성 ex) touch README.md
3. 데이터를 첨부
```shell
$git add README.md	//파일의 개수 100개이상, 100MB 이상, 한달에 1기가 이상은 제한된다
```
4. 첨부된 데이터의 내용을 작성
```shell
$git commit -m "데이터의 내용"
```
5. 상태를 자주 확인해 볼 것
```shell
$git status			//붉은색 글씨-첨부가 되지 않았음
					//녹색 글씨-첨부가 완료되었음
					//내용없음-전송할 자료가 없거나 이미 commit된 자료뿐일 때
```
6. 데이터 전송
```shell
$git push
```

*깃허브 사이트에서 수정한 자료를 동기화
```shell
$git pull

```









에러가 생겼을때는 이런 모양이다.