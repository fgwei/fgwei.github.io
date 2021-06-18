<div class="container">
  <div class="row">
    <div class="col-lg-12 text-center">
      <div class="navy-line"></div>
      <h1><span>About Me</span></h1>
    </div>
  </div>
  <div id="primary" class="content-area full-width">
    <main id="main" class="site-main full-width" role="main">
        <div class="fl-builder-content fl-builder-content-4135 fl-builder-content-primary fl-builder-global-templates-locked" data-post-id="4135" markdown="1">

<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">

<p style="margin-bottom:5px" markdown="1">

I am currently a Software Engineer at [Google](https://www.google.com/), and working with the Mobile Malware Detection Group.

I graduated with a Ph.D. in the department of Computer Science and Engineering at University of South Florida,
and honored to be advised by [Dr.Xinming (Simon) Ou](http://www.cse.usf.edu/~xou/).
Furthermore, I am a member of [Argus CyberSecurity Lab](http://www.arguslab.org/). 

</p>

</div></div>

<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">

## Research
    
My main research interests are in the areas of computer networks and security with emphasis on:

<div class="row">
    <div class="col-lg-12" markdown="1">

- `Applying static analysis for Android security vetting`: The focus is on detecting security issues on Android application. 
A large portion of those issues can be resolved by addressing one core problem – capturing semantic behaviors of the app 
such as object points-to and control-/data-flow information. 
Thus, we designed an approach to conducting static analysis for vetting Android apps, 
and built a generic framework, called [Argus-SAF](http://pag.arguslab.org/argus-saf),
which does inter-component, flow-/context-sensitive data flow analysis.
Based on [Argus-SAF](http://pag.arguslab.org/argus-saf),
we applied certain security applications on popular Android apps, and the results shows that the tool 
is capable of finding real security issues and efficient enough in terms of analysis time. 
Our research paper is accepted by [CCS 2014](http://www.sigsac.org/ccs/CCS2014/) and a significantly enhanced version
is accepted by [TOPS 2018](https://tops.acm.org/).
The JNI analysis part of Argus-SAF is published at [CCS 2018](https://www.sigsac.org/ccs/CCS2018/).
The Argus-SAF tool has been downloaded over 13,300 times as of Jan 2018 and
become foundation of many research projects (cited over 250 times as of Aug
2018).

</div>
<div class="col-lg-12" markdown="1">

- `Android static analysis tool chain building`: Based upon Amandroid work to design a comprehensive Android application analysis tool chain.
Then, apply it into domains like: vulnerability finding, malware detection, etc.
The current open source tools including: [Argus-SAF](https://github.com/arguslab/Argus-SAF) (Amandroid is a submodule),
Argus-CIT (code inspection IDE plugin for [eclipse](https://github.com/fgwei/argus-cit) and 
[intellij](https://github.com/arguslab/argus-cit-intellij)), 
[jawa-compiler](https://github.com/arguslab/jawa-compiler), [jawa2java](https://github.com/arguslab/jawa2java).
For detailed information, please visit my project cite: [PAG](http://pag.arguslab.org/).
    
</div>
<div class="col-lg-12" markdown="1">
    
- `Android malware categorization and landscape study`: 
By utilizing the tool chains I built during last couple years, 
I perform a large-scale landscape study to revealing 
the new threats and evolving trends of Android malware. 
This work presents a detailed picture of current malware 
behaviors and their evolving trend, 
which provides the Android malware research community 
a better ground truth dataset, 
a.k.a. [Android Malware Dataset (AMD)](http://amd.arguslab.org/),
for evaluating their approach.
AMD have been shared with 145 research
institute world-wide.
    
</div></div>
</div></div>

<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">

## Publication

<div class="col-lg-12 bs-callout bs-callout-primary">
  <h4><a href="http://www.fengguow.dev/resources/papers/JN-SafCCS18.pdf">JN-SAF: Precise and Efficient NDK/JNI-aware Inter-language Static Analysis Framework for Security Vetting of Android Applications with Native Code.</a></h4>
  <p markdown="1">**Fengguo Wei**, Xingwei Lin, Xinming Ou, Ting Chen, Xiaosong Zhang. 
  
  In the 25th ACM Conference on Computer and Communications Security. (CCS 2018)</p>
</div>

<div class="col-lg-12 bs-callout bs-callout-primary">
  <h4><a>Automated Forensic Analysis of Mobile Applications on Android Devices.</a></h4>
  <p markdown="1">Xiaodong Lin, Ting Chen, Tong Zhu, Kun Yang, **Fengguo Wei**. 
  
  In the 18th USA Digital Forensics Research Workshop. (DFRWS 2018)</p>
</div>

<div class="col-lg-12 bs-callout bs-callout-primary">
  <h4><a href="http://www.fengguow.dev/resources/papers/AmandroidTOPS18.pdf">Amandroid: A Precise and General Inter-component Data Flow Analysis Framework for Security Vetting of Android Apps.</a></h4>
  <p markdown="1">**Fengguo Wei**, Sankardas Roy, Xinming Ou, Robby. 
  
  ACM Transactions on Privacy and Security. (TOPS 2018) 
  
  **A significantly enhanced version of our Amandroid CCS 2014.**</p>
</div>

<div class="col-lg-12 bs-callout bs-callout-primary">
  <h4><a href="http://www.fengguow.dev/resources/papers/AMD-DIMVA17.pdf">Deep Ground Truth Analysis of Current Android Malware.</a></h4>
  <p markdown="1">**Fengguo Wei**, Yuping Li, Sankardas Roy, Xinming Ou, and Wu Zhou.
   
   In the 14th Conference on Detection of Intrusions and Malware & Vulnerability Assessment. (DIMVA 2017)</p>
</div>

<div class="col-lg-12 bs-callout bs-callout-primary">
  <h4><a href="http://www.fengguow.dev/resources/papers/AmandroidCCS14.pdf">Amandroid: A Precise and General Inter-component Data Flow Analysis Framework for Security Vetting of Android Apps.</a></h4>
  <p markdown="1">**Fengguo Wei**, Sankardas Roy, Xinming Ou, Robby. 
  
  In the 21st ACM Conference on Computer and Communications Security. (CCS 2014)</p>
</div>


<p style="line-height:1">
<font size="-2">
The documents contained in these pages are included to ensure timely dissemination 
of scholarly and technical work on a non-commercial basis. 
Copyright and all rights therein are maintained by the authors or by other 
copyright holders, notwithstanding that they have offered their works here electronically. 
It is understood that all persons copying this information will adhere to the terms and constraints 
invoked by each author's copyright. These works may not be reposted without the explicit permission 
of the copyright holder.
</font></p>

</div></div>

<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">
    
## Education

<div class="col-lg-12 bs-callout bs-callout-warning">
  <h4>University of South Florida, Tampa, FL, USA</h4>
  <p markdown="1">**Ph.D. student** in Computer Science, August 2015 – May 2018</p>
</div>

<div class="col-lg-12 bs-callout bs-callout-warning">
  <h4>Kansas State University, Manhattan, KS, USA</h4>
  <p markdown="1">**Ph.D. student** in Computer Science, August 2012 - August 2015</p>
</div>

<div class="col-lg-12 bs-callout bs-callout-warning">
  <h4>People’s Public Security University, Beijing, China</h4>
  <p markdown="1">**B.S.** in Computer Science, September 2008 - June 2012</p>
</div>

</div></div>
<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">

## Industry Experience

<div class="col-lg-12 bs-callout bs-callout-default" markdown="1">
  <h4>Google, Mountain View, CA</h4>
  **Software Engineer**, July 2018 - Present\\
  Manager: Monirul Sharif
  
  Mobile malware detection.
  
</div>

<div class="col-lg-12 bs-callout bs-callout-default" markdown="1">
  <h4>JD.com American Technologies Corporation, Santa Clara, CA</h4>
  **Research & Development Intern**, Sep 2017 - Nov 2017\\
  Supervisor: Yueh-Hsun Lin, Manager: Jimmy Su
  
  I am doing code review for JD’s web framework and applications to identify vulnerabilities. I am also doing hybrid code analysis research to provide automation solutions for java vulnerability finding.
  
</div>

<div class="col-lg-12 bs-callout bs-callout-default" markdown="1">
  <h4>SIG, Synopsys Inc, San Francisco, CA</h4>
  **Research & Development Intern**, May 2017 - August 2017\\
  Supervisor: Aaron Hurst, Manager: Timothy Alper
  
  I am working in the Software Integrity Group (SIG) R&D team to design WEB/Android/IOS security checkers for Coverity static analysis tool.
  
</div>

<div class="col-lg-12 bs-callout bs-callout-default" markdown="1">
  <h4>B2B Lab, Samsung Research America, Mountain View, CA</h4>
  **Research & Development Intern**, January 2015 - July 2015\\
  Supervisor: Wu Zhou, Manager: Michael Grace
  
  Our team is responsible of providing security solutions for Samsung’s internal products. My work includes:
  
  - Perform static analysis and manual analysis for Samsung KNOX Trust-zone applications, and Samsung Pay backend framework codes.
  - Designed an integrated android application reverse engineering and code analysis tool called Argus-CIT (Argus Code Inspect Tool), and implemented as a plugin for IntelliJ.
  
</div>

<div class="col-lg-12 bs-callout bs-callout-default" markdown="1">
  <h4>China Academy of Launch Vehicle Technology, Beijing, China</h4>
  **Research Intern**, June 2011 – August 2011\\
  Supervisor: Shuliang Ren
  
  Central Control with MES System Integration Development.
  <div class="col-lg-12" markdown="1">
  - Participated in the control system interface development of external system which including the enterprise service bus (ESB), Web service and XML.
  </div>
</div>

</div></div>

<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">

## Professional Affiliations

- The Honor Society of [Phi Kappa Phi](http://www.phikappaphi.org/web/) (ΦΚΦ)

</div></div>

<div class="fl-row fl-row-full-width fl-row-bg-color fl-node-571945cc8ecfb about-section">
    <div class="wow animated fadeIn" markdown="1">

## miscellaneous

<div class="col-lg-12" markdown="1">

- My chinese name is `魏丰国` [<a class="pinyin tone4" href="/mp3/wei4.mp3" id="audiolink">wèi</a> <a class="pinyin tone1 " href="/mp3/feng1.mp3">fēng</a> <a class="pinyin tone2 " href="/mp3/guo2.mp3">guó</a>]

</div>

<div class="col-lg-12" markdown="1">

- I play a little Harmonica ([Blues harp](https://en.wikipedia.org/wiki/Richter-tuned_harmonica) and [Chromatic](https://en.wikipedia.org/wiki/Chromatic_harmonica)), Piano, and Guitar, non-professional, just for enjoyment.

</div>

<div class="col-lg-12" markdown="1">

- I am currently 5th kyū in [Aikido](https://en.wikipedia.org/wiki/Aikido). Aikido (Japanese: 合気道) [aikiꜜdoː] is a modern Japanese martial art developed by [Morihei Ueshiba](https://en.wikipedia.org/wiki/Morihei_Ueshiba) as a synthesis of his martial studies, philosophy, and religious beliefs.

</div>

<div class="col-lg-12" markdown="1">

- The cover image is [Huang Guo Shu Waterfall](https://en.wikipedia.org/wiki/Huangguoshu_Waterfall) (also known as Yellow Fruit Tree Waterfall) near my hometown.
It is the world third largest waterfall located on the Baishui (white water) River in Anshun, Guizhou province, China.

</div>

</div></div>

</div></main></div></div>
