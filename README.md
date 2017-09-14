# Youtube
- 썸네일 보이기

#### cueVideo
- 지정한 동영상의 미리보기 이미지를 로드하고 플레이어가 동영상을 재생하도록 준비하지만 play()를 호출하기 전에는 동영상 스트림을 다운로드하지 않음.
```java
@Override
   public void onInitializationSuccess(YouTubePlayer.Provider provider, YouTubePlayer youTubePlayer, boolean b) {
   youTubePlayer.cueVideo("IA1hox-v0jQ");
}
```

#### YouTubePlayer.Provider
- 초기화하는데 사용
```java
getYouTubePlayerProvider().initialize(DeveloperKey.DEVELOPER_KEY,this);
```


---
> Gradle - app - signingReport에서 SHA1 복사해서 프로젝트 생성해야 함

> Google API Console 개발자 콘솔에서 Key 발급받기
