# webrtc-mentoring
webrtc based mentoring website development for '2020 솔직 챌린지' (not submitted, uncompleted)

webrtc original code from : https://github.com/googlecodelabs/webrtc-web/tree/master/step-05
/*
 *  Copyright (c) 2014 The WebRTC project authors. All Rights Reserved.
 *
 *  Use of this source code is governed by a BSD-style license
 *  that can be found in the LICENSE file in the root of the source
 *  tree.
 */

...and original version of html form from : 
/*!
    * Start Bootstrap - Freelancer v6.0.4 (https://startbootstrap.com/themes/freelancer)
    * Copyright 2013-2020 Start Bootstrap
    * Licensed under MIT (https://github.com/StartBootstrap/startbootstrap-freelancer/blob/master/LICENSE)
    */
   
   !! Warning
   The Camera would never work without following the set-up steps below.
   This way you can work it with local network only, STUN or TURN Server needed for broad area communication.
   
   npm install and basic setting before work this code :
   https://forest71.tistory.com/211 (Korean)
   
   you'll also need OpenSSL to work it properly : 
   https://m.blog.naver.com/PostView.nhn?blogId=baekmg1988&logNo=221454486746&proxyReferer=https:%2F%2Fwww.google.com%2F (Korean)
   
  한국어 설명 :
  
  해당 코드는 2020년 '솔직 챌린지' 응모를 위해 개발한 것으로, 아동 학대 모니터링 기능을 추가한 webrtc 기반의 멘토링 사이트를 구현하는 것이 목표였습니다.
  
  웹캠은 npm 설치와 OpenSSL 세팅 이전에는 작동하지 않을 것입니다. 링크된 주소를 참고하여 설치해주세요.
  
  웹캠 설정이 제대로 되지 않으면 웹캠 부분이 빈 상태의 사이트가 나올 것입니다.
  
  해당 코드와 설정을 통해 로컬 네트워크(ex. 동일된 WIFI로 연결된 두 대의 기기) 를 통한 화면 공유가 가능합니다.
  
  webrtc는 peer-to-peer 서버 기반으로 작동하기 때문에, STUN서버나 TURN 서버 적용 이전에는 멀리서 통신하는 용도로는 사용 불가능할 것입니다.

