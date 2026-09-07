---
title: LFX'26 - urunc
tags:
  - urunc
  - cncf
  - lfx
---
![[2026-lfx.png]]
I thought of managing the digital footprint on LFX'26 process. So i thought, why not document the process in my Obsidian vault. However, this is something I will impromptively write/ transcribe. **So do expect bad grammar and typos.**

I've been introduced to open source around 2017-2018 and ve been more structurally contributing since 2020, but those were on-and-off small contributions via raising issues or small upstream PRs. To date, there is no single OSS project that I can call home. I love systems engineering and open source, but life had other plans to keep me busy with research work, PhD applications, job, and family commitments. 

But this August, I got a clean 3-month window where I can finally have some pause before new beginnings. But as my wife Jayani says, *you will never be free and relaxed*. I have this weird behavior of searching the corners of the web and applying for something to keep me engaged.

So, following that, I've been attempting to engage with a few open-source projects. I was drawn to two projects. A few months back, [[OpenSearch for AssociationRule Mining With ActivityWatch|my talk at OpenSearch Con India]] and the network I built there drawn me to OpenSearch, and I had this new found interest around agent sandboxes, which introduced me to a project named urunc. urunc is an OCI compatible runtime for unikernels, but it's not limited to unikernels. In a way I believe urunc was the missing link to bring the absolute best security to sandboxes (which currently primarily rely on gVisor or Kata containers). Anyway, that's a rabbit-hall ill dive in later, but my objective here is to document LFX program work, which I will stick to.

While playing around with urunc, I noticed LFX'26 winter call is open, and urunc is actually taking part. LFX mentorship was something I was well aware of from my indian colleagues I met at KubeCon|OpenSource Summit (It was actually big in India). There were 2 urunc issues willing to take mentees, so I applied to both. 

![[2026-lfx-application.png|367]]

The application process was not very easy, I would say. In the one I got in, I had to
1. Replicate the GitHub issue
2. Face an interview with maintainers 
In addition to the normal LFC102, cover letter, and resume submission. That work clearly required someone a bit experienced in Kubernetes, Argo, and low-level systems engineering. My cover letter and issue replication are embedded below.
<iframe src="https://drive.google.com/file/d/13hm-1Q8HzjakOfBc1eDo0cNhh6sfIgqY/preview" width="640" height="480"></iframe>
<iframe src="https://drive.google.com/file/d/1DJdi6QnF-35HgTBd5ACEw69p4QhjGqSm/preview" width="640" height="480"></iframe>

Also for the interview with maintainers I went with an Excalidraw diagram on issue replication which I used to hilight the actual issue and walk maintainers through potential directions.

![[2026-argo-urunc-issue-replication.png]]

I also didn't stop at Argo; I tested the same setup with Tekton Chains as well. The issue persisted there also, with a slightly different outlook, and I think that helped me generalise the issue and show wider interest not limited to Argo Workflow for LFX's sake.

Yeah, all in all, that's pretty much what I did to get in: no previous upstream PRs at the project, no show in any of the community calls, no messaging on the Slack group, no messaging under the GH issue, not DMing maintainers (which I of course do not recommend at all). It was all freshly initiated genuine passion for the project and showing that I can engage in intellectual conversation with maintainers deeply, hands-on solving difficult engineering challenges + my background in Kubernetes and platform engineering could have helped too.

The next phases of the project I will write as Eps. Things that go well, things that go bad; I aim to write all of it as a reference point for myself, plus to motivate someone following the way...