---
ID: 18
post_title: 'Windows Tiny Tip &#8211; 1'
author: chronosa
post_excerpt: ""
layout: post
permalink: >
  http://13.124.99.87/2019/09/13/windows-tiny-tip-1/
published: true
post_date: 2019-09-13 20:59:05
---
<!-- wp:heading -->
<h2 id="vm에서-public-ip-확인하는-방법">vm에서 public ip 확인하는 방법</h2>
<!-- /wp:heading -->

<!-- wp:table -->
<table class="wp-block-table"><tbody><tr><td>1<br></td><td>curl ifconfig.co<br></td></tr></tbody></table>
<!-- /wp:table -->

<!-- wp:heading -->
<h2 id="Windows-OS-Password-변경하는-방법-CLI">Windows OS Password 변경하는 방법 (CLI)</h2>
<!-- /wp:heading -->

<!-- wp:heading {"level":1} -->
<h1 id="Windows-2016-Only">Windows 2016 Only</h1>
<!-- /wp:heading -->

<!-- wp:table -->
<table class="wp-block-table"><tbody><tr><td>1<br>2<br>3<br></td><td>$newpwd = ConvertTo-SecureString -String "1qaz@WSX3EDC" -AsPlainText -Force<br>$UserAccount = Get-LocalUser -Name "test"<br>$UserAccount | Set-LocalUser -Password $newpwd<br></td></tr></tbody></table>
<!-- /wp:table -->

<!-- wp:heading {"level":1} -->
<h1 id="Windows-2012-2016">Windows 2012, 2016</h1>
<!-- /wp:heading -->

<!-- wp:table -->
<table class="wp-block-table"><tbody><tr><td>1<br></td><td>net user test password123!<br></td></tr></tbody></table>
<!-- /wp:table -->