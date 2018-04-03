# rc24-april-fools
April Fool's 2018 joke for RiiConnect24.

The player.swf (ew! Flash) file can be used on the Wii Internet Channel in order to play videos in .flv format, since the Wii unfortunately lacks an HTML5 video player. Here's a template for the embed code:

```html
<div id="swfcontent">
  <object type="application/x-shockwave-flash" data="player.swf" width="384" height="256" id="flvplayer" style="visibility: visible;">
    <param name="id" value="flvplayer">
    <param name="wmode" value="transparent">
    <param name="allowFullScreen" value="false">
    <param name="allowScriptAccess" value="sameDomain">
    <param name="quality" value="high">
    <param name="flashvars" value="filename=http://link.to/flv/file/here">
  </object>
</div>```
