---
layout: post
title: How to uninstall Cpanel from Centos 6 server
date: 2015-05-27 07:20:19.000000000 +08:00
type: post
published: true
status: publish
categories: []
tags: []
meta:
  sharing_disabled: '1'
  _rest_api_published: '1'
  _rest_api_client_id: "-1"
  _publicize_job_id: '11053722212'
author:
  login: paragasu
  email: paragasu@gmail.com
  display_name: paragasu
  first_name: ''
  last_name: ''
---
    #yum erase 'centos*'


Make sure to edit the _/etc/yum.conf_ to remove the packages listed in the exclude section

    [main]
    exclude= ..



