<html>
    <head>
        <title></title>
    </head>
    <body>
        <h1>
            HTML5 Video
        </h1>
        <h2>
            Why we need it ? (pros)
        </h2>
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
        <h2>
            Elements
        </h2>
        <p class="p1" style="text-align: left;"></p>
        <ul>
            <li>
                <span style="font-size: 24px;"><b>autoplay*</b></span>
            </li>
            <li>
                <span><font style="font-size: 24px;"><b>preload</b></font></span>
            </li>
            <li style="list-style: none; display: inline">
                <ul>
                    <li>
                        <b style="background-color: rgba(255, 255, 255, 0.0470588); font-size: 24px;">none</b> <span style="background-color: rgba(255, 255, 255, 0.0470588); font-size: 24px;">- Hints to the browser that the user likely will not watch the video,&nbsp;</span>
                    </li>
                    <li>
                        <b style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);">metadata</b> <span style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);">- Hints to the browser that the user is not expected to need the video, but that fetching its metadata (dimensions, first frame, track list, duration, and so on) is desirable.</span>
                    </li>
                    <li>
                        <b style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);"><span class="Apple-tab-span">&nbsp;</span>auto</b> <span style="font-size: 24px; background-color: rgba(255, 255, 255, 0.0470588);">- Hints to browser that optimistically downloading the entire video</span>
                    </li>
                </ul>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>poster :&nbsp;</b></font> <span style="font-size: 24px;">Provides an image to show before the video loads</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>controls* :&nbsp;</b></font> <span style="font-size: 24px;">Shows the default video controls (play, pause, etc)</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>height &amp; width &nbsp;:&nbsp;</b></font> <span style="font-size: 24px;">Sets the width and height of the video in CSS pixels</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>loop* :&nbsp;</b></font> <span style="font-size: 24px;">Tells the browser to automatically loop the video</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>muted* :&nbsp;</b></font> <span style="font-size: 24px;">Mute s the audio from the video</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>Video :&nbsp;</b></font> <span style="font-size: 24px;">source src="../video/movie.webm" type="video/webm</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>Audio :&nbsp;</b></font> <span style="font-size: 24px;">audio src="audio.mp3" controls preload/audio</span>
            </li>
            <li>
                <font style="font-family: inherit; font-style: inherit; font-variant: inherit; font-weight: inherit; font-size: 24px;"><b>Subtitle :&nbsp;</b></font> <span style="font-size: 24px;">track src="../video/subtitles_en.vtt" label="English subtitles" kind="subtitles" srclang="en</span>
            </li>
            <li style="list-style: none">
                <font style="font-size: 32px;"><b>Video</b></font> <font style="font-size: 24px;">&nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &lt;source src="../video/movie.webm" type="video/webm"&gt;</font>
            </li>
        </ul>
        <h2>
            HTML5 Video Sources
        </h2>
        <div>
            <ul>
            <div style="text-align: left;">
                <li>
                    <font style="font-size: 24px;">MP4 = MPEG 4 files with H264 video codec and AAC audio codec</font>
                </li>
                <li>
                    <font style="font-size: 24px;">WebM = WebM files with VP8 video codec and Vorbis audio codec</font>
                </li>
                <li>
                    <font style="font-size: 24px;">Ogg/Ogv/Ogm = Ogg files with Theora video codec and Vorbis audio codec</font>
                </li>
            </div>
        </ul>
        </div>
        <section>
            <h4 style="text-align: left;">
            Browser Support
            </h4>
            <blockquote style="margin: 0 0 0 40px; border: none; padding: 0px;">
                <div>
                    <table class="reference notranslate" style="font-variant: normal; font-size: 13px; width: 821px; color: rgb(64, 64, 64); font-style: normal; background-color: rgb(255, 255, 255);">
                        <tbody>
                            <tr style="background-color: rgb(246, 244, 240);">
                                <th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 199px;">
                                    Browser
                                </th>
                                <th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 198px;">
                                    MP4
                                </th>
                                <th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 198px;">
                                    WebM
                                </th>
                                <th style="text-align: center; font-size: 12px; color: rgb(255, 255, 255); background-color: rgb(85, 85, 85); border: 1px solid rgb(85, 85, 85); padding: 3px; vertical-align: top; width: 198px;">
                                    Ogg
                                </th>
                            </tr>
                            <tr>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    Internet Explorer
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    NO
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    NO
                                </td>
                            </tr>
                            <tr style="background-color: rgb(246, 244, 240);">
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    Chrome
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                            </tr>
                            <tr>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    Firefox
                                </td>
                                <td style="font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    <div style="text-align: center;">
                                        NO
                                    </div>
                                    <div style="text-align: center;">
                                        <strong><strong>Update:</strong>&nbsp;Firefox 21 running on Windows 7, Windows 8, Windows Vista, and Android now supports MP4</strong>
                                    </div>
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                            </tr>
                            <tr style="background-color: rgb(246, 244, 240);">
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    Safari
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    NO
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    NO
                                </td>
                            </tr>
                            <tr>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    Opera
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    NO
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                                <td style="text-align: center; font-size: 13px; border: 1px solid rgb(212, 212, 212); padding: 7px 5px; vertical-align: top;">
                                    YES
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </blockquote>
            <div style="text-align: left;"></div>
        </section>
        <section>
            <section>
                <h2 style="text-align: center;">
                    Video Codecs &amp;&nbsp;<span style="font-size: 75.96px;">Encoding Video</span>
                </h2>
                <div>
                    <p>
                        <font style="font-size: 32px;">H.264</font>
                    </p>
                    <p>
                        <font style="font-size: 32px;">OGG THRORA</font>
                    </p>
                    <p>
                        <font style="font-size: 32px;">VP8(WEBM)</font>
                    </p>
                    <p>
                        <a href="http://techcrunch.com/2014/01/02/googles-vp9-video-codec-gets-backing-from-arm-nvidia-sony-and-others-gives-4k-video-streaming-a-fighting-chance/?utm_campaign=fb&amp;ncid=fb"><font style="font-size: 32px;">VP9 - Just released</font></a>
                    </p>
                </div>
            </section>
            <section>
                <h2>
                    How to Specify Codec&nbsp;
                </h2>
                <div>
                    <div>
                        <ul>
                            <li style="text-align: left;">
                                <span style="font-size: 24px; text-align: center;">&lt;source src="path/to/myvideo.mp4" type='video/mp4; codecs="avc1.42E01E, mp4a.40.2"'&gt;</span>
                            </li>
                            <li style="text-align: left;">
                                <span style="font-size: 24px; text-align: center;">&lt;source src="path/to/myvideo.ogv" type='video/ogg; codecs="theora, vorbis"'&gt;</span>
                            </li>
                            <li style="text-align: left;">
                                <span style="font-size: 24px; text-align: center;">&lt;source src="../video/movie.webm" type='video/webm codecs="vp8, vorbis"'&gt;</span>
                            </li>
                        </ul>
                    </div>
                </div>
            </section>
        </section>
        <section>
            <h2>
                ADAPTIVE sTEAM HTML5
            </h2>
            <div>
                AVS - adobe Scene7 - Scene7 player
            </div>
            <div>
                <div style="font-size: 36.11820602416992px; font-style: normal; font-variant: normal;">
                    m3u8 - Safari
                </div>
                <div>
                    <span><font style="font-size: 24px;">you can't simply point your video tag to a local .m3u8, but rather, you must point it to an .m3u8 file that is being served over HTTP.</font></span>
                </div>
                <div style="font-size: 36.11820602416992px; font-style: normal; font-variant: normal;"></div>
            </div>
        </section>
        <section>
            <h2>
                Video Converter
            </h2>
            <div>
                <div>
                    <a href="http://www.mirovideoconverter.com/">Miro Video Converter</a>
                </div>
                <div>
                    <a href="http://handbrake.fr/">Handbrake</a>
                </div>
                <div>
                    <a href="http://www.squared5.com/">MPEG Streamclip ()</a>
                </div>
                <div>
                    <a href="http://firefogg.org/">Firefogg</a>
                </div>
            </div>
        </section>
        <section>
            <h2>
                Good Video Player in market&nbsp;
            </h2>
            <div>
                <font style="font-size: 32px;">http://www.jwplayer.com</font> http://www.videojs.com
            </div>
            <div>
                http://mediaelementjs.com
            </div>
            <div>
                http://flowplayer.org
            </div>
        </section>
        <section>
            <h2>
                IT’S THE FUTURE, GET WITH IT!
            </h2>
            <div>
                Questions ??
            </div>
        </section>
    </body>
</html>
