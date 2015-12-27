Model.Root.Note=This page presents the key=value pairs, (aka properties) in the order that they are used in rendering.  Normally, they are presented in the order of most recent to oldest, as new is usually added at the top. But for a first-time reading, it is helpful to see how the page is built.  

Model.Root=<center>{Logo}<br><br><b>{Site.Name}</b></center></p><br>{Content.Sec}

Logo=<img src="File/cmacc-trans.png" style="width:35%" />

Site.Name=CommonAccord.Org

Content.Sec=<table><tr><td width="50%">{Intro.Sec}</td><td>   </td><td>{TwitterBlock.sec}<br><br><b><a href="https://github.com/CommonAccord/Cmacc-Org/commits/master">Latest Activity on GitHub</a></b><br><br>{DocumentsFolder.sec}<br>{SubjectIndex.Sec}<br>{RecentWork.Sec}</td></tr></table>

Intro.Sec={Introduction.sec}<br><br>{SiteLinks.Sec}

Introduction.sec=<b>Overview:</b><ul><li>{CmAQuick.sec}<li>{Codification.sec}<li>{Code-ification.sec}</ul>

CmAQuick.sec=CommonAccord is an initiative to codify and automate legal documents, including contracts, permits, organizational documents, and consents.  We do this by "code-ifying" them, treating them like software source code: folders of files of key/values of HTML, hosted on GitHub.  We collaborate on model forms, sections, clauses, and ways of using them.   The shared materials provide starting points for transactions and will merge to form "legal codes" of transacting.  We also develop "object models" for transaction fields and transacting generally. 

Codification.sec=Codification of documents with legal significance can make them transparent, well-understood and continuously improving.  It can demystify law and encourage <a href="http://p2pfoundation.net/Common_Accord">P2P autonomy</a>.

Code-ification.sec={PDS.sec}<li>{OnGitHub.sec}<li> {InfoLinks.sec} <li>{DeCenter.sec}

PDS.sec=P2P enables everyone to have folders of files that state their legal relationships and transaction histories with everyone else.  These are private, under their control, handled however they want. They transact by synchronizing new files with partners. Synchronization can be done by git, blockchain, or any other method the parties find satisfactory, including email, Skype, and Slack.

OnGitHub.sec=All of the text, and the little bit of code that brings it together, is on <a href="http://github.com/CommonAccord/Cmacc-Org">GitHub</a>.

InfoLinks.sec={ParserByPrimavera.sec} {Peer2Peer.sec} {XrayView.sec} {Slashdot.sec} {Technical.sec}

ParserByPrimavera.sec=This website uses a parser done by <a href="https://cyber.law.harvard.edu/people/pdefilippi">Primavera De Filippi of Harvard's Berkman Center</a>.

Peer2Peer.sec=It supports a <a href="index.php?action=doc&file=S/About/Pitch/Support/DRY_Transacting_v0.md">"DRY," peer-to-peer transaction model</a>, including with <a href="http://hardjono.mit.edu/sites/default/files/documents/CommonAccord_Provenance_11182015.pdf">blockchain and UMA (pdf)</a>.  There can be  <a href="http://financialcryptography.com/mt/archives/001556.html">close coupling of "smart contracts" and contract text</a>, enabling <a href="http://iang.org/ricardian/">"Ricardian" contracts</a>.

XrayView.sec=A taste of the "experience" can be seen  in this <a href="https://www.youtube.com/watch?v=4ZfsyTPYFIA">YouTube video</a>.

Slashdot.sec=The vision was articulated in an <a href="http://news.slashdot.org/story/13/07/25/1814255/attorney-jim-hazard-is-working-to-open-source-law-video"> OSCON interview with Slashdot</a>

DeCenter.sec=We are working toward a "<a href="index.php?action=doc&file=S/About/Pitch/Support_v0.md">Center for Decentralized Law</a>," a trustee for global legal code.  The project is open source. You can contribute: as a lawyer to legal documents, as a coder to our software, as a platform by interfacing with our materials, as a business by using the system, as a benefactor by supporting the effort.  <a href="http://github.com/commonaccord/cmacc-org">Contribute on GitHub</a> or <a href="mailto:commonaccord@gmail.com?Subject=Contact" target="_top">email commonaccord@gmail.com.</a>

Technical.sec=The files can also be expressed in <a href="http://www.commonaccord.org/index.php?action=json&file=Dx/Acme_FR/04-NDA-From-Quake-FR/Doc_v0.md">JSON</a> or managed as <a href="http://neo4j.com/graphgist/github-HazardJ%2Fgists%2F%2FDoc_Source_Graph.adoc/">graphs</a>.


SiteLinks.Sec=<b>Site links:</b><ul type=none><li>{DocumentsFolder.sec}<li>{Views.List.sec}<li>{PageSource.sec}</ul>

Views.List.sec=Each file on the site has six "views": <a href="index.php?action=source&file=Dx/Acme_UK/01-EU-US-DataTransfer/Doc_v0.md">Source</a>.  E.g., click on <a href="index.php?action=doc&file=Dx/Acme_UK/01-EU-US-DataTransfer/Doc_v0.md">"Document"</a>.

PageSource.sec=This page is made using the tool ("dog fooding" in tech parlance): <a href="index.php?action=source&file=S/About/Landing.md">Landing Page Source</a>.
  
DemoDocName=Dx/Acme_UK/01-EU-US-DataTransfer/Doc_v0.md

DocumentsFolder.sec=<a href="index.php?action=list&file=/">Top level</a> folder of files.

SubjectIndex.Sec=<a href="index.php?action=list&file=/S/Index">Subject Index</a> of (some) materials.

RecentWork.=[S/About/RecentWork/0.md]

TwitterBlock.sec=<a class="twitter-timeline" href="https://twitter.com/CommonAccord/with_replies" data-widget-id="574817616360964096" width="600" height="300">Tweets by @CommonAccord</a><script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>

TwitterBlock.sec=<a class="twitter-timeline" href="https://twitter.com/CommonAccord/with_replies" data-widget-id="574817616360964096" width="600" height="300">Tweets by @CommonAccord</a><script>!function(d,s,id){var js,fjs=d.getElementsByTagName(s)[0],p=/^http:/.test(d.location)?'http':'https';if(!d.getElementById(id)){js=d.createElement(s);js.id=id;js.src=p+"://platform.twitter.com/widgets.js";fjs.parentNode.insertBefore(js,fjs);}}(document,"script","twitter-wjs");</script>