# k8s-teslamate

#### Teslamate의 최신 버전 확인
```
curl https://api.github.com/repos/adriankumpf/teslamate/releases/latest -s | jq .name -r
```

# kcompose
```
kompose convert -c
```

# Package 생성
```
helm package helm
```

# helm index 생성
```
helm repo index .
```