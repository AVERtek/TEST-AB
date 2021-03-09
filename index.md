### Immersive 3D Tour Below <!-- Loads <model-viewer> for old browsers like IE11: -->
### Augmented Reality 4D Tour on Mobile <!-- Loads <model-viewer> for old browsers like IE11: -->
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js">
  </script>

  <!-- The following libraries and polyfills are recommended to maximize browser support -->  
  <!-- REQUIRED: Web Components polyfill to support Edge and Firefox < 63 -->
  <script src="https://unpkg.com/@webcomponents/webcomponentsjs/webcomponents-loader.js"></script>

  <!-- OPTIONAL: Intersection Observer polyfill for better performance in Safari and IE11 -->
  <script src="https://unpkg.com/intersection-observer/intersection-observer.js"></script>

  <!-- OPTIONAL: Resize Observer polyfill improves resize behavior in non-Chrome browsers -->
  <script src="https://unpkg.com/resize-observer-polyfill/dist/ResizeObserver.js"></script>

  <!-- OPTIONAL: Fullscreen polyfill is required for experimental AR features in Canary -->
  <!--<script src="https://unpkg.com/fullscreen-polyfill/dist/fullscreen.polyfill.js"></script>-->

  <!-- OPTIONAL: Include prismatic.js for Magic Leap support -->
  <!--<script src="https://unpkg.com/@magicleap/prismatic/prismatic.min.js"></script>-->

<model-viewer camera-controls camera-orbit="0deg 45deg 10m" id="annotation" loading="eager" src="Models/Bahay_1 bed Apartment_02_experiment.glb" ar="" ar-modes="scene-viewer webxr quick-look" ios-src="usdz_bahay_1_bed_apartment_02_experiment___1612219828086.usdz" alt="Alexan Bahay" auto-rotate-delay="0" ar-scale="auto" camera-controls="" style="width: 95%; height: 500px" exposure="0.5"> <button slot="hotspot-hand" data-position="-0.6577432407752888m 0.5435449945961643m" data-normal="0.0958066931824225m -0.169619142622571m 0.9808416916085048m"<div id="annotation">This hotspot disappears completely</div></button> <button slot="ar-button" style="background-color: white; border-radius: 8px; border: 1 px solid black; position: absolute; top: 20px; right: 20px; ">
      👋 AR Click Here
  </button>
</model-viewer>
<script>
/**
* Function that registers a click on an outbound link in Analytics.
* This function takes a valid URL string as an argument, and uses that URL string
* as the event label. Setting the transport method to 'beacon' lets the hit be sent
* using 'navigator.sendBeacon' in browser that support it.
*/
var getOutboundLink = function(url) {
  gtag('event', 'click', {
    'event_category': 'outbound',
    'event_label': url,
    'transport_type': 'beacon',
    'event_callback': function(){document.location = url;}
  });
}
</script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>
<script src="{{ "/assets/js/scale.fix.js" | relative_url }}"></script>

<!-- Loads <model-viewer> for modern browsers: -->
 <script type="module" src="https://unpkg.com/@google/model-viewer/dist/model-viewer.js">
  </script>
<script nomodule="" src="https://unpkg.com/@google/model-viewer/dist/model-viewer-legacy.js"></script>

---

### <a href="https://avertek.net/xr-now" onclick="getOutboundLink('https://avertek.net/xr-now'); return false;">Learn More About AVERtek's XR-NOW</a> 
  <br><br>
