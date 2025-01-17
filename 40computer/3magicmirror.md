---
sort: 3
---

# PhotoAlbum with RaspberryPi 3A

**집에 게임기로 쓰려고 빼두었던 라즈베이파이 3A로 만든 매직미러 프로젝트.    
구현된 프로그램을 불러다가 내 라즈베리파이에 잘 설치만 하면 되는데..**    

본래 이 프로그램의 이름이 매직미러인 이유는     
거울처럼 만들어서 평상시에 거울에 시간과 날씨 등등을 띄워서 활용하라는 의미이다.    
하지만 거울보다 포토앨범을 구현하고 싶었다.    
우리집에서는 매일 수십~수백장의 사진을 찍기 때문에 매우 유용하겠다는 생각이 들었다.

프로그램을 불러다가 잘 설치만 하면 되지만 역시 상당히 많은 시행착오 발생.    
대표적으로는     
```note    
시놀로지 NAS로부터 사진 불러오기 위해 NFS(Network File System) 설정    
NPM(Node Package Manager) 설치 및 사용을 위한 package.json 파일 생성    
매직미러 프로그램에서 사진을 슬라이드쇼 하기 위한 모듈 설치(MMM-BackgroundSlideshow)    
```

이외에도 config파일 수정하면서 날씨api연동, 사진의 특성 및 권한에 따른 실행중 뻗음,    
사진 리사이즈 설정 등등 난관을 지나면서     
작은 프로젝트지만 많은 경험을 할 수 있었다.     
결과적으로 잘 띄우니 그만큼 또 만족스러운 결과 ^^.    

![image](https://user-images.githubusercontent.com/48585035/232506426-f05d8ce8-69e4-4dea-bb75-531bd9a4ccca.jpeg)

![image](https://user-images.githubusercontent.com/48585035/232506429-c8e25a48-1ca8-4fc6-a702-ad8ad652c85a.jpeg)

