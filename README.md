<h1>Alltynex</h1>
<img width="165" height="124" align="right" src="https://github.com/DerekPascarella/Alltynex-EnglishPatchFMTowns/blob/main/title_screen.png?raw=true">English translation patch for the doujin shooting game "Alltynex" on the FM Towns, created and developed by Satoshi Yoshida.
<br><br>
"Alltynex" was originally distributed for hard-drive installation on 486 FM Towns computers. However, a self-booting CD-ROM disc image was compiled by <a href="https://nfggames.com/forum2/index.php?action=profile;u=4501">Anna Wu</a>. Due to this custom disc image's use of TOWNS OS V2.1 L51, the consolized FM Towns Marty was unable to boot it.
<br><br>
Given the Marty includes a 386 CPU, this is seen largely as a non-issue, as "Alltynex" requires a 486 CPU for full-speed gameplay. However, a new version of this self-booting disc image was created for this patch, using TOWNS OS V2.1 L40, so that it can be used on the Marty, even with slowdown. This also future-proofs this patch should future modifications to the Marty allow for a sensible CPU upgrade.
<br><br>
The latest version of this patch is <a href="https://github.com/DerekPascarella/Alltynex-EnglishPatchFMTowns/releases/download/1.0/Alltynex.T-En.v1.0.zip">1.0</a>.

<h2>Table of Contents</h2>

1. [Patching Instructions](#patching-instructions)
2. [Credits](#credits)
3. [Release Changelog](#release-changelog)
4. [What's Changed](#whats-changed)
5. [How to Play](#how-to-play)

<h2>Patching Instructions</h2>
This patch targets the hard-drive image named <tt>Alltynex.h0</tt> distributed by the "Neo Kobe" set of FM Towns/Marty software. Its original MD5 checksum is <tt>87527376B66A8E895D25B33C4C41E2A6</tt>.
<br><br>
To apply this patch, download the <a href="https://github.com/DerekPascarella/Alltynex-EnglishPatchFMTowns/releases">latest release</a> and extract it to a folder of your choosing.
<br><br>
Next, copy <tt>Alltynex.h0</tt> into the same folder and launch the <tt>apply_patch.bat</tt> script. This will produce <tt>Alltynex (T-En v1.0).iso</tt> with an MD5 checksum of <tt>FAF881AC83FD2A15D738799408240141</tt>.

<h2>Credits</h2>
<ul>
 <li><b>Hacking</b></li>
  <ul>
   <li>Derek Pascarella (ateam)</li>
  </ul>
 <br>
 <li><b>Translation</b></li>
  <ul>
   <li>Walnut</li>
  </ul>
</ul>

<h2>Release Changelog</h2>
<ul>
 <li>Version 1.0 (2024-04-02)</li>
 <ul>
  <li>Initial release.</li>
 </ul>
</ul>

<h2>What's Changed</h2>
<ul>
 <li>TOWNS OS V2.1 L40 and its libraries used so that disc image can be booted on Marty.</li>
   <ul>
    <li>Note that there is significant slowdown on both the Marty and any 386 FM Towns.</li>
   </ul>
 <li>Opening and closing scene text has been translated into English.</li>
 <li>Staff credits have been translated into English.</li>
 <li>Menu text has been altered from original "Engrish" spellings and grammar.</li>
 <li>Stage opening and closing text has been altered from original "Engrish" spellings and grammar.</li>
</ul>

<h2>How to Play</h2>
<ul>
 <li><b>ODE (Optical Drive Emulator)</b>
  <br>
  The English-patched version of this game is compatible with both the <a href="https://gdemu.wordpress.com/details/docbrown-details/">DocBrown</a> and <a href="https://gdemu.wordpress.com/details/wizard-details/">Wizard</a> ODEs for the FM Towns Marty and the FM Towns, respectively.  Note that only the patched <tt>.iso</tt> file should be copied to the SD card, as neither ODE supports parsing CUE sheets.  Because "Alltynex" uses only one data track with no CDDA, both of these ODEs are compatible with the single <tt>.iso</tt>.
  <br><br>
 </li>
 <li><b>Emulator</b>
  <br>The English-patched version of this game is compatible with the <a href="https://github.com/captainys/TOWNSEMU">Tsugaru</a> emulator, and likely <a href="http://townsemu.world.coocan.jp/download.html">Unz</a> as well. Note that Tsugaru should be configured to use a 486 CPU for optimal game performance.
</ul>
