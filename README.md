# PerfectSinger
네이버 D2 CAMPUS FEST 지원 프로젝트 파일입니다.<br> 
소개 Slide_Share 링크 : http://www.slideshare.net/ssuser03cf4b/perfectsinger <br>
소개 Youtube 링크 : https://youtu.be/W0MvUCyPXKk
# 프로젝트 소개
사용자의 음역대에 따른 노래 추천 어플리케이션 < 나도가왕 - Perfect Singer >
 처음 저희는 한국인을 위한 서비스를 만들어 보고 싶었습니다. 
 현재 우리나라 어느 곳을 가더라도 노래방이 존재할 정도로 우리들은 노래 부르기를 좋아하는 민족이라는 것을 확인할 수 있습니다.
 모두들 노래방을 가면 자신이 잘 부르는 노래를 부르고 싶어하지만 노래방에 자주 가는 이들 조차도
 자신이 음이탈 없이 편안하게 부를수 있는 노래가 무엇인지 찾는 것은 힘들 일입니다.
 그래서 사용자의 목소리의 음역대를 확인하여 노래를 추천해 주는 서비스를 생각하게 되었습니다.
#핵심 기능
1) 사용자의 음역대를 확인하는 기능 <br>
2) 음역대에 맞는 노래를 추천해 주는 기능<br>
3) 음역대에 따른 난이도별 추천기능
#기본적인 알고리즘
사용자 계정 설정 (나이 및 성별) <br>
-> 음역대의 낮은 음을 찾는 단계 ( 단계별로 피아노음을 들려주고 그 음을 불렀을때 통과 ) <br>
-> 음역대의 높은 음을 찾는 단계 (낮은 음 찾는 방법과 같다 ) <br>
-> 사용자의 음역대에 따른 노래 추천
#사용한 오픈 소스
-"Back.java" = 뒤로가기 버튼을 2번 눌렀을 때 어플리케이션 종료 코드 <br> http://blog.naver.com/alens82/220734956642<br>
-"ca"폴더 = 시간에따른 목소리 Data를 주파수에 따른 Data로 바꿔주는 FFT 코드 <br>http://www.programcreek.com/java-api-examples/index.php?source_dir=Scrambled-Net-master/HermitLibrary/src/ca/uol/aig/fftpack/Complex1D.java# <br>www.netlib.org/fftpack<br>
-"AudioProcessing.java" = 주파수에 따른 목소리 Data를 막대 그래프로 시각화 하는 코드 출처<br>책) 프로 안드로이드 미디어 - 그래픽, 오디오, 비디오를 비롯한 리치 미디어 앱 개발하기
