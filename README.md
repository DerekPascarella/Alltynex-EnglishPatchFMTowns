<h1>Alltynex</h1>
<img width="165" height="124" align="right" src="https://github.com/DerekPascarella/Alltynex-EnglishPatchFMTowns/blob/main/title_screen.png?raw=true">English translation patch for the doujin shooting game "Alltynex" on the FM Towns, created and developed by Satoshi Yoshida.
<br><br>
"Alltynex" was originally distributed for hard drive installation on 486 FM Towns computers. However, a self-booting CD-ROM disc image was compiled by <a href="https://nfggames.com/forum2/index.php?action=profile;u=4501">Anna Wu</a>. Due to this custom disc image's use of TOWNS OS V2.1 L51, the consolized FM Towns Marty was unable to boot it. Given the Marty includes a 386 CPU, this is seen largely as a non-issue, as "Alltynex" requires a 486 CPU for full-speed gameplay. However, a new version of this self-booting disc image was created for this patch, using TOWNS OS V2.1 L40, so that it can be used on the Marty, even with slowdown.
<br><br>
The latest version of this patch is <a href="https://github.com/DerekPascarella/Temptation-EnglishPatchFMTowns/releases/download/0.91/Temptation.T-En.v0.91.xdelta">1.0</a>.

<h2>Table of Contents</h2>

1. [Patching Instructions](#patching-instructions)
2. [Credits](#credits)
3. [Release Changelog](#release-changelog)
4. [What's Changed](#whats-changed)
5. [How to Play](#how-to-play)

<h2>Patching Instructions</h2>
This patch targets the hard-drive image named "Alltynex.h0" distributed by the "Neo Kobe" set of FM Towns/Marty software. Its original MD5 checksum is <tt>87527376B66A8E895D25B33C4C41E2A6</tt>.
<br><br>
To apply this patch, download the <a href="https://github.com/DerekPascarella/Alltynex-EnglishPatchFMTowns/releases">latest release</a> and extract it to a folder of your choosing.
<br><br>
Next, copy "Alltynex.h0" into the same folder and launch the "apply_patch.bat" script. This will produce "Alltynex (T-En v1.0).iso" with an MD5 checksum of <tt>FAF881AC83FD2A15D738799408240141</tt>

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
 <li>Menu text has been altered from original "Engrish" spellings and grammar.</li>
 <li>Stage opening and closing text has been altered from original "Engrish" spellings and grammar.</li>
</ul>

<h2>How to Play</h2>
<ul>
 <li><b>ODE (Optical Drive Emulator)</b>
  <br>
  The English-patched version of this game is compatible with both the <a href="https://gdemu.wordpress.com/details/docbrown-details/">DocBrown</a> and <a href="https://gdemu.wordpress.com/details/wizard-details/">Wizard</a> ODEs for the FM Towns Marty and the FM Towns, respectively.  Note that only the patched <tt>.bin</tt> file should be copied to the SD card, as neither ODE supports parsing CUE sheets.  Because "Temptation" uses only one data track with no CDDA, both of these ODEs are compatible with the single <tt>.bin</tt>.
  <br><br>
  This game, like many on the FM Towns, requires a user disk to boot the game disc. Note that progress can also be saved to the same disk. For users of FDD emulators (e.g., <a href="https://www.gotekemulator.com/">GoTek</a>, <a href="https://caiusarcade.blogspot.com/2021/05/the-thing-fm-towns-marty-fdd-emulator.html">The Thing</a>), download disk image below.
  <br><br>
  ⯈ <a href="https://github.com/DerekPascarella/Temptation-EnglishPatchFMTowns/raw/main/fdd_images/Temptation%20(User%20Disk).hfe">Temptation (User Disk).hfe</a>
  <br><br>
 </li>
 <li><b>Emulator</b>
  <br>The English-patched version of this game is compatible with the <a href="https://github.com/captainys/TOWNSEMU">Tsugaru</a> emulator, and likely <a href="http://townsemu.world.coocan.jp/download.html">Unz</a> as well.  This game, like many on the FM Towns, requires a user disk to boot the game disc. Note that progress can also be saved to the same disk. The following disk image has been tested and confirmed working with Tsugaru.
  <br><br>
  ⯈ <a href="https://github.com/DerekPascarella/Temptation-EnglishPatchFMTowns/raw/main/fdd_images/Temptation%20(User%20Disk).d88">Temptation (User Disk).d88</a>
</ul>
