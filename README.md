from stephen.marquard@uct.ac.za sat jan  5 09:14:16 2008 ← mismatch
return-path:
received: from murder (mail.umich.edu [141.211.14.90])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 sat, 05 jan 2008 09:14:16 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 sat, 05 jan 2008 09:14:16 -0500
received: from holes.mr.itd.umich.edu (holes.mr.itd.umich.edu [141.211.14.79])
	by flawless.mail.umich.edu () with esmtp id m05eefr1013674;
	sat, 5 jan 2008 09:14:15 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by holes.mr.itd.umich.edu id 477f90b0.2db2f.12494 ;
	 5 jan 2008 09:14:10 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 5f919bc2f2;
	sat,  5 jan 2008 14:10:05 +0000 (gmt)
message-id: <200801051412.m05eciah010327@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 899
          for ;
          sat, 5 jan 2008 14:09:50 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id a215243002
	for ; sat,  5 jan 2008 14:13:33 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m05ecjvp010329
	for ; sat, 5 jan 2008 09:12:19 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m05eciah010327
	for source@collab.sakaiproject.org; sat, 5 jan 2008 09:12:18 -0500
date: sat, 5 jan 2008 09:12:18 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to stephen.marquard@uct.ac.za using -f
to: source@collab.sakaiproject.org
from: stephen.marquard@uct.ac.za
subject: [sakai] svn commit: r39772 - content/branches/sakai_2-5-x/content-impl/impl/src/java/org/sakaiproject/content/impl
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: sat jan  5 09:14:16 2008
x-dspam-confidence: 0.8475
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39772

author: stephen.marquard@uct.ac.za
date: 2008-01-05 09:12:07 -0500 (sat, 05 jan 2008)
new revision: 39772

modified:
content/branches/sakai_2-5-x/content-impl/impl/src/java/org/sakaiproject/content/impl/contentservicesqloracle.java
content/branches/sakai_2-5-x/content-impl/impl/src/java/org/sakaiproject/content/impl/dbcontentservice.java
log:
sak-12501 merge to 2-5-x: r39622, r39624:5, r39632:3 (resolve conflict from differing linebreaks for r39622)

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from louis@media.berkeley.edu fri jan  4 18:10:48 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.97])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 18:10:48 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 18:10:48 -0500
received: from icestorm.mr.itd.umich.edu (icestorm.mr.itd.umich.edu [141.211.93.149])
	by sleepers.mail.umich.edu () with esmtp id m04nabga029441;
	fri, 4 jan 2008 18:10:37 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by icestorm.mr.itd.umich.edu id 477ebce3.161bb.4320 ;
	 4 jan 2008 18:10:31 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 07969bb706;
	fri,  4 jan 2008 23:10:33 +0000 (gmt)
message-id: <200801042308.m04n8v6o008125@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 710
          for ;
          fri, 4 jan 2008 23:10:10 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 4ba2f42f57
	for ; fri,  4 jan 2008 23:10:10 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04n8vhg008127
	for ; fri, 4 jan 2008 18:08:57 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04n8v6o008125
	for source@collab.sakaiproject.org; fri, 4 jan 2008 18:08:57 -0500
date: fri, 4 jan 2008 18:08:57 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to louis@media.berkeley.edu using -f
to: source@collab.sakaiproject.org
from: louis@media.berkeley.edu
subject: [sakai] svn commit: r39771 - in bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src: bundle java/org/sakaiproject/site/tool
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 18:10:48 2008
x-dspam-confidence: 0.6178
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39771

author: louis@media.berkeley.edu
date: 2008-01-04 18:08:50 -0500 (fri, 04 jan 2008)
new revision: 39771

modified:
bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src/bundle/sitesetupgeneric.properties
bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src/java/org/sakaiproject/site/tool/siteaction.java
log:
bsp-1415 new (guest) user notification

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from zqian@umich.edu fri jan  4 16:10:39 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.25])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 16:10:39 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 16:10:39 -0500
received: from ghostbusters.mr.itd.umich.edu (ghostbusters.mr.itd.umich.edu [141.211.93.144])
	by panther.mail.umich.edu () with esmtp id m04laczw014275;
	fri, 4 jan 2008 16:10:38 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by ghostbusters.mr.itd.umich.edu id 477ea0c6.a0214.25480 ;
	 4 jan 2008 16:10:33 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id c48cdbb490;
	fri,  4 jan 2008 21:10:31 +0000 (gmt)
message-id: <200801042109.m04l92hb007923@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 906
          for ;
          fri, 4 jan 2008 21:10:18 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 7d13042f71
	for ; fri,  4 jan 2008 21:10:14 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04l927e007925
	for ; fri, 4 jan 2008 16:09:02 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04l92hb007923
	for source@collab.sakaiproject.org; fri, 4 jan 2008 16:09:02 -0500
date: fri, 4 jan 2008 16:09:02 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to zqian@umich.edu using -f
to: source@collab.sakaiproject.org
from: zqian@umich.edu
subject: [sakai] svn commit: r39770 - site-manage/branches/sakai_2-5-x/site-manage-tool/tool/src/webapp/vm/sitesetup
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 16:10:39 2008
x-dspam-confidence: 0.6961
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39770

author: zqian@umich.edu
date: 2008-01-04 16:09:01 -0500 (fri, 04 jan 2008)
new revision: 39770

modified:
site-manage/branches/sakai_2-5-x/site-manage-tool/tool/src/webapp/vm/sitesetup/chef_site-siteinfo-list.vm
log:
merge fix to sak-9996 into 2-5-x branch: svn merge -r 39687:39688 https://source.sakaiproject.org/svn/site-manage/trunk/

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from rjlowe@iupui.edu fri jan  4 15:46:24 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.25])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 15:46:24 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 15:46:24 -0500
received: from dreamcatcher.mr.itd.umich.edu (dreamcatcher.mr.itd.umich.edu [141.211.14.43])
	by panther.mail.umich.edu () with esmtp id m04kknbx032077;
	fri, 4 jan 2008 15:46:23 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by dreamcatcher.mr.itd.umich.edu id 477e9b13.2f3bc.22965 ;
	 4 jan 2008 15:46:13 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 4ae03bb552;
	fri,  4 jan 2008 20:46:13 +0000 (gmt)
message-id: <200801042044.m04kiem3007881@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 38
          for ;
          fri, 4 jan 2008 20:45:56 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id a55d242f57
	for ; fri,  4 jan 2008 20:45:52 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04kieqe007883
	for ; fri, 4 jan 2008 15:44:40 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04kiem3007881
	for source@collab.sakaiproject.org; fri, 4 jan 2008 15:44:40 -0500
date: fri, 4 jan 2008 15:44:40 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to rjlowe@iupui.edu using -f
to: source@collab.sakaiproject.org
from: rjlowe@iupui.edu
subject: [sakai] svn commit: r39769 - in gradebook/trunk/app/ui/src: java/org/sakaiproject/tool/gradebook/ui/helpers/beans java/org/sakaiproject/tool/gradebook/ui/helpers/producers webapp/web-inf webapp/web-inf/bundle
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 15:46:24 2008
x-dspam-confidence: 0.7565
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39769

author: rjlowe@iupui.edu
date: 2008-01-04 15:44:39 -0500 (fri, 04 jan 2008)
new revision: 39769

modified:
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/beans/assignmentgraderecordbean.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/producers/gradegradebookitemproducer.java
gradebook/trunk/app/ui/src/webapp/web-inf/applicationcontext.xml
gradebook/trunk/app/ui/src/webapp/web-inf/bundle/messages.properties
gradebook/trunk/app/ui/src/webapp/web-inf/requestcontext.xml
log:
sak-12180 - fixed errors with grading helper

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from zqian@umich.edu fri jan  4 15:03:18 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.46])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 15:03:18 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 15:03:18 -0500
received: from firestarter.mr.itd.umich.edu (firestarter.mr.itd.umich.edu [141.211.14.83])
	by fan.mail.umich.edu () with esmtp id m04k3hgf006563;
	fri, 4 jan 2008 15:03:17 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by firestarter.mr.itd.umich.edu id 477e9100.8f7f4.1590 ;
	 4 jan 2008 15:03:15 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 57770bb477;
	fri,  4 jan 2008 20:03:09 +0000 (gmt)
message-id: <200801042001.m04k1co0007738@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 622
          for ;
          fri, 4 jan 2008 20:02:46 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id ab4d042f4d
	for ; fri,  4 jan 2008 20:02:50 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04k1cxv007740
	for ; fri, 4 jan 2008 15:01:38 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04k1co0007738
	for source@collab.sakaiproject.org; fri, 4 jan 2008 15:01:38 -0500
date: fri, 4 jan 2008 15:01:38 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to zqian@umich.edu using -f
to: source@collab.sakaiproject.org
from: zqian@umich.edu
subject: [sakai] svn commit: r39766 - site-manage/branches/sakai_2-4-x/site-manage-tool/tool/src/java/org/sakaiproject/site/tool
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 15:03:18 2008
x-dspam-confidence: 0.7626
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39766

author: zqian@umich.edu
date: 2008-01-04 15:01:37 -0500 (fri, 04 jan 2008)
new revision: 39766

modified:
site-manage/branches/sakai_2-4-x/site-manage-tool/tool/src/java/org/sakaiproject/site/tool/siteaction.java
log:
merge fix to sak-10788 into site-manage 2.4.x branch:

sakai source repository  	#38024  	wed nov 07 14:54:46 mst 2007  	zqian@umich.edu  	 fix to sak-10788: if a provided id in a couse site is fake or doesn't provide any user information, site info appears to be like project site with empty participant list

watch for enrollments object being null and concatenate provider ids when there are more than one.
files changed
modify /site-manage/trunk/site-manage-tool/tool/src/java/org/sakaiproject/site/tool/siteaction.java




----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from rjlowe@iupui.edu fri jan  4 14:50:18 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.93])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 14:50:18 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 14:50:18 -0500
received: from eyewitness.mr.itd.umich.edu (eyewitness.mr.itd.umich.edu [141.211.93.142])
	by mission.mail.umich.edu () with esmtp id m04johji019755;
	fri, 4 jan 2008 14:50:17 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by eyewitness.mr.itd.umich.edu id 477e8df2.67b91.5278 ;
	 4 jan 2008 14:50:13 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 2d1b9bb492;
	fri,  4 jan 2008 19:47:10 +0000 (gmt)
message-id: <200801041948.m04jmdwo007705@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 960
          for ;
          fri, 4 jan 2008 19:46:50 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id b3e6742f4a
	for ; fri,  4 jan 2008 19:49:51 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04jmev9007707
	for ; fri, 4 jan 2008 14:48:40 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04jmdwo007705
	for source@collab.sakaiproject.org; fri, 4 jan 2008 14:48:39 -0500
date: fri, 4 jan 2008 14:48:39 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to rjlowe@iupui.edu using -f
to: source@collab.sakaiproject.org
from: rjlowe@iupui.edu
subject: [sakai] svn commit: r39765 - in gradebook/trunk/app: business/src/java/org/sakaiproject/tool/gradebook/business business/src/java/org/sakaiproject/tool/gradebook/business/impl ui ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/beans ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/entity ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/params ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/producers ui/src/webapp/web-inf ui/src/webapp/web-inf/bundle ui/src/webapp/content/templates
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 14:50:18 2008
x-dspam-confidence: 0.7556
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39765

author: rjlowe@iupui.edu
date: 2008-01-04 14:48:37 -0500 (fri, 04 jan 2008)
new revision: 39765

added:
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/beans/assignmentgraderecordbean.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/beans/assignmentgraderecordcreator.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/entity/gradebookentrygradeentityprovider.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/params/gradegradebookitemviewparams.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/producers/gradegradebookitemproducer.java
gradebook/trunk/app/ui/src/webapp/content/templates/grade-gradebook-item.html
modified:
gradebook/trunk/app/business/src/java/org/sakaiproject/tool/gradebook/business/gradebookmanager.java
gradebook/trunk/app/business/src/java/org/sakaiproject/tool/gradebook/business/impl/gradebookmanagerhibernateimpl.java
gradebook/trunk/app/ui/pom.xml
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/beans/gradebookitembean.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/entity/gradebookentryentityprovider.java
gradebook/trunk/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/helpers/producers/addgradebookitemproducer.java
gradebook/trunk/app/ui/src/webapp/web-inf/applicationcontext.xml
gradebook/trunk/app/ui/src/webapp/web-inf/bundle/messages.properties
gradebook/trunk/app/ui/src/webapp/web-inf/requestcontext.xml
log:
sak-12180 - new helper tool to grade an assignment

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from cwen@iupui.edu fri jan  4 11:37:30 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.46])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 11:37:30 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 11:37:30 -0500
received: from tadpole.mr.itd.umich.edu (tadpole.mr.itd.umich.edu [141.211.14.72])
	by fan.mail.umich.edu () with esmtp id m04gbt9x022078;
	fri, 4 jan 2008 11:37:29 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by tadpole.mr.itd.umich.edu id 477e60b2.82756.9904 ;
	 4 jan 2008 11:37:09 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 8d13dbb001;
	fri,  4 jan 2008 16:37:07 +0000 (gmt)
message-id: <200801041635.m04gzqgz007313@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 120
          for ;
          fri, 4 jan 2008 16:36:40 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id d430b42e42
	for ; fri,  4 jan 2008 16:36:37 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04gzq7w007315
	for ; fri, 4 jan 2008 11:35:26 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04gzqgz007313
	for source@collab.sakaiproject.org; fri, 4 jan 2008 11:35:26 -0500
date: fri, 4 jan 2008 11:35:26 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to cwen@iupui.edu using -f
to: source@collab.sakaiproject.org
from: cwen@iupui.edu
subject: [sakai] svn commit: r39764 - in msgcntr/trunk/messageforums-app/src/java/org/sakaiproject/tool/messageforums: . ui
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 11:37:30 2008
x-dspam-confidence: 0.7002
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39764

author: cwen@iupui.edu
date: 2008-01-04 11:35:25 -0500 (fri, 04 jan 2008)
new revision: 39764

modified:
msgcntr/trunk/messageforums-app/src/java/org/sakaiproject/tool/messageforums/privatemessagestool.java
msgcntr/trunk/messageforums-app/src/java/org/sakaiproject/tool/messageforums/ui/privatemessagedecoratedbean.java
log:
unmerge xingtang's checkin for sak-12488.

svn merge -r39558:39557 https://source.sakaiproject.org/svn/msgcntr/trunk
u    messageforums-app/src/java/org/sakaiproject/tool/messageforums/privatemessagestool.java
u    messageforums-app/src/java/org/sakaiproject/tool/messageforums/ui/privatemessagedecoratedbean.java

svn log -r 39558
------------------------------------------------------------------------
r39558 | hu2@iupui.edu | 2007-12-20 15:25:38 -0500 (thu, 20 dec 2007) | 3 lines

sak-12488
when send a message to yourself. click reply to all, cc row should be null.
http://jira.sakaiproject.org/jira/browse/sak-12488
------------------------------------------------------------------------


----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from cwen@iupui.edu fri jan  4 11:35:08 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.46])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 11:35:08 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 11:35:08 -0500
received: from it.mr.itd.umich.edu (it.mr.itd.umich.edu [141.211.93.151])
	by fan.mail.umich.edu () with esmtp id m04gz6lt020480;
	fri, 4 jan 2008 11:35:06 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by it.mr.itd.umich.edu id 477e6033.6469d.21870 ;
	 4 jan 2008 11:35:02 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id e40fabae5b;
	fri,  4 jan 2008 16:34:38 +0000 (gmt)
message-id: <200801041633.m04gx6eg007292@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 697
          for ;
          fri, 4 jan 2008 16:34:01 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 1cd0c42e42
	for ; fri,  4 jan 2008 16:34:17 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04gx6y3007294
	for ; fri, 4 jan 2008 11:33:06 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04gx6eg007292
	for source@collab.sakaiproject.org; fri, 4 jan 2008 11:33:06 -0500
date: fri, 4 jan 2008 11:33:06 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to cwen@iupui.edu using -f
to: source@collab.sakaiproject.org
from: cwen@iupui.edu
subject: [sakai] svn commit: r39763 - in msgcntr/trunk: messageforums-api/src/bundle/org/sakaiproject/api/app/messagecenter/bundle messageforums-app/src/java/org/sakaiproject/tool/messageforums
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 11:35:08 2008
x-dspam-confidence: 0.7615
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39763

author: cwen@iupui.edu
date: 2008-01-04 11:33:05 -0500 (fri, 04 jan 2008)
new revision: 39763

modified:
msgcntr/trunk/messageforums-api/src/bundle/org/sakaiproject/api/app/messagecenter/bundle/messages.properties
msgcntr/trunk/messageforums-app/src/java/org/sakaiproject/tool/messageforums/privatemessagestool.java
log:
unmerge xingtang's check in for sak-12484.

svn merge -r39571:39570 https://source.sakaiproject.org/svn/msgcntr/trunk
u    messageforums-api/src/bundle/org/sakaiproject/api/app/messagecenter/bundle/messages.properties
u    messageforums-app/src/java/org/sakaiproject/tool/messageforums/privatemessagestool.java

svn log -r 39571
------------------------------------------------------------------------
r39571 | hu2@iupui.edu | 2007-12-20 21:26:28 -0500 (thu, 20 dec 2007) | 3 lines

sak-12484
reply all cc list should not include the current user name.
http://jira.sakaiproject.org/jira/browse/sak-12484
------------------------------------------------------------------------


----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from gsilver@umich.edu fri jan  4 11:12:37 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.25])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 11:12:37 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 11:12:37 -0500
received: from holes.mr.itd.umich.edu (holes.mr.itd.umich.edu [141.211.14.79])
	by panther.mail.umich.edu () with esmtp id m04gcahb030887;
	fri, 4 jan 2008 11:12:36 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by holes.mr.itd.umich.edu id 477e5aeb.e670b.28397 ;
	 4 jan 2008 11:12:30 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 99715bae7d;
	fri,  4 jan 2008 16:12:27 +0000 (gmt)
message-id: <200801041611.m04gb1lb007221@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 272
          for ;
          fri, 4 jan 2008 16:12:14 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 0a6ed42dfc
	for ; fri,  4 jan 2008 16:12:12 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04gb1wt007223
	for ; fri, 4 jan 2008 11:11:01 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04gb1lb007221
	for source@collab.sakaiproject.org; fri, 4 jan 2008 11:11:01 -0500
date: fri, 4 jan 2008 11:11:01 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to gsilver@umich.edu using -f
to: source@collab.sakaiproject.org
from: gsilver@umich.edu
subject: [sakai] svn commit: r39762 - web/trunk/web-tool/tool/src/bundle
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 11:12:37 2008
x-dspam-confidence: 0.7601
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39762

author: gsilver@umich.edu
date: 2008-01-04 11:11:00 -0500 (fri, 04 jan 2008)
new revision: 39762

modified:
web/trunk/web-tool/tool/src/bundle/iframe.properties
log:
sak-12596
http://bugs.sakaiproject.org/jira/browse/sak-12596
- left moot (unused) entries commented for now

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from gsilver@umich.edu fri jan  4 11:11:52 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.36])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 11:11:52 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 11:11:52 -0500
received: from creepshow.mr.itd.umich.edu (creepshow.mr.itd.umich.edu [141.211.14.84])
	by godsend.mail.umich.edu () with esmtp id m04gbqqv025330;
	fri, 4 jan 2008 11:11:52 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by creepshow.mr.itd.umich.edu id 477e5ab3.5cc32.30840 ;
	 4 jan 2008 11:11:34 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 62aa4bae46;
	fri,  4 jan 2008 16:11:31 +0000 (gmt)
message-id: <200801041610.m04ga5kp007209@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 1006
          for ;
          fri, 4 jan 2008 16:11:18 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id c596a3dfa2
	for ; fri,  4 jan 2008 16:11:16 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04ga5lr007211
	for ; fri, 4 jan 2008 11:10:05 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04ga5kp007209
	for source@collab.sakaiproject.org; fri, 4 jan 2008 11:10:05 -0500
date: fri, 4 jan 2008 11:10:05 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to gsilver@umich.edu using -f
to: source@collab.sakaiproject.org
from: gsilver@umich.edu
subject: [sakai] svn commit: r39761 - site/trunk/site-tool/tool/src/bundle
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 11:11:52 2008
x-dspam-confidence: 0.7605
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39761

author: gsilver@umich.edu
date: 2008-01-04 11:10:04 -0500 (fri, 04 jan 2008)
new revision: 39761

modified:
site/trunk/site-tool/tool/src/bundle/admin.properties
log:
sak-12595
http://bugs.sakaiproject.org/jira/browse/sak-12595
- left moot (unused) entries commented for now

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from zqian@umich.edu fri jan  4 11:11:03 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.97])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 11:11:03 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 11:11:03 -0500
received: from carrie.mr.itd.umich.edu (carrie.mr.itd.umich.edu [141.211.93.152])
	by sleepers.mail.umich.edu () with esmtp id m04gb3vg011502;
	fri, 4 jan 2008 11:11:03 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by carrie.mr.itd.umich.edu id 477e5a8d.b378f.24200 ;
	 4 jan 2008 11:10:56 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id c7251bad44;
	fri,  4 jan 2008 16:10:53 +0000 (gmt)
message-id: <200801041609.m04g9eux007197@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 483
          for ;
          fri, 4 jan 2008 16:10:27 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 2e7043dfa2
	for ; fri,  4 jan 2008 16:10:26 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04g9eqg007199
	for ; fri, 4 jan 2008 11:09:15 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04g9eux007197
	for source@collab.sakaiproject.org; fri, 4 jan 2008 11:09:14 -0500
date: fri, 4 jan 2008 11:09:14 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to zqian@umich.edu using -f
to: source@collab.sakaiproject.org
from: zqian@umich.edu
subject: [sakai] svn commit: r39760 - in site-manage/trunk/site-manage-tool/tool/src: java/org/sakaiproject/site/tool webapp/vm/sitesetup
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 11:11:03 2008
x-dspam-confidence: 0.6959
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39760

author: zqian@umich.edu
date: 2008-01-04 11:09:12 -0500 (fri, 04 jan 2008)
new revision: 39760

modified:
site-manage/trunk/site-manage-tool/tool/src/java/org/sakaiproject/site/tool/siteaction.java
site-manage/trunk/site-manage-tool/tool/src/webapp/vm/sitesetup/chef_site-siteinfo-list.vm
log:
fix to sak-10911: refactor use of site.upd, site.upd.site.mbrship and site.upd.grp.mbrship permissions

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from gsilver@umich.edu fri jan  4 11:10:22 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.39])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 11:10:22 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 11:10:22 -0500
received: from holes.mr.itd.umich.edu (holes.mr.itd.umich.edu [141.211.14.79])
	by faithful.mail.umich.edu () with esmtp id m04gal9k010604;
	fri, 4 jan 2008 11:10:21 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by holes.mr.itd.umich.edu id 477e5a67.34350.23015 ;
	 4 jan 2008 11:10:18 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 98d04bad43;
	fri,  4 jan 2008 16:10:11 +0000 (gmt)
message-id: <200801041608.m04g8d7w007184@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 966
          for ;
          fri, 4 jan 2008 16:09:51 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 9f89542dd0
	for ; fri,  4 jan 2008 16:09:50 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04g8dxn007186
	for ; fri, 4 jan 2008 11:08:39 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04g8d7w007184
	for source@collab.sakaiproject.org; fri, 4 jan 2008 11:08:39 -0500
date: fri, 4 jan 2008 11:08:39 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to gsilver@umich.edu using -f
to: source@collab.sakaiproject.org
from: gsilver@umich.edu
subject: [sakai] svn commit: r39759 - mailarchive/trunk/mailarchive-tool/tool/src/bundle
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 11:10:22 2008
x-dspam-confidence: 0.7606
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39759

author: gsilver@umich.edu
date: 2008-01-04 11:08:38 -0500 (fri, 04 jan 2008)
new revision: 39759

modified:
mailarchive/trunk/mailarchive-tool/tool/src/bundle/email.properties
log:
sak-12592
http://bugs.sakaiproject.org/jira/browse/sak-12592
- left moot (unused) entries commented for now

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from wagnermr@iupui.edu fri jan  4 10:38:42 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.90])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 10:38:42 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 10:38:42 -0500
received: from shining.mr.itd.umich.edu (shining.mr.itd.umich.edu [141.211.93.153])
	by flawless.mail.umich.edu () with esmtp id m04fcfjm012313;
	fri, 4 jan 2008 10:38:41 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by shining.mr.itd.umich.edu id 477e52fa.e6c6e.24093 ;
	 4 jan 2008 10:38:37 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 6a39594cd2;
	fri,  4 jan 2008 15:37:36 +0000 (gmt)
message-id: <200801041537.m04fb6ci007092@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 690
          for ;
          fri, 4 jan 2008 15:37:21 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id cefa037ace
	for ; fri,  4 jan 2008 15:38:17 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04fb6nh007094
	for ; fri, 4 jan 2008 10:37:06 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04fb6ci007092
	for source@collab.sakaiproject.org; fri, 4 jan 2008 10:37:06 -0500
date: fri, 4 jan 2008 10:37:06 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to wagnermr@iupui.edu using -f
to: source@collab.sakaiproject.org
from: wagnermr@iupui.edu
subject: [sakai] svn commit: r39758 - in gradebook/trunk: app/business/src/java/org/sakaiproject/tool/gradebook/business/impl service/api/src/java/org/sakaiproject/service/gradebook/shared service/impl/src/java/org/sakaiproject/component/gradebook
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 10:38:42 2008
x-dspam-confidence: 0.7559
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39758

author: wagnermr@iupui.edu
date: 2008-01-04 10:37:04 -0500 (fri, 04 jan 2008)
new revision: 39758

modified:
gradebook/trunk/app/business/src/java/org/sakaiproject/tool/gradebook/business/impl/gradebookmanagerhibernateimpl.java
gradebook/trunk/service/api/src/java/org/sakaiproject/service/gradebook/shared/gradebookservice.java
gradebook/trunk/service/impl/src/java/org/sakaiproject/component/gradebook/gradebookservicehibernateimpl.java
log:
sak-12175
http://bugs.sakaiproject.org/jira/browse/sak-12175
create methods required for gb integration with the assignment2 tool
get_gradedefinitionforstudentforitem

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from zqian@umich.edu fri jan  4 10:17:43 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.97])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 10:17:43 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 10:17:42 -0500
received: from creepshow.mr.itd.umich.edu (creepshow.mr.itd.umich.edu [141.211.14.84])
	by sleepers.mail.umich.edu () with esmtp id m04fhgfs011536;
	fri, 4 jan 2008 10:17:42 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by creepshow.mr.itd.umich.edu id 477e4e0f.cca4b.926 ;
	 4 jan 2008 10:17:38 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id bd02dbac64;
	fri,  4 jan 2008 15:17:34 +0000 (gmt)
message-id: <200801041515.m04ffv42007050@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 25
          for ;
          fri, 4 jan 2008 15:17:11 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 5b396236b9
	for ; fri,  4 jan 2008 15:17:08 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04ffv85007052
	for ; fri, 4 jan 2008 10:15:57 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04ffv42007050
	for source@collab.sakaiproject.org; fri, 4 jan 2008 10:15:57 -0500
date: fri, 4 jan 2008 10:15:57 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to zqian@umich.edu using -f
to: source@collab.sakaiproject.org
from: zqian@umich.edu
subject: [sakai] svn commit: r39757 - in assignment/trunk: assignment-impl/impl/src/java/org/sakaiproject/assignment/impl assignment-tool/tool/src/webapp/vm/assignment
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 10:17:42 2008
x-dspam-confidence: 0.7605
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39757

author: zqian@umich.edu
date: 2008-01-04 10:15:54 -0500 (fri, 04 jan 2008)
new revision: 39757

modified:
assignment/trunk/assignment-impl/impl/src/java/org/sakaiproject/assignment/impl/baseassignmentservice.java
assignment/trunk/assignment-tool/tool/src/webapp/vm/assignment/chef_assignments_instructor_list_submissions.vm
log:
fix to sak-12604:don't show groups/sections filter if the site doesn't have any

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from antranig@caret.cam.ac.uk fri jan  4 10:04:14 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.25])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 10:04:14 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 10:04:14 -0500
received: from holes.mr.itd.umich.edu (holes.mr.itd.umich.edu [141.211.14.79])
	by panther.mail.umich.edu () with esmtp id m04f4dci015108;
	fri, 4 jan 2008 10:04:13 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by holes.mr.itd.umich.edu id 477e4ae3.d7af.31669 ;
	 4 jan 2008 10:04:05 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 933e3bac17;
	fri,  4 jan 2008 15:04:00 +0000 (gmt)
message-id: <200801041502.m04f21jo007031@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 32
          for ;
          fri, 4 jan 2008 15:03:15 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id ac2f6236b9
	for ; fri,  4 jan 2008 15:03:12 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04f21hn007033
	for ; fri, 4 jan 2008 10:02:01 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04f21jo007031
	for source@collab.sakaiproject.org; fri, 4 jan 2008 10:02:01 -0500
date: fri, 4 jan 2008 10:02:01 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to antranig@caret.cam.ac.uk using -f
to: source@collab.sakaiproject.org
from: antranig@caret.cam.ac.uk
subject: [sakai] svn commit: r39756 - in component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component: impl impl/spring/support impl/spring/support/dynamic impl/support util
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 10:04:14 2008
x-dspam-confidence: 0.6932
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39756

author: antranig@caret.cam.ac.uk
date: 2008-01-04 10:01:40 -0500 (fri, 04 jan 2008)
new revision: 39756

added:
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/spring/support/dynamic/
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/spring/support/dynamic/dynamiccomponentmanager.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/support/
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/support/dynamiccomponentrecord.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/support/dynamicjarmanager.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/support/jarrecord.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/util/bytetocharbase64.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/util/fileutil.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/util/recordfileio.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/util/recordreader.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/util/recordwriter.java
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/util/streamdigestor.java
modified:
component/branches/sak-12166/component-api/component/src/java/org/sakaiproject/component/impl/spring/support/componentsloaderimpl.java
log:
temporary commit of incomplete work on jar caching

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from gopal.ramasammycook@gmail.com fri jan  4 09:05:31 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.90])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 09:05:31 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 09:05:31 -0500
received: from guys.mr.itd.umich.edu (guys.mr.itd.umich.edu [141.211.14.76])
	by flawless.mail.umich.edu () with esmtp id m04e5u3c029277;
	fri, 4 jan 2008 09:05:30 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by guys.mr.itd.umich.edu id 477e3d23.ee2e7.5237 ;
	 4 jan 2008 09:05:26 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 33c7856dc0;
	fri,  4 jan 2008 14:05:26 +0000 (gmt)
message-id: <200801041403.m04e3psw006926@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 575
          for ;
          fri, 4 jan 2008 14:05:04 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 3c0261d617
	for ; fri,  4 jan 2008 14:05:03 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04e3pqs006928
	for ; fri, 4 jan 2008 09:03:52 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04e3psw006926
	for source@collab.sakaiproject.org; fri, 4 jan 2008 09:03:51 -0500
date: fri, 4 jan 2008 09:03:51 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to gopal.ramasammycook@gmail.com using -f
to: source@collab.sakaiproject.org
from: gopal.ramasammycook@gmail.com
subject: [sakai] svn commit: r39755 - in sam/branches/sak-12065: samigo-api/src/java/org/sakaiproject/tool/assessment/shared/api/grading samigo-app/src/java/org/sakaiproject/tool/assessment/ui/bean/evaluation samigo-app/src/java/org/sakaiproject/tool/assessment/ui/listener/evaluation samigo-services/src/java/org/sakaiproject/tool/assessment/facade samigo-services/src/java/org/sakaiproject/tool/assessment/integration/helper/ifc samigo-services/src/java/org/sakaiproject/tool/assessment/integration/helper/integrated samigo-services/src/java/org/sakaiproject/tool/assessment/integration/helper/standalone samigo-services/src/java/org/sakaiproject/tool/assessment/shared/impl/grading
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 09:05:31 2008
x-dspam-confidence: 0.7558
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39755

author: gopal.ramasammycook@gmail.com
date: 2008-01-04 09:02:54 -0500 (fri, 04 jan 2008)
new revision: 39755

modified:
sam/branches/sak-12065/samigo-api/src/java/org/sakaiproject/tool/assessment/shared/api/grading/gradingsectionawareserviceapi.java
sam/branches/sak-12065/samigo-app/src/java/org/sakaiproject/tool/assessment/ui/bean/evaluation/questionscoresbean.java
sam/branches/sak-12065/samigo-app/src/java/org/sakaiproject/tool/assessment/ui/bean/evaluation/submissionstatusbean.java
sam/branches/sak-12065/samigo-app/src/java/org/sakaiproject/tool/assessment/ui/bean/evaluation/totalscoresbean.java
sam/branches/sak-12065/samigo-app/src/java/org/sakaiproject/tool/assessment/ui/listener/evaluation/submissionstatuslistener.java
sam/branches/sak-12065/samigo-services/src/java/org/sakaiproject/tool/assessment/facade/publishedassessmentfacadequeries.java
sam/branches/sak-12065/samigo-services/src/java/org/sakaiproject/tool/assessment/facade/publishedassessmentfacadequeriesapi.java
sam/branches/sak-12065/samigo-services/src/java/org/sakaiproject/tool/assessment/integration/helper/ifc/sectionawareservicehelper.java
sam/branches/sak-12065/samigo-services/src/java/org/sakaiproject/tool/assessment/integration/helper/integrated/sectionawareservicehelperimpl.java
sam/branches/sak-12065/samigo-services/src/java/org/sakaiproject/tool/assessment/integration/helper/standalone/sectionawareservicehelperimpl.java
sam/branches/sak-12065/samigo-services/src/java/org/sakaiproject/tool/assessment/shared/impl/grading/gradingsectionawareserviceimpl.java
log:
sak-12065 gopal - samigo group release. submissionstatus/totalscores/questions view filter.

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from david.horwitz@uct.ac.za fri jan  4 07:02:32 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.39])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 07:02:32 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 07:02:32 -0500
received: from guys.mr.itd.umich.edu (guys.mr.itd.umich.edu [141.211.14.76])
	by faithful.mail.umich.edu () with esmtp id m04c2vn7026678;
	fri, 4 jan 2008 07:02:31 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by guys.mr.itd.umich.edu id 477e2050.c2599.3263 ;
	 4 jan 2008 07:02:27 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 6497fba906;
	fri,  4 jan 2008 12:02:11 +0000 (gmt)
message-id: <200801041200.m04c0gfk006793@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 611
          for ;
          fri, 4 jan 2008 12:01:53 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 5296342d3c
	for ; fri,  4 jan 2008 12:01:53 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04c0gnm006795
	for ; fri, 4 jan 2008 07:00:42 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04c0gfk006793
	for source@collab.sakaiproject.org; fri, 4 jan 2008 07:00:42 -0500
date: fri, 4 jan 2008 07:00:42 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to david.horwitz@uct.ac.za using -f
to: source@collab.sakaiproject.org
from: david.horwitz@uct.ac.za
subject: [sakai] svn commit: r39754 - in polls/branches/sakai_2-5-x: . tool tool/src/java/org/sakaiproject/poll/tool tool/src/java/org/sakaiproject/poll/tool/evolvers tool/src/webapp/web-inf
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 07:02:32 2008
x-dspam-confidence: 0.6526
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39754

author: david.horwitz@uct.ac.za
date: 2008-01-04 07:00:10 -0500 (fri, 04 jan 2008)
new revision: 39754

added:
polls/branches/sakai_2-5-x/tool/src/java/org/sakaiproject/poll/tool/evolvers/
polls/branches/sakai_2-5-x/tool/src/java/org/sakaiproject/poll/tool/evolvers/sakaifcktextevolver.java
removed:
polls/branches/sakai_2-5-x/tool/src/java/org/sakaiproject/poll/tool/evolvers/sakaifcktextevolver.java
modified:
polls/branches/sakai_2-5-x/.classpath
polls/branches/sakai_2-5-x/tool/pom.xml
polls/branches/sakai_2-5-x/tool/src/webapp/web-inf/requestcontext.xml
log:
svn log -r39753 https://source.sakaiproject.org/svn/polls/trunk
------------------------------------------------------------------------
r39753 | david.horwitz@uct.ac.za | 2008-01-04 13:05:51 +0200 (fri, 04 jan 2008) | 1 line

sak-12228 implmented workaround sugested by ab - needs to be tested against a trunk build
------------------------------------------------------------------------
dhorwitz@david-horwitz-6:~/branchmanagemnt/sakai_2-5-x> svn merge -c39753 https://source.sakaiproject.org/svn/polls/trunk polls/
u    polls/.classpath
a    polls/tool/src/java/org/sakaiproject/poll/tool/evolvers
a    polls/tool/src/java/org/sakaiproject/poll/tool/evolvers/sakaifcktextevolver.java
c    polls/tool/src/webapp/web-inf/requestcontext.xml
u    polls/tool/pom.xml

dhorwitz@david-horwitz-6:~/branchmanagemnt/sakai_2-5-x> svn resolved polls/tool/src/webapp/web-inf/requestcontext.xml
resolved conflicted state of 'polls/tool/src/webapp/web-inf/requestcontext.xml


----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from david.horwitz@uct.ac.za fri jan  4 06:08:27 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.98])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 06:08:27 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 06:08:27 -0500
received: from firestarter.mr.itd.umich.edu (firestarter.mr.itd.umich.edu [141.211.14.83])
	by casino.mail.umich.edu () with esmtp id m04b8qw9001368;
	fri, 4 jan 2008 06:08:26 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by firestarter.mr.itd.umich.edu id 477e13a5.30fc0.24054 ;
	 4 jan 2008 06:08:23 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 784a476d7b;
	fri,  4 jan 2008 11:08:12 +0000 (gmt)
message-id: <200801041106.m04b6lk3006677@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 585
          for ;
          fri, 4 jan 2008 11:07:56 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 1cacc42d0c
	for ; fri,  4 jan 2008 11:07:58 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m04b6lwm006679
	for ; fri, 4 jan 2008 06:06:47 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m04b6lk3006677
	for source@collab.sakaiproject.org; fri, 4 jan 2008 06:06:47 -0500
date: fri, 4 jan 2008 06:06:47 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to david.horwitz@uct.ac.za using -f
to: source@collab.sakaiproject.org
from: david.horwitz@uct.ac.za
subject: [sakai] svn commit: r39753 - in polls/trunk: . tool tool/src/java/org/sakaiproject/poll/tool tool/src/java/org/sakaiproject/poll/tool/evolvers tool/src/webapp/web-inf
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 06:08:27 2008
x-dspam-confidence: 0.6948
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39753

author: david.horwitz@uct.ac.za
date: 2008-01-04 06:05:51 -0500 (fri, 04 jan 2008)
new revision: 39753

added:
polls/trunk/tool/src/java/org/sakaiproject/poll/tool/evolvers/
polls/trunk/tool/src/java/org/sakaiproject/poll/tool/evolvers/sakaifcktextevolver.java
modified:
polls/trunk/.classpath
polls/trunk/tool/pom.xml
polls/trunk/tool/src/webapp/web-inf/requestcontext.xml
log:
sak-12228 implmented workaround sugested by ab - needs to be tested against a trunk build

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from david.horwitz@uct.ac.za fri jan  4 04:49:08 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.92])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 04:49:08 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 04:49:08 -0500
received: from galaxyquest.mr.itd.umich.edu (galaxyquest.mr.itd.umich.edu [141.211.93.145])
	by score.mail.umich.edu () with esmtp id m049n60g017588;
	fri, 4 jan 2008 04:49:06 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by galaxyquest.mr.itd.umich.edu id 477e010c.48c2.10259 ;
	 4 jan 2008 04:49:03 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 254cc8cdee;
	fri,  4 jan 2008 09:48:55 +0000 (gmt)
message-id: <200801040947.m049luxo006517@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 246
          for ;
          fri, 4 jan 2008 09:48:36 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 8c13342c92
	for ; fri,  4 jan 2008 09:48:40 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m049lu3p006519
	for ; fri, 4 jan 2008 04:47:30 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m049luxo006517
	for source@collab.sakaiproject.org; fri, 4 jan 2008 04:47:30 -0500
date: fri, 4 jan 2008 04:47:30 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to david.horwitz@uct.ac.za using -f
to: source@collab.sakaiproject.org
from: david.horwitz@uct.ac.za
subject: [sakai] svn commit: r39752 - in podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp: css podcasts
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 04:49:08 2008
x-dspam-confidence: 0.6528
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39752

author: david.horwitz@uct.ac.za
date: 2008-01-04 04:47:16 -0500 (fri, 04 jan 2008)
new revision: 39752

modified:
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/css/podcaster.css
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/podcasts/podmain.jsp
log:
svn log -r39641 https://source.sakaiproject.org/svn/podcasts/trunk
------------------------------------------------------------------------
r39641 | josrodri@iupui.edu | 2007-12-28 23:44:24 +0200 (fri, 28 dec 2007) | 1 line

sak-9882: refactored podmain.jsp the right way (at least much closer to)
------------------------------------------------------------------------

dhorwitz@david-horwitz-6:~/branchmanagemnt/sakai_2-5-x> svn merge  -c39641 https://source.sakaiproject.org/svn/podcasts/trunk podcasts/
c    podcasts/podcasts-app/src/webapp/podcasts/podmain.jsp
u    podcasts/podcasts-app/src/webapp/css/podcaster.css

conflict merged manualy



----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from david.horwitz@uct.ac.za fri jan  4 04:33:44 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.46])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 04:33:44 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 04:33:44 -0500
received: from workinggirl.mr.itd.umich.edu (workinggirl.mr.itd.umich.edu [141.211.93.143])
	by fan.mail.umich.edu () with esmtp id m049xge3031803;
	fri, 4 jan 2008 04:33:42 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by workinggirl.mr.itd.umich.edu id 477dfd6c.75dbe.26054 ;
	 4 jan 2008 04:33:35 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 6c929ba656;
	fri,  4 jan 2008 09:33:27 +0000 (gmt)
message-id: <200801040932.m049w2i5006493@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 153
          for ;
          fri, 4 jan 2008 09:33:10 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 6c69423767
	for ; fri,  4 jan 2008 09:33:13 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m049w3fl006495
	for ; fri, 4 jan 2008 04:32:03 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m049w2i5006493
	for source@collab.sakaiproject.org; fri, 4 jan 2008 04:32:02 -0500
date: fri, 4 jan 2008 04:32:02 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to david.horwitz@uct.ac.za using -f
to: source@collab.sakaiproject.org
from: david.horwitz@uct.ac.za
subject: [sakai] svn commit: r39751 - in podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp: css images podcasts
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 04:33:44 2008
x-dspam-confidence: 0.7002
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39751

author: david.horwitz@uct.ac.za
date: 2008-01-04 04:31:35 -0500 (fri, 04 jan 2008)
new revision: 39751

removed:
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/images/rss-feed-icon.png
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/podcasts/podpermissions.jsp
modified:
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/css/podcaster.css
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/podcasts/poddelete.jsp
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/podcasts/podmain.jsp
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/podcasts/podnoresource.jsp
podcasts/branches/sakai_2-5-x/podcasts-app/src/webapp/podcasts/podoptions.jsp
log:
svn log -r39146 https://source.sakaiproject.org/svn/podcasts/trunk
------------------------------------------------------------------------
r39146 | josrodri@iupui.edu | 2007-12-12 21:40:33 +0200 (wed, 12 dec 2007) | 1 line

sak-9882: refactored the other pages as well to take advantage of proper jsp components as well as validation cleanup.
------------------------------------------------------------------------
dhorwitz@david-horwitz-6:~/branchmanagemnt/sakai_2-5-x> svn merge -c39146 https://source.sakaiproject.org/svn/podcasts/trunk podcasts/
d    podcasts/podcasts-app/src/webapp/podcasts/podpermissions.jsp
u    podcasts/podcasts-app/src/webapp/podcasts/poddelete.jsp
u    podcasts/podcasts-app/src/webapp/podcasts/podmain.jsp
u    podcasts/podcasts-app/src/webapp/podcasts/podnoresource.jsp
u    podcasts/podcasts-app/src/webapp/podcasts/podoptions.jsp
d    podcasts/podcasts-app/src/webapp/images/rss-feed-icon.png
u    podcasts/podcasts-app/src/webapp/css/podcaster.css



----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from stephen.marquard@uct.ac.za fri jan  4 04:07:34 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.25])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 fri, 04 jan 2008 04:07:34 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 fri, 04 jan 2008 04:07:34 -0500
received: from salemslot.mr.itd.umich.edu (salemslot.mr.itd.umich.edu [141.211.14.58])
	by panther.mail.umich.edu () with esmtp id m0497wan027902;
	fri, 4 jan 2008 04:07:32 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by salemslot.mr.itd.umich.edu id 477df74e.49493.30415 ;
	 4 jan 2008 04:07:29 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 88598ba5b6;
	fri,  4 jan 2008 09:07:19 +0000 (gmt)
message-id: <200801040905.m0495rwb006420@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 385
          for ;
          fri, 4 jan 2008 09:07:04 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 90636418a8
	for ; fri,  4 jan 2008 09:07:04 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m0495szs006422
	for ; fri, 4 jan 2008 04:05:54 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m0495rwb006420
	for source@collab.sakaiproject.org; fri, 4 jan 2008 04:05:53 -0500
date: fri, 4 jan 2008 04:05:53 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to stephen.marquard@uct.ac.za using -f
to: source@collab.sakaiproject.org
from: stephen.marquard@uct.ac.za
subject: [sakai] svn commit: r39750 - event/branches/sak-6216/event-util/util/src/java/org/sakaiproject/util
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: fri jan  4 04:07:34 2008
x-dspam-confidence: 0.7554
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39750

author: stephen.marquard@uct.ac.za
date: 2008-01-04 04:05:43 -0500 (fri, 04 jan 2008)
new revision: 39750

modified:
event/branches/sak-6216/event-util/util/src/java/org/sakaiproject/util/emailnotification.java
log:
sak-6216 merge event change from sak-11169 (r39033) to synchronize branch with 2-5-x (for convenience for uct local build)

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from louis@media.berkeley.edu thu jan  3 19:51:21 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.91])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 thu, 03 jan 2008 19:51:21 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 thu, 03 jan 2008 19:51:21 -0500
received: from eyewitness.mr.itd.umich.edu (eyewitness.mr.itd.umich.edu [141.211.93.142])
	by jacknife.mail.umich.edu () with esmtp id m040pjhb027171;
	thu, 3 jan 2008 19:51:19 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by eyewitness.mr.itd.umich.edu id 477d8300.ac098.32562 ;
	 3 jan 2008 19:51:15 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id e6cc4b9f8a;
	fri,  4 jan 2008 00:36:06 +0000 (gmt)
message-id: <200801040023.m040npcc005473@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 754
          for ;
          fri, 4 jan 2008 00:35:43 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 8889842c49
	for ; fri,  4 jan 2008 00:25:00 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m040npgm005475
	for ; thu, 3 jan 2008 19:23:51 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m040npcc005473
	for source@collab.sakaiproject.org; thu, 3 jan 2008 19:23:51 -0500
date: thu, 3 jan 2008 19:23:51 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to louis@media.berkeley.edu using -f
to: source@collab.sakaiproject.org
from: louis@media.berkeley.edu
subject: [sakai] svn commit: r39749 - in bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src: bundle webapp/vm/sitesetup
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: thu jan  3 19:51:20 2008
x-dspam-confidence: 0.6956
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39749

author: louis@media.berkeley.edu
date: 2008-01-03 19:23:46 -0500 (thu, 03 jan 2008)
new revision: 39749

modified:
bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src/bundle/sitesetupgeneric.properties
bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src/webapp/vm/sitesetup/chef_site-importsites.vm
log:
bsp-1420 update text to clarify "re-use materials..." option in ws setup

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from louis@media.berkeley.edu thu jan  3 17:18:23 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.91])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 thu, 03 jan 2008 17:18:23 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 thu, 03 jan 2008 17:18:23 -0500
received: from salemslot.mr.itd.umich.edu (salemslot.mr.itd.umich.edu [141.211.14.58])
	by jacknife.mail.umich.edu () with esmtp id m03mimxy027729;
	thu, 3 jan 2008 17:18:22 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by salemslot.mr.itd.umich.edu id 477d5f23.797f6.16348 ;
	 3 jan 2008 17:18:14 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id ef439b98ce;
	thu,  3 jan 2008 22:18:19 +0000 (gmt)
message-id: <200801032216.m03mghda005292@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 236
          for ;
          thu, 3 jan 2008 22:18:04 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 905d53c2fd
	for ; thu,  3 jan 2008 22:17:52 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m03mghrs005294
	for ; thu, 3 jan 2008 17:16:43 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m03mghda005292
	for source@collab.sakaiproject.org; thu, 3 jan 2008 17:16:43 -0500
date: thu, 3 jan 2008 17:16:43 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to louis@media.berkeley.edu using -f
to: source@collab.sakaiproject.org
from: louis@media.berkeley.edu
subject: [sakai] svn commit: r39746 - in bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src: bundle webapp/vm/sitesetup
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: thu jan  3 17:18:23 2008
x-dspam-confidence: 0.6959
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39746

author: louis@media.berkeley.edu
date: 2008-01-03 17:16:39 -0500 (thu, 03 jan 2008)
new revision: 39746

modified:
bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src/bundle/sitesetupgeneric.properties
bspace/site-manage/sakai_2-4-x/site-manage-tool/tool/src/webapp/vm/sitesetup/chef_site-siteinfo-duplicate.vm
log:
bsp-1421 add text to clarify "duplicate site" option in site info

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from ray@media.berkeley.edu thu jan  3 17:07:00 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.39])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 thu, 03 jan 2008 17:07:00 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 thu, 03 jan 2008 17:07:00 -0500
received: from anniehall.mr.itd.umich.edu (anniehall.mr.itd.umich.edu [141.211.93.141])
	by faithful.mail.umich.edu () with esmtp id m03m6xaq014868;
	thu, 3 jan 2008 17:06:59 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by anniehall.mr.itd.umich.edu id 477d5c7a.4fe1f.22211 ;
	 3 jan 2008 17:06:53 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 0bc8d7225e;
	thu,  3 jan 2008 22:06:57 +0000 (gmt)
message-id: <200801032205.m03m5ea7005273@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 554
          for ;
          thu, 3 jan 2008 22:06:34 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 2ab513c2fd
	for ; thu,  3 jan 2008 22:06:23 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m03m5eqa005275
	for ; thu, 3 jan 2008 17:05:14 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m03m5ea7005273
	for source@collab.sakaiproject.org; thu, 3 jan 2008 17:05:14 -0500
date: thu, 3 jan 2008 17:05:14 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to ray@media.berkeley.edu using -f
to: source@collab.sakaiproject.org
from: ray@media.berkeley.edu
subject: [sakai] svn commit: r39745 - providers/trunk/cm/cm-authz-provider/src/java/org/sakaiproject/coursemanagement/impl/provider
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: thu jan  3 17:07:00 2008
x-dspam-confidence: 0.7556
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39745

author: ray@media.berkeley.edu
date: 2008-01-03 17:05:11 -0500 (thu, 03 jan 2008)
new revision: 39745

modified:
providers/trunk/cm/cm-authz-provider/src/java/org/sakaiproject/coursemanagement/impl/provider/coursemanagementgroupprovider.java
log:
sak-12602 fix logic when a user has multiple roles in a section

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from cwen@iupui.edu thu jan  3 16:34:40 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.34])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 thu, 03 jan 2008 16:34:40 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 thu, 03 jan 2008 16:34:40 -0500
received: from icestorm.mr.itd.umich.edu (icestorm.mr.itd.umich.edu [141.211.93.149])
	by chaos.mail.umich.edu () with esmtp id m03lydy1029538;
	thu, 3 jan 2008 16:34:39 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by icestorm.mr.itd.umich.edu id 477d54ea.13f34.26602 ;
	 3 jan 2008 16:34:36 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id cc710adc79;
	thu,  3 jan 2008 21:34:29 +0000 (gmt)
message-id: <200801032133.m03lx3gg005191@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 611
          for ;
          thu, 3 jan 2008 21:34:08 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 43c4242b55
	for ; thu,  3 jan 2008 21:34:12 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m03lx3vb005193
	for ; thu, 3 jan 2008 16:33:03 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m03lx3gg005191
	for source@collab.sakaiproject.org; thu, 3 jan 2008 16:33:03 -0500
date: thu, 3 jan 2008 16:33:03 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to cwen@iupui.edu using -f
to: source@collab.sakaiproject.org
from: cwen@iupui.edu
subject: [sakai] svn commit: r39744 - oncourse/branches/oncourse_opc_122007
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: thu jan  3 16:34:40 2008
x-dspam-confidence: 0.9846
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39744

author: cwen@iupui.edu
date: 2008-01-03 16:33:02 -0500 (thu, 03 jan 2008)
new revision: 39744

modified:
oncourse/branches/oncourse_opc_122007/
oncourse/branches/oncourse_opc_122007/.externals
log:
update external for gb.

----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from cwen@iupui.edu thu jan  3 16:29:07 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.46])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 thu, 03 jan 2008 16:29:07 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 thu, 03 jan 2008 16:29:07 -0500
received: from galaxyquest.mr.itd.umich.edu (galaxyquest.mr.itd.umich.edu [141.211.93.145])
	by fan.mail.umich.edu () with esmtp id m03lt6uw027749;
	thu, 3 jan 2008 16:29:06 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by galaxyquest.mr.itd.umich.edu id 477d5397.e161d.20326 ;
	 3 jan 2008 16:28:58 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id dec65adc79;
	thu,  3 jan 2008 21:28:52 +0000 (gmt)
message-id: <200801032127.m03lruqh005177@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 917
          for ;
          thu, 3 jan 2008 21:28:39 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 1fbb042b30
	for ; thu,  3 jan 2008 21:28:38 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m03lruk4005179
	for ; thu, 3 jan 2008 16:27:30 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m03lruqh005177
	for source@collab.sakaiproject.org; thu, 3 jan 2008 16:27:30 -0500
date: thu, 3 jan 2008 16:27:30 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to cwen@iupui.edu using -f
to: source@collab.sakaiproject.org
from: cwen@iupui.edu
subject: [sakai] svn commit: r39743 - gradebook/branches/oncourse_2-4-2/app/ui/src/java/org/sakaiproject/tool/gradebook/ui
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: thu jan  3 16:29:07 2008
x-dspam-confidence: 0.8509
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39743

author: cwen@iupui.edu
date: 2008-01-03 16:27:29 -0500 (thu, 03 jan 2008)
new revision: 39743

modified:
gradebook/branches/oncourse_2-4-2/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/rosterbean.java
log:
svn merge -c 39403 https://source.sakaiproject.org/svn/gradebook/trunk
u    app/ui/src/java/org/sakaiproject/tool/gradebook/ui/rosterbean.java

svn log -r 39403 https://source.sakaiproject.org/svn/gradebook/trunk
------------------------------------------------------------------------
r39403 | wagnermr@iupui.edu | 2007-12-17 17:11:08 -0500 (mon, 17 dec 2007) | 3 lines

sak-12504
http://jira.sakaiproject.org/jira/browse/sak-12504
viewing "all grades" page as a ta with grader permissions causes stack trace
------------------------------------------------------------------------


----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.



from cwen@iupui.edu thu jan  3 16:23:48 2008
return-path:
received: from murder (mail.umich.edu [141.211.14.91])
	 by frankenstein.mail.umich.edu (cyrus v2.3.8) with lmtpa;
	 thu, 03 jan 2008 16:23:48 -0500
x-sieve: cmu sieve 2.3
received: from murder ([unix socket])
	 by mail.umich.edu (cyrus v2.2.12) with lmtpa;
	 thu, 03 jan 2008 16:23:48 -0500
received: from salemslot.mr.itd.umich.edu (salemslot.mr.itd.umich.edu [141.211.14.58])
	by jacknife.mail.umich.edu () with esmtp id m03lnlf0002115;
	thu, 3 jan 2008 16:23:47 -0500
received: from paploo.uhi.ac.uk (app1.prod.collab.uhi.ac.uk [194.35.219.184])
	by salemslot.mr.itd.umich.edu id 477d525e.1448.30389 ;
	 3 jan 2008 16:23:44 -0500
received: from paploo.uhi.ac.uk (localhost [127.0.0.1])
	by paploo.uhi.ac.uk (postfix) with esmtp id 9d005b9d06;
	thu,  3 jan 2008 21:23:38 +0000 (gmt)
message-id: <200801032122.m03lmfo4005148@nakamura.uits.iupui.edu>
mime-version: 1.0
content-transfer-encoding: 7bit
received: from prod.collab.uhi.ac.uk ([194.35.219.182])
          by paploo.uhi.ac.uk (james smtp server 2.1.3) with smtp id 6
          for ;
          thu, 3 jan 2008 21:23:24 +0000 (gmt)
received: from nakamura.uits.iupui.edu (nakamura.uits.iupui.edu [134.68.220.122])
	by shmi.uhi.ac.uk (postfix) with esmtp id 3535542b69
	for ; thu,  3 jan 2008 21:23:24 +0000 (gmt)
received: from nakamura.uits.iupui.edu (localhost [127.0.0.1])
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11) with esmtp id m03lmftt005150
	for ; thu, 3 jan 2008 16:22:15 -0500
received: (from apache@localhost)
	by nakamura.uits.iupui.edu (8.12.11.20060308/8.12.11/submit) id m03lmfo4005148
	for source@collab.sakaiproject.org; thu, 3 jan 2008 16:22:15 -0500
date: thu, 3 jan 2008 16:22:15 -0500
x-authentication-warning: nakamura.uits.iupui.edu: apache set sender to cwen@iupui.edu using -f
to: source@collab.sakaiproject.org
from: cwen@iupui.edu
subject: [sakai] svn commit: r39742 - gradebook/branches/oncourse_2-4-2/app/ui/src/java/org/sakaiproject/tool/gradebook/ui
x-content-type-outer-envelope: text/plain; charset=utf-8
x-content-type-message-body: text/plain; charset=utf-8
content-type: text/plain; charset=utf-8
x-dspam-result: innocent
x-dspam-processed: thu jan  3 16:23:48 2008
x-dspam-confidence: 0.9907
x-dspam-probability: 0.0000

details: http://source.sakaiproject.org/viewsvn/?view=rev&rev=39742

author: cwen@iupui.edu
date: 2008-01-03 16:22:14 -0500 (thu, 03 jan 2008)
new revision: 39742

modified:
gradebook/branches/oncourse_2-4-2/app/ui/src/java/org/sakaiproject/tool/gradebook/ui/rosterbean.java
log:
svn merge -c 35014 https://source.sakaiproject.org/svn/gradebook/trunk
u    app/ui/src/java/org/sakaiproject/tool/gradebook/ui/rosterbean.java

svn log -r 35014 https://source.sakaiproject.org/svn/gradebook/trunk
------------------------------------------------------------------------
r35014 | wagnermr@iupui.edu | 2007-09-12 16:17:59 -0400 (wed, 12 sep 2007) | 3 lines

sak-11458
http://bugs.sakaiproject.org/jira/browse/sak-11458
course grade does not appear on "all grades" page if no categories in gb
------------------------------------------------------------------------


----------------------
this automatic notification message was sent by sakai collab (https://collab.sakaiproject.org/portal) from the source site.
you can modify how you receive notifications at my workspace > preferences.
