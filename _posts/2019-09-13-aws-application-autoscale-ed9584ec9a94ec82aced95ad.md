---
ID: 12
post_title: '[AWS] Application AutoScale 필요사항'
author: chronosa
post_excerpt: ""
layout: post
permalink: 'http://13.124.99.87/2019/09/13/aws-application-autoscale-%ed%95%84%ec%9a%94%ec%82%ac%ed%95%ad/'
published: true
post_date: 2019-09-13 20:52:13
---
<!-- wp:list {"ordered":true} -->
<ol><li>라이센스 : 상용소프트웨어 사용중일 경우 라이센스에 대한 고려필요</li><li>세션 유지 : 솔루션별로 세션 클러스터링 구성을 위한 아키텍처 필요</li><li>OS 계정 관리 : AMI로 필요한 계정은 미리 생성 가능하지만 신규 계정 생성시 AMI 재생성 필요.</li><li>툴 호환 : 인스턴스 정보가 동적이기에 관련하여 Scale Out 시 툴 동작 여부 확인 필요</li><li>SG 사용 : rule 등록시 IP가 아닌 SG 사용 권고</li><li>로그 관리 : Scale-in 시의 터미네이트 대비 하여 실시간 통합 로그 관리 준비 필요.</li><li>ASG 설정 관련<ul><li>서비스에 맞는 scaling plan 옵션(dynamic scaling) 확인 후 활용<br>(<a href="https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/scaling_plan.html" target="_blank" rel="noreferrer noopener">https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/scaling_plan.html</a>)</li><li>인스턴스 종료시 사용자 지정 작업 수행 필요시 lifecycle-hooks 활용<br>(<a href="https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/lifecycle-hooks.html" target="_blank" rel="noreferrer noopener">https://docs.aws.amazon.com/ko_kr/autoscaling/ec2/userguide/lifecycle-hooks.html</a>)</li></ul></li><li>AMI 관리<ul><li>버젼 관리 필요</li><li>운영자에 의해 실수로 AMI가 삭제 되지 않게 구분 관리 필요</li></ul></li></ol>
<!-- /wp:list -->