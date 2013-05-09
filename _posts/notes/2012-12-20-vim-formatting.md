---

layout: post
category : notes
tags : [vim]
title: Formatting in vim
---
Format json

	:%!python -mjson.tool
	
Format xml (requires libxml2-utils)

	:%!xmllint --format -
