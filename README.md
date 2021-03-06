# [릴레이 프로젝트]3주차 (B기능)
## 🎈 3주차 구현 목표

* 채팅방에 접속한 A씨가 옷을 벗자 접속 유저들은 신고기능을 이용해 영상을 신고하였고, 관리자(AI)는 해당 영상을 유해동영상으로 판단하고, 접근을 제한하는 것 입니다.

<br>

## 🎈 체크포인트
* ✅ `http://49.50.160.6:3000/components` 주소로 접속시 여러개의 동영상이 확인된다.
* ✅ 동영상을 클릭한 화면에서 `신고하기` 버튼을 누르면 신고가 접수 되었다는 알림창이 뜬다.
* ✅ 사람의 신체부위가 많이 노출된 동영상의 경우 유해동영상으로 판단되는지 확인한다.
* ✅ 이 후 일정시간이 지난 후 유저가 신고한 동영상이 유해한 동영상인지, 아닌지 확인 알림창이 뜬다. (신고 후 알림창이 뜨기전까지 다른 작업을 진행해도 됩니다.)
* ✅ 만약 신고한 동영상이 유해영상이었다면 페이지가 리로드되고 동영상을 다시 클릭했을 때 차단되어 들어가지지 않는다.

<br>

## 🎈 데모 URL
* http://49.50.160.6:3000/components

<br>

## 🎈 데모 영상
* [데모영상](https://i.imgur.com/mAgNkWy.gifv)

<br>

## 🎈 참여자
* J008_강진구, J032_김동현, J041_김석중, J050_김은빈, J082_박은식, J089_박지홍, J103_신승현, J116_오정석, J145_이세은, J202_차효준

<br>

## 🎈 haburi Wiki ( 하부리 기획확인 링크)
* 화상채팅 서비스인 [하두리](https://namu.wiki/w/하두리) 사이트를 개선시키고자 한다.
* 자세한 설명은 [Wiki](https://github.com/boostcamp-2020/relay_09/wiki/하부리-Wiki)를 확인해주세요 :)

<br>
<br>

# [릴레이 프로젝트]2주차 (A기능)
## 🎈 2주차 구현 목표

* 채팅방 구현/동작(현재 채팅방은 하나에서 여러명이 사용하도록 해두었습니다.)
* 기본적인 레이아웃 구현

<br>

## 🎈 체크포인트
* ✅ 채팅을 분석하여 채팅의 감정을 예측하여 해당 화상 채팅을 보고있는 과반수 유저들의 감정을 추정
* ✅ 추정한 감정으로, 메인 페이지에서 보이는 영상에 Label을 붙여준다.
* ✅ 해당 영상 방 상단에 Label을 표시해준다.

<br>

## 🎈 개발 결과
* Django Server를 만들어서 API 서버처럼 사용할 수 있도록 하였습니다. (진행중)
* ...

<br>

## 🎈 참여자
* J206(최정은), J055(김진성), J056(김창윤), J091(박진영), J092(박진용), J129(윤영우), J166(이헌준), J128(윤석주), J017(권영언), J018(권예지), J167(이호영)

<br>

## 🎈 haburi Wiki ( 하부리 기획확인 링크)
* 화상채팅 서비스인 [하두리](https://namu.wiki/w/하두리) 사이트를 개선시키고자 한다.
* 자세한 설명은 [Wiki](https://github.com/boostcamp-2020/relay_09/wiki/하부리-Wiki)를 확인해주세요 :)