---

layout: post
category: notes
tags: []
title: Graphing event interactions

---

List modules containing .raise('
ggrep "\.raise('" ../we7/webFiles/scripts/ | awk '{print $1}' | sort -u

List Raise events by module
ggrep "\.raise('" ../we7/webFiles/scripts/w7i-chugger.js | sed "s/.*\.raise('\([^,]*\)'.*$/\1/"

cat filesWithRaise | xargs -n 1 -d \\n ./extactWatches.sh > filesWithWatches
