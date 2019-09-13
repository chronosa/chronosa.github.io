---
ID: 14
post_title: 'Azure Fundamentals &#8211; 1'
author: chronosa
post_excerpt: ""
layout: post
permalink: >
  http://13.124.99.87/2019/09/13/azure-fundamentals-1/
published: true
post_date: 2019-09-13 20:53:15
---
<!-- wp:heading -->
<h2 id="Geographies">Geographies</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>An Azure geography is a discrete market typically containing two or more regions that preserve data residency and compliance boundaries.<br><a href="https://docs.microsoft.com/en-us/learn/modules/explore-azure-infrastructure/3-geographies" target="_blank" rel="noreferrer noopener">출처</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>각 Azure 지역은 한 지리적 위치에 속하며 특정 서비스 가용성, 규정 준수 및 데이터 상주/주권 규칙이 적용됩니다.<br><a href="https://docs.microsoft.com/ko-kr/learn/modules/explore-azure-infrastructure/3-geographies" target="_blank" rel="noreferrer noopener">출처</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="Availability-Zones">Availability Zones</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>Azure services that support Availability Zones fall into two categories:</p>
<!-- /wp:paragraph -->

<!-- wp:list -->
<ul><li>Zonal services : you pin the resource to a specific zone (for example, virtual machines, managed disks, IP addresses)</li><li>Zone-redundant services : platform replicates automatically across zones (for example, zone-redundant storage, SQL Database).<br><a href="https://docs.microsoft.com/en-us/learn/modules/explore-azure-infrastructure/4-availability-zones" target="_blank" rel="noreferrer noopener">출처</a></li></ul>
<!-- /wp:list -->

<!-- wp:heading -->
<h2 id="Region-Pairs">Region Pairs</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>각 Azure 지역은 300마일 이상 떨어져 있는 동일한 지리적 위치(예: 미국, 유럽 또는 아시아) 내의 다른 Azure 지역과 항상 쌍을 이룹니다.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p>Azure 지역 쌍의 예로는 미국 동부와 미국 서부 쌍, 동남 아시아와 동아시아 쌍이 있습니다.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="https://docs.microsoft.com/ko-kr/learn/modules/explore-azure-infrastructure/5-region-pairs" target="_blank" rel="noreferrer noopener">출처</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="SLA">SLA</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>일반적인 SLA는 해당하는 각 Azure 제품 또는 서비스의 성능 목표 약정을 99.9%(“3개의 9”)에서 99.999%(“5개의 9”) 사이에서 지정합니다. 이러한 목표는 서비스의 작동 시간 또는 응답 시간 같은 성능 기준에 적용할 수 있습니다.<br>다음 표는 여러 시간 동안 다양한 SLA 수준의 잠재적인 누적 가동 중지 시간을 보여줍니다.</p>
<!-- /wp:paragraph -->

<!-- wp:image {"linkDestination":"custom"} -->
<figure class="wp-block-image"><a href="https://chronosa.github.io/images/azure_sla.GIF"><img src="https://chronosa.github.io/images/azure_sla.GIF" alt="Azure_SLA"/></a></figure>
<!-- /wp:image -->

<!-- wp:paragraph -->
<p>예를 들어 Azure Cosmos DB(Database) 서비스 SLA는 99.999% 작동 시간을 제공하며, 여기에는 DB 읽기 작업뿐만 아니라 DB 쓰기 작업에서도 10밀리초 미만의 짧은 대기 시간이 포함됩니다.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="https://docs.microsoft.com/ko-kr/learn/modules/explore-azure-infrastructure/6-service-level-agreements" target="_blank" rel="noreferrer noopener">출처</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="복원력-Resiliency">복원력(Resiliency)</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>복원력은 오류를 복구하여 계속 작동하는 시스템 기능입니다. 오류를 방지하는 것이 아니라 가동 중지 또는 데이터 손실을 방지하는 방법으로 오류에 대응하는 것입니다. 복원력의 목표는 오류가 발생한 후 애플리케이션을 완전히 작동하는 상태로 되돌리는 것입니다. 복원력의 두 가지 중요한 측면은 고가용성과 재해 복구입니다.</p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="https://docs.microsoft.com/ko-kr/learn/modules/explore-azure-infrastructure/8-improve-app-slas" target="_blank" rel="noreferrer noopener">출처</a></p>
<!-- /wp:paragraph -->

<!-- wp:heading -->
<h2 id="Application-availability">Application availability&nbsp;</h2>
<!-- /wp:heading -->

<!-- wp:paragraph -->
<p>The overall time that a system is functional and working.<br><a href="https://docs.microsoft.com/en-us/learn/modules/explore-azure-infrastructure/9-summary" target="_blank" rel="noreferrer noopener">출처</a></p>
<!-- /wp:paragraph -->

<!-- wp:paragraph -->
<p><a href="https://docs.microsoft.com/ko-kr/learn/paths/azure-fundamentals/" target="_blank" rel="noreferrer noopener">Azure 기본사항</a></p>
<!-- /wp:paragraph -->