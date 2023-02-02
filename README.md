# k8s-teslamate


# 아래의 과정이 진행되었습니다.

1. kcompose
```
# 공식 문서에 있는 docker-compose를 아래의 명령을 통해 변환
kompose convert -c
```
2. 실제 적용 가능하게 yaml 내용들 수정 진행

3. Package 생성
```
helm package helm
```
4. helm index 생성
```
helm repo index .
```

# 참고
#### Teslamate의 최신 버전 확인 방법
```
curl https://api.github.com/repos/adriankumpf/teslamate/releases/latest -s | jq .name -r
```
