---
layout: post
category : notes
tags : [memcached, perl]
title: Getting extra stats from memcached using perl
---

Get stats from memcached

    perl -MCache::Memcached -MData::Dumper=Dumper -le 'print Dumper(Cache::Memcached->new(servers => ["localhost:11211"])->stats);

Described on [pal-blog][]

[pal-blog]: http://www.pal-blog.de/entwicklung/memcached/2011/memcached-statistics-stats-command.html
