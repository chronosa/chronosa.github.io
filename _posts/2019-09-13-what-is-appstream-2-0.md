---
ID: 16
post_title: What Is AppStream 2.0
author: chronosa
post_excerpt: ""
layout: post
permalink: >
  http://13.124.99.87/2019/09/13/what-is-appstream-2-0/
published: true
post_date: 2019-09-13 20:55:58
---
<!-- wp:paragraph -->
<p>데스크톱 애플리케이션에 대해 즉각적인 액세스 권한을 제공하는 완전 관리형 애플리케이션 스트리밍 서비스<br>(HTML5 호환 웹 브라우저를 통한 모든 디바이스에서의 접근가능)</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="주요-개념">주요 개념</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p><strong>이미지 빌더</strong><br>이미지를 생성하는 데 사용하는 가상 머신</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>이미지</strong><br>Windows + App 설정이 포함된 이미지, AWS에서 제공하는 이미지를 통해서 시작해야 한다.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>플릿</strong><br>지정한 이미지를 실행하는 스트리밍 인스턴스 집합, 동적으로 조정되며 사용자 한 명당 하나의 인스턴스가 필요</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>스택</strong><br>사용자가 실제로 접근하게 되는 것.<br>플릿 + 액세스 정책 + 스토리지 구성으로 이루어짐.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><strong>사용자 풀</strong><br>사용자들을 관리</p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="포트">포트</h2>
<!-- /wp:heading -->

<!-- wp:image {"linkDestination":"custom"} -->
<figure class="wp-block-image"><a href="https://chronosa.github.io/images/appstream_required_port.GIF"><img src="https://chronosa.github.io/images/appstream_required_port.GIF" alt="required_port"/></a></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>기본적으로 80, 443 port가 필요.<br></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="프로토콜">프로토콜</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>NICE DCV 프로토콜 이용</p>
<!-- /wp:paragraph -->

<!-- wp:list {"ordered":true} -->
<ol><li>AppStream 2.0은 NICE Desktop Cloud Visualization(DCV)을 사용하여 사용자가 다양한 네트워크 조건에서 안전하게 액세스하고 애플리케이션을 스트리밍할 수 있게 합니다.</li><li>대역폭 소비를 줄일 수 있도록 NICE DCV는 H.264 기반 비디오 압축 및 인코딩을 사용합니다.</li><li>스트리밍 세션 중에 애플리케이션의 시각적 출력이 압축되고 HTTPS를 통해 AES-256 암호화된 픽셀 스트림으로 사용자에게 스트리밍됩니다.</li><li>스트림이 수신되면 암호화되고 사용자의 로컬 화면에 출력됩니다.</li><li>사용자가 스트리밍 애플리케이션과 상호 작용할 때, NICE DCV 프로토콜은 입력을 캡처하고 HTTPS를 통해 스트리밍 애플리케이션에 다시 보냅니다.<br><a href="https://docs.aws.amazon.com/ko_kr/appstream2/latest/developerguide/appstream2-dg.pdf" target="_blank" rel="noreferrer noopener">Amazon AppStream 2.0에 대한 사용자 연결</a></li></ol>
<!-- /wp:list -->