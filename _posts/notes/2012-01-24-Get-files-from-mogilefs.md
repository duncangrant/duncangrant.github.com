---

layout: post
category: notes
tags: [bash, we7, cheatsheet, cmd]
title: Get files from mogilefs

---

"""for i in `moglistkeys --domain=podsplice --key_prefix='logs/tracking/2012-01-24-09'`; do echo $i ;mogfetch --domain=podsplice --key=$i --file=`basename $i`; done"""
