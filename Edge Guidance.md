---
extensions:
  preset: gfm

---

<h1 id="microsoft-edge-guidance---january-2020">Microsoft Edge Guidance - January 2020</h1>
<h2 id="situation">Situation</h2>
<p><img src="https://www.file-extensions.org/imgs/app-icon/128/11586/microsoft-edge.png" alt="Legacy Edge Icon"><br>
Microsoft Edge, which was introduced with Windows 8 and continued into Windows 10 up to version 45, will be referred to as <em>Legacy Edge</em>.</p>
<p><img src="https://udger.com/pub/img/ua/Microsoft_Edge_big.png" alt="New Edge Icon January 2020"><br>
The new version of Microsoft Edge, released on January 15, 2020 beginning with version 79, will be referred to as <em>Edge</em> or <em>Microsoft Edge</em>.</p>
<h2 id="background">Background</h2>
<p>Microsoft Edge is <strong>not</strong> being deployed to Windows 7 and <em>Legacy Edge</em> is <strong>not</strong> being updated on Windows 10 at this time.</p>
<p>SA-EDS is <strong>testing</strong> Edge in a controlled environment in order to develop understanding, documentation, and configurations which will be needed for when a decision is made to deploy/update. Windows 10 version 2004 (20H1) will ship with Edge thus replacing <em>Legacy Edge</em></p>
<h2 id="assessment">Assessment</h2>
<h3 id="internet-explorer-ie-is-not-replaced.">Internet Explorer (IE) is not replaced.</h3>
<p><img src="https://prabidhi.info/wp-content/uploads/2019/11/microsoft-edge-old-logo-new-logo-e1572852302325-696x285.png" alt="enter image description here"><br>
The new Microsoft Edge replaces <em>Legacy Edge</em> on Windows 10. This new version of Edge is based on Google's open source Chromium project, to which Microsoft is a contributor, and which is used in Google Chrome.<br>
On Windows 7 there was no previous version of Edge so Edge is installed alongside IE.</p>
<h3 id="legacy-websites-flash-java--silverlight-are-handled-by-ie">Legacy websites, Flash, Java, &amp; Silverlight are handled by IE</h3>
<p><img src="https://lh3.googleusercontent.com/_Km3MdBqHdsEIPh1qIZ4UN4X7f1iAo-sDZSzo6eNU0MhBphwN6_gqPfnlt-92bHsPt2YIvjIY2w" alt="IE tab in Edge Windows 7"><br>
On Windows 10 the same technology which has redirected legacy websites to IE continues to function as before with the added benefit of displaying pages in a tab and thus not requiring a new window. On Windows 7, and with August 2019 update <a href="https://support.microsoft.com/en-us/help/4511872/cumulative-security-update-for-internet-explorer">KB4511872</a> installed together with commensurate configuration used for Windows 10, Microsoft Edge functions the same as <em>Legacy Edge</em> and legacy websites, as needed, will still be rendered by IE.</p>
<h2 id="recommendation">Recommendation</h2>
<ul>
<li>SA-EDS will, along with consultation from stake holders, determine when and if Edge would be deployed to Windows 7.</li>
<li>SA-EDS will consult on Edge upgrades for Windows 10 to determine when and if the upgrade should be approved for versions of Windows 10 prior to 2004.</li>
<li>Starting with Windows 10 version 2004 (20H1) <em>Legacy Edge</em> will no longer be included in the OS as published by Microsoft; SA-EDS is already working on group policy, Enterprise Mode IE site list, and other configurations to have in place to assure a smooth transition.</li>
</ul>

