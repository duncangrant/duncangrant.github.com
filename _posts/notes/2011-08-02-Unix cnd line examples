---

layout: post
category: notes
tags: [bash, cmd]
title: Unix cnd line examples

---

Get list of unique urls with counts
cat /scratch/duncang/logs/20110801-pound-pollux.log | awk '{if($15!=404) print $13}' | cut -f 1 -d ? | sort | uniq -c  > /scratch/duncang/logs/20110801-unique-urls
