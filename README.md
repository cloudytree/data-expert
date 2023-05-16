## source
소스 폴더 백업용

## git 초기화 
```
$ git init 
```

## git 계정 설정 
```
$ git config --global user.name cloudytree    
$ git config --global user.email woojintree@gmail.com 
```

## windows C:/ 디렉토리 접근 권한 발생 시, 실행  
```
$ git config --global --add safe.directory C:/source 
```

## 원격 저장소 설정 
```
$ git remote add origin https://github.com/cloudytree/source.git
```

## 원격 저장소를 처음 가져올 때 
```
$ git clone https://github.com/cloudytree/source.git  
```

## 원격 저장소와 Sync , 최신 커밋 가져오기 
```
$ git pull https://github.com/cloudytree/source.git
```

## 소스 커밋 
```
$ git add .
$ git commit -m "커밋 메시지"
```

## Branch 이름 변경 ( master가 아닌 경우 )
```
$ git branch -M main  
```

## 원격 저장소로 Push 
```
$ git push -u origin main 
```

## 상태 확인 
```
$ git status 
```

## Commit 변경 사항 추적
```
$ git log
```

