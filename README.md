
<h1>HTML5 Video</h1>
<h2>Why we need it ? (pros)</h2>
<ul>
<li>
<span style="text-align: center;">Doesn't require plug-in.&nbsp;</span>
</li>
<li>
<span style="text-align: center;">Built into browser so better performance.</span>
</li>
<li>
<span style="text-align: center;">CLEANER CODE</span>
</li>
<li>
<span style="text-align: center;">MOBILE, MOBILE, MOBILE</span>
</li>
<li>
<span style="text-align: center;">LEGACY/CROSS BROWSER SUPPORT</span>
</li>
</ul>
<h2>Elements</h2>








<p class="p1" style="text-align: left; ">
    </p>
<ul>
<li>
<span style="font-size: 24px;">
    <b>autoplay*</b>
</span>
<br>
</li>
<li>
<span>
    <font style="font-size: 24px;">preload</font>
</span>
</li>
<ul>
<li>
<b style="background-color: rgba(255, 255, 255, 0.0470588); font-size: 24px;">none</b>
<span style="background-color: rgba(255, 255, 255, 0.0470588); font-size: 24px;"> - Hints to the browser that the user likely will not watch the video,&nbsp;</span>
</li>
<li>
<b style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);">metadata</b>
<span style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);"> - Hints to the browser that the user is not expected to need the video, but that fetching its metadata (dimensions, first frame, track list, duration, and so on) is desirable.</span>
</li>
<li>
<b style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);">
<span class="Apple-tab-span">&nbsp;</span>auto</b>
<span style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);"> - Hints to browser that optimistically downloading the entire video</span>
</li>
</ul>
<li>
<font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;">poster :&nbsp;</font>
<span style="font-size: 24px;">Provides an image to show before the video loads</span>
<br>
</li>
<li>
<font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;">controls* :&nbsp;</font>
<span style="font-size: 24px;">Shows the default video controls (play, pause, etc)</span>
<br>
</li>
<li>
<font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;">height &amp; width &nbsp;:&nbsp;</font>
<span style="font-size: 24px;">Sets the width and height of the video in CSS pixels</span>
<br>
</li>
<li>
<font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;">loop* :&nbsp;</font>
<span style="font-size: 24px;">Tells the browser to automatically loop the video</span>
<br>
</li>
<li>
<font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;">muted* :&nbsp;</font>
<span style="font-size: 24px;">Mute s the audio from the video</span>
<br>
</li>
</ul>
<p>
</p>

</div>
</section>
<section>
    <h2>
        <font style="font-size: 18px;">
            <br>
        </font>
    </h2>
<div>
    <b>
    <font style="font-size: 32px;">Video</font>
</b>
</div>
<div>
<div>
<font style="font-size: 24px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;source src="../video/movie.webm" type="video/webm"&gt;</font>
</div>
<div>
<br>
</div>
<div>
<font style="font-size: 32px;">
    <b>Subtitle</b>
</font>
</div>
<div>
<font style="font-size: 24px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;track src="../video/subtitles_en.vtt" label="English subtitles" kind="subtitles" srclang="en" default&gt;&lt;/track&gt;</font>
</div>
</div>
<div>
<font style="font-size: 24px;">
    <br>
</font>
</div>
<div>
<font style="font-size: 24px;">
    <div style="font-size: 36.11820602416992px; font-style: normal; font-variant: normal;">Audio&nbsp;</div>
<div style="font-size: 36.11820602416992px; font-style: normal; font-variant: normal;">
    <font style="font-size: 24px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;audio src="audio.mp3" controls preload&gt;&lt;/audio&gt;</font>
</div>
<div>
<font style="font-size: 24px;">
    <br>
</font>
</div>
</font>
</div>
</section>
<section>
    <h2>
        <br>
    </h2>
</section>
</section>
<section>
    <section>
        <h2>HTML5 Video Sources</h2>
<div>
        <font style="font-size: 24px;">
            <br>
        </font>
    </div>
<div>
    <div style="text-align: left;">
<div>
    <font style="font-size: 24px;">
        <span class="Apple-tab-span" style="white-space:pre">   </span>•<span class="Apple-tab-span" style="white-space:pre">   </span>MP4 = MPEG 4 files with H264 video codec and AAC audio codec</font>
    </div>
<div>
    <font style="font-size: 24px;">
        <span class="Apple-tab-span" style="white-space:pre">   </span>•<span class="Apple-tab-span" style="white-space:pre">   </span>WebM = WebM files with VP8 video codec and Vorbis audio codec</font>
    </div>
<div>
    <font style="font-size: 24px;">
        <span class="Apple-tab-span" style="white-space: pre;"> </span>•<span class="Apple-tab-span" style="white-space: pre;"> </span>Ogg/Ogv/Ogm = Ogg files with Theora video codec and Vorbis audio codec</font>
    </div>
</div>
</div>
</section>
<section>
    <h2 style="text-align: left; ">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;Browser Support</h2>
<div>
    <br>
</div>
<blockquote style="margin: 0 0 0 40px; border: none; padding: 0px;">
<div>
    <table class="reference notranslate" style="font-variant: normal; font-size: 13px; width: 821px; color: rgb(64, 64, 64); font-style: normal; background-color: rgb(255, 255, 255);">
        <tbody>
<tr style="background-color: rgb(246, 244, 240);">
<th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 199px;">Browser</th>
<th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 198px;">MP4</th>
<th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 198px;">WebM</th>
<th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 198px;">Ogg</th>
</tr>
<tr>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">Internet Explorer</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">NO</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">NO</td>
</tr>
<tr style="background-color: rgb(246, 244, 240);">
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">Chrome</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
</tr>
<tr>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">Firefox</td>
<td style="font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
<div style="text-align: center;">NO</div>
<strong>
        <div style="text-align: center;">
<strong>Update:</strong>&nbsp;Firefox 21 running on Windows 7, Windows 8, Windows Vista, and Android now supports MP4</div>
    </strong>
</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
</tr>
<tr style="background-color: rgb(246, 244, 240);">
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">Safari</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">NO</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">NO</td>
</tr>
<tr>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">Opera</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">NO</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
<td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">YES</td>
</tr>
</tbody>
</table>
</div>
</blockquote>
<div style="text-align: left;">
<span>
    <br>
</span>
</div>
</section>
</section>
<section>
    <section>
        <h2 style="text-align: center;">Video Codecs &amp;&nbsp;<span style="font-size: 75.96px;">Encoding Video</span>
</h2>
<div>
        <span style="font-size: 75.96px;">
            <br>
        </span>
    </div>
<div>
<p>
    <font style="font-size: 32px;">H.264</font>
</p>
<p>
<font style="font-size: 32px;">
    <br>OGG THRORA</font>
</p>
<p>
<font style="font-size: 32px;">
    <br>VP8(WEBM)</font>
</p>
<p>
<font style="font-size: 32px;">
    <br>
</font>
</p>
<p>
<font style="font-size: 32px;">
    <a href="http://techcrunch.com/2014/01/02/googles-vp9-video-codec-gets-backing-from-arm-nvidia-sony-and-others-gives-4k-video-streaming-a-fighting-chance/?utm_campaign=fb&amp;ncid=fb">VP9 - Just released</a>
</font>
</p>
</div>
</section>
<section>
    <h2>How to Specify Codec&nbsp;</h2>
<div>
    <br>
</div>
<div>
<br>
</div>
<div>
<div>
    <ul>
<li style="text-align: left; ">
<span style="font-size: 24px; text-align: center;">&lt;source src="path/to/myvideo.mp4" type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'&gt;</span>
    <br>
</li>
<li style="text-align: left; ">
<span style="font-size: 24px; text-align: center;">&lt;source src="path/to/myvideo.ogv" type='video/ogg; codecs="theora, vorbis"'&gt;</span>
    <br>
</li>
<li style="text-align: left; ">
<span style="font-size: 24px; text-align: center;">&lt;source src="../video/movie.webm" type='video/webm codecs="vp8, vorbis"'&gt;</span>
    <br>
</li>
</ul>
</div>
</div>
</section>
</section>
<section>
    <h2>ADAPTIVE sTEAM HTML5</h2>
<div>
    <br>
</div>
<div>
<br>
</div>
<div>AVS - adobe Scene7 - Scene7 player</div>
<div>
<br>
</div>
<div>
<div style="font-size: 36.11820602416992px; font-style: normal; font-variant: normal;">m3u8 - Safari</div>
<div>
<span>
<font style="font-size: 24px;">you can't simply point your video tag to a local .m3u8, but rather, you must point it to an .m3u8 file that is being served over HTTP.</font>
</span>
<br>
</div>
<div style="font-size: 36.11820602416992px; font-style: normal; font-variant: normal;">
<br>
</div>
</div>
</section>
<section>
    <h2>Video Converter</h2>
<div>
    <br>
    </div>
<div>
<div>
<span class="Apple-tab-span" style="white-space:pre">   </span>
    <a href="http://www.mirovideoconverter.com/">Miro Video Converter</a>
</div>
<div>
    <br>
    </div>
<div>
<span class="Apple-tab-span" style="white-space:pre">   </span>
    <a href="http://handbrake.fr/">Handbrake</a>
</div>
<div>
    <br>
    </div>
<div>
<span class="Apple-tab-span" style="white-space:pre">   </span>
    <a href="http://www.squared5.com/">MPEG Streamclip ()</a>
</div>
<div>
    <br>
    </div>
<div>
<span class="Apple-tab-span" style="white-space:pre">   </span>
    <a href="http://firefogg.org/">Firefogg</a>
</div>
</div>
</section>
<section>
    <h2>Good Video Player in market&nbsp;</h2>
<div>
    <br>
</div>
<div>
<font style="font-size: 32px;">http://www.jwplayer.com/<br>
</font>
<br>http://www.videojs.com/<br>
<br>
</div>
<div>http://mediaelementjs.com/<br>
<br>
</div>
<div>http://flowplayer.org/<br>
</div>
</section>
<section>
    <h2>IT’S THE FUTURE, GET WITH IT!</h2>
<div>
    <br>
</div>
<div>
<br>
</div>
<div>Questions ??</div>
</section>
</div>
