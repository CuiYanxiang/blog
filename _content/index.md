---
layout: index
title: Hello World!
category : index
tagline: "Supporting tagline"
tags : []
---

��ӭ�Ķ�[bootlog](https://github.com/jasonqu/bootlog)�Ŀ�������˵����������ʹ��˵�����ĵ���μ�[bootlog in github](https://github.com/jasonqu/bootlog)��
��ʾ���Ĵ��붼������[bootlogDemo](https://github.com/jasonqu/bootlogDemo)��Ŀ�С�

## bootlog��ʲô

bootlog�ǻ���sbt��twirl��pegdown��bootstrap��bootflat������һ����̬������������Ŀ���û���scala��java�Լ�githubʹ���ߡ�

## Update configuration

In `conf/blog.conf` remember to specify your own data:

    site.title : My Blog =)
    author : {
      name : Name Lastname
      email : "blah@email.test"
      github : username
      twitter : username
    }

The theme should reference these variables whenever needed.

## To-Do

A lot of job need to be done, including:

1. make play be able to compile md template smoothly so that the index page
2. make it easy to [generate static site](https://github.com/sbt/sbt-site) and [git pushing](http://github.com/sbt/sbt-ghpages)
3. add extra features like play-doc support
4. add examples

Any suggestion or contribution is welcome.

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".