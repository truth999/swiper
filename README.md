<h1>Swiper - Mobile touch slider with hardware accelerated transitions</h1>
<h2>About</h2>
<p><strong>Swiper</strong> - is the <strong>free and ultra lightweight</strong> mobile touch slider with hardware accelerated transitions (where supported) and amazing native behavior. It is intended to use in mobile websites, mobile web apps, and mobile native apps. Designed mostly for iOS, but also works on Android and latest Desktop browsers. <strong>Swiper</strong> is created by <a href="http://www.idangero.us">iDangero.us</a></p>
<h2>Change Log</h2>
<h3>Swiper 1.5 - Updated on October 6, 2012</h3>
<ul>
	<li>A lot of major and minor fixes, core optimization</li>
	<li>Not it works in Internet Explorer 9 (without animation) and Internet Explorer 10</li>
	<li>Improved perfomance</li>
	<li>New "loop" mode with infinite scroll (see demo below)</li>
	<li>New carousel mode, now you can show few slides per slider container (see demo below)</li>
	<li>New "smart" pagination, looks fun with loop and carousel modes</li>
	<li>Now Swipers can be easily nested one into another (see demo below)</li>
	<li>Added ability to disable automatic slider resize on windows resize</li>
	<li>Updated CSS</li>
</ul>
<h3>Swiper 1.3 - Updated on April 15, 2012</h3>
<ul>
	<li>External functions swipeNext, swipePrev, swipeTo now return true or false.</li>
	<li><strong>.previousSlide</strong> property returns the index of previously displayed slide</li>
	<li>Added <strong>onSlideInitialize</strong> callback</li>
</ul>
<h3>Swiper 1.3 - Updated on April 2, 2012</h3>
<ul>
	<li>Added <strong>onSlideChangeStart</strong> callback</li>
	<li>Added <strong>onSlideReset</strong> callback</li>
	<li><strong>onSlideChange</strong> is renamed to <strong>onSlideChangeEnd</strong></li>
	<li>Now <strong>.swipeTo()</strong> method accepts 3 parameters - index <em>(number)</em>, speed <em>(number)</em> and runCallbacks <em>(boolean)</em></li>
	<li>Now <strong>.swipeTo()</strong> method will produce 'onSlideChangeStart' and 'onSlideChangeEnd' callback functions (if "runCallbacks" is not equal to "false")</li>
	<li>New <strong>mySwiper.destroy()</strong> method to release all events assigned by Swiper</li>
	<li>Fixed serious bug when using fluid (responsive) Swiper to re-calculate slides' position on window resize</li>
</ul>
<h3>Swiper 1.2 - Updated on March 31, 2012</h3>
<ul>
	<li>Improved mouse events to get the same behaviour as on touch devices</li>
</ul>
<h3>Swiper 1.1 - Updated on March 18, 2012</h3>
<ul>
	<li>Added <strong>autoPlay</strong> parameter to enable auto play</li>
    <li><strong>mySwiper.startAutoPlay()</strong> - external function to start auto play</li>
    <li><strong>mySwiper.startAutoPlay()</strong> - external function to stop auto play</li>
    <li>Optimized for usage as a fallback for upcoming <a href="http://www.idangero.us/sliders/s6/" target="_blank"><strong>"iDangero.us S6"</strong></a> 3D slider</li>
    <li>Added small plugin to use Swiper with <a href="http://zeptojs.com" target="_blank">Zepto.js</a></li>
</ul>
<h3>Swiper 1.0 - Initial release on March 15, 2012</h3>

<h2>Features</h2>
<ul>
	<li><p><strong>1:1 Touch movement</strong>. But this ratio can be configured</p></li>
	<li><p><strong>Touch emulation</strong>. This function will be useful if you are going to use Swiper on desktop sites. In this case Swiper will accept mouse events like touch events (click and drag to change slides)</p></li>
	<li><p><strong>Vertical/Horizontal</strong>. Swiper comes with 2 main modes - horizontal (for horizontal animation and horizontal swipes) and vertical (for vertical animation and vertical swipes)</p></li>
	<li><p><strong>Free Mode</strong>. When this mode enabled slides will not have fixed positions, like usual scroller (see demos bellow)</p></li>
	<li><p><strong>Rotation/resize adjustment</strong>. Swiper will be reinitialized after rotation of device</p></li>
	<li><p><strong>Responsive</strong>. Can be used with a width or/and height defined in percents, not fixed. Useful for usage on devices with a different resolutions</p></li>
	<li><p><strong>Scroll prevention</strong>. Swiper will prevent vertical scroll when you touch it in "horizontal" mode, and horizontal scroll in "vertical" mode</p></li>
	<li><p><strong>Resistant bounds</strong>. Swiper will increase resistance when you try to swipe it over than most left and most right positions (most top and most bottom for "vertical" mode)</p></li>
	<li><p><strong>Built-in pagination control</strong>. Can be disabled</p></li>
	<li><p><strong>Auto Play</strong>. Just set the delay and Swiper will change the slides automatically untill you touch it.</p></li>
	<li><p><strong>Loop mode</strong>. In this mode you will get infinite scrolling and first slides will repeat after last ones. <span class="new-in">New in 1.5</span></p></li>
	<li><p><strong>Carousel mode</strong>. Swiper allows you to set numbers of slides you want to display at the same time on slider's container. <span class="new-in">New in 1.5</span></p></li>
	<li><p><strong>Nested Swipers.</strong> You can insert one Swiper into slide of different Swiper, for example vertical into horizontal. <span class="new-in">New in 1.5</span></p></li>
	<li><p><strong>Any HTML</strong>. You can put any HTML content inside of slide, not only images</p></li>
	<li><p><strong>Rich API</strong>. Swiper comes with very rich API. It allows to create your own pagination, "next" and "previous" buttons and comes with 4 callbacks - onTouchStart, onTouchMove, onTouchEnd, onSlideSwitch </p></li>
	<li><p><strong>Flexible configuration</strong>. Swiper accepts a lot of parameters on initialization to make it much flexible as possible. You can configure animation speed, mode (vertical or horizontal), free mode, enable/disable pagination, touch ratio, etc.</p></li>
	<li><p><strong>Hardware accelerated</strong>. Swiper uses hardware accelerated technics (where supported) to achive ultra smooth animation and perfomance, especially on iOS devices.</p></li>
	<li><p><strong>Awesome compatibility</strong>. Swiper compatible and tested with: Mobile Safari (tested on iOS5), Android 2.1+, latest desktop versions of Google Chrome, Safari, Firefox, Internet Explorer 10 and Opera. It also works in Internet Explorer 9 but without animation.</p></li>
	<li><p><strong>Standalone</strong>. Swiper doesn't require any JavaScript libraries like jQuery, it makes Swiper much more smaller and faster. So it can be safely used with such libraries as jQuery, jQuery Mobile, jQTouch, etc.</p></li>
	<li><p><strong>Ultra lightweight</strong>. Only 3.2 KB minified and gzipped</p></li>
</ul>
<p><em><strong>With all these features you can build amazing touch interfaces and apps with awesome native behavior.</strong></em></p>

<h2>Demos & Usage</h2>
<p><a href="http://www.idangero.us/sliders/swiper/">http://www.idangero.us/sliders/swiper/</a></p>

<h2>License</h2>
<p>Swiper is licensed under GPL & MIT</p>
