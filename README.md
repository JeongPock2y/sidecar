# sidecar
일시적인 데이서 저장공간


해당 리파지토리 안에 html파일의 내용이   kubectl apply -f  해주면  여기를 저장소로 둔 사이드카기능으로  여기의 파일 이 나와짐

커밋해서  내용을 바꾸면 몇 초뒤   바뀜

/ # C:\kubernetes>kubectl run busybox --image=busybox --restart=Never --rm -it sh

/ # wget -q -O - http://192.168.22.73
<h1>hi<h1>
/ # wget -q -O - http://192.168.22.73
<h1>hi  -->   test 2<h1>

